## atoibase

### Instructions

Write a function that takes a `string` number and its `string` base in parameters and returns its conversion as an `int`.

If the base is not valid it returns `0`.

Validity rules for a base :

- A base must contain at least 2 characters.
- Each character of a base must be unique.
- A base should not contain `+` or `-` characters.

String number must contain only elements that are in base.

Only valid `string` numbers will be tested.

The function **does not have** to manage negative numbers.

### Expected function

```go
func AtoiBase(s string, base string) int {

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
	fmt.Println(piscine.AtoiBase("125", "0123456789"))
	fmt.Println(piscine.AtoiBase("1111101", "01"))
	fmt.Println(piscine.AtoiBase("7D", "0123456789ABCDEF"))
	fmt.Println(piscine.AtoiBase("uoi", "choumi"))
	fmt.Println(piscine.AtoiBase("bbbbbab", "-ab"))
}
```

And its output :

```console
$ go run .
125
125
125
125
0
$
```
