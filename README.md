# Go Setup

## Prerequisites
1. Go runtime and libs up and running on machine ([Instaling go](https://golang.org/doc/install))
1. Git installed and configured
 
## Getting Started (Hello World)

### Creating GoLang project basic folders

```
mkdir go-setup
cd go-setup
go mod init github.com/myname/my-app
mkdir -p cmd/cli
```

On folder cmd/cli create a file called **main.go** with the content above:

```
package main

import "fmt"

func main()  {
	fmt.Println("Hello!")
}
```

### Build an run

```
go build -o releases/my-app cmd/cli/main.go
./releases/my-app 
Hello!
```

### DDD Aprouch

//TODO: Explanation about DDD and Clean Architecture

//TODO: Talk about the folder structure

## A simple cli

```
go get -u github.com/spf13/cobra/cobra
```
