## basicjoin

### Instructions

Write a function that returns the concatenation of all the `string` of a slice of `string` passed in argument.

### Expected function

```go
func BasicJoin(elems []string) string {

}
```

### Usage

Here is a possible program to test your function :

```go
package main

import (
	"fmt"
	"piscine"
)

func main() {
	elems := []string{"Hello!", " How", " are", " you?"}
	fmt.Println(piscine.BasicJoin(elems))
}
```

And its output :

```console
$ go run .
Hello! How are you?
$
```
