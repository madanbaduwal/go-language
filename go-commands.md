# Go Commands

```

$ go help 

$ go mod init example.com/greetings # create package, generate go.mod file inside your module folder for module

$ go run . # Run package

$ go mod tidy # Add new module requirements and sums.


$ go mod edit -replace example.com/greetings=../greetings

$ go test # For testing

$ go test -v # -v flag to get verbose output that lists all of the tests and their results.


While the go run command is a useful shortcut for compiling and running a program when you're making frequent changes, it doesn't generate a binary executable.

$ go build # compiles the packages, along with their dependencies, but it doesn't install the results.

$ go list -f '{{.Target}}' # Discover the Go install path, where the go command will install the current package.

$ go install


$ go get golang.org/x/example # to download a package


$ go work init ./hello # Initialize the workspace, generate go.work file in your workspace folder for your workspace



```

**go install vs go mod tidy vs go get vs go mod download**



go install is used to install a binary, not a package

go get to download a package

go mod tidy scans your project and updates the go.mod file and downloads all dependencies mentioned in the go.mod file

go mod download only downloads the dependencies from go.mod, without modifications of the go.mod file

