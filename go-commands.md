# Go Commands

```

$ go help 

$ go mod init example.com/greetings # create package

$ go run . # Run package

$ go mod tidy # Add new module requirements and sums.


$ go mod edit -replace example.com/greetings=../greetings

$ go test # For testing

$ go test -v # -v flag to get verbose output that lists all of the tests and their results.

$ go build # compiles the packages, along with their dependencies, but it doesn't install the results.

$ go list -f '{{.Target}}' # Discover the Go install path, where the go command will install the current package.



```
