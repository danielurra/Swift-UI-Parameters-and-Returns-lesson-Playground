# SwiftUI Parameters & Returns lesson Playground
![Screenshot 2024-03-31 at 5 12 34 AM](https://github.com/danielurra/Swift-UI-Parameters-and-Returns-lesson-Playground/assets/51704179/7fbd50d3-7b9a-471f-a813-23bdf98447a8)

## Parameters are Potential, Arguments are Actual
[Mnemoic01](https://github.com/danielurra/mnemonic01)
## Grab the code
```swift
// #### Input values into a function ####
func addIntegers (entero1: Int, entero2: Int){
    print(entero1 + entero2)
}
// now let's call our function
addIntegers(entero1: 3, entero2: 5)
addIntegers(entero1: 1, entero2: 100)
addIntegers(entero1: -10, entero2: 20)
// ### Get out (extract) value from the function - introducing RETURNS
func addNumbers (num1: Int, num2: Int) -> Int {
//    print(num1 + num2)
//    return 7
    return num1 + num2
}
// now let's call our function
addNumbers(num1: 3, num2: 3)
addNumbers(num1: 6, num2: 6)
// return is different that print
// You can pass the function to a function
addNumbers(num1: 11, num2: addNumbers(num1: 11, num2: 11))
// You can create a variable equal to the result of the function
var yearsInUSA = addNumbers(num1: 3, num2: 2)
```
