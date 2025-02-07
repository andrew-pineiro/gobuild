# gobuild
Single build file for golang projects

Simple type `go build build.go` and run the executable. 

## Options
--arch string
        Architecture to build application under (default "amd64")
--config string
    Configuration to build the project under (Debug/Release) (default "debug")
--dir string
    Directory with main function for build (default ".")
--name string
    Name of the project (default "main")
--os string
    Operating systme to build application under (default "linux")
--output string
    Directory to output  build files (default "./bin")
--publish
    Enable publish mode in build
