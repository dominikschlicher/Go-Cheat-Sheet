# Go Cheat Sheet


For shorter code samples I skip package declaration and imports

<!-- code -->
```go
package main

import "fmt"
```

## Basic Stuff

- GO-Applications starts always in the package `main`
- export package elements by capital letter at the beginning
- var and init

## Variables and constants

```go
var a,b int = 3,6 // initializing of multiple variables
c := "short"      // shorthand declaration and initializing (typed by its value)
const foo = "ab"  // a constant
```

## Data types
### Basic data types
`bool` \n
`string`\n
`int`	  `int8`  `int16`		 `int32`	  `int64`\n
`uint`	`uint8`	`uinit16`	 `unint32` 	`uint64` 	`uintptr`\n
`byte` =`uint8`\n
`rune` =`int32`\n
`float32` `float64`\n
`complex64` `complex128`\n

### Collections (Array, Slice & Map)

- Arrays have a fixed size
```go
myArray := [3]int{2,3,4}  // init a array of 3 elements of type int
myArray[3] = 100          // assign the 3rd element of myArray with 100
len(myArray)              // length of my array
var myArray = [2][2]int   // init a 2D array
```

- Slice have a dynamic size

### Pointers

## Control Structures
### `if`-Statement
### `switch`-Statement
### `for`-loop

## Functions

## Methods & Structs


## Topic I



## Topic II



## Topic III
