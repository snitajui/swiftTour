# swiftTour
This includes the solutions of the short quiz of the official book of Swift .
// 1..“Create a constant with an explicit type of Float and a value of 4”
let explicitFloat : Float = 4.00


let label = "The width is "
let width = 94
let widthLabel = label + String(width)
//2..“Try removing the conversion to String from the last line. What error do you get”
// a string and an integer cannot be added by "+" operator

//3.. “Use \() to include a floating-point calculation in a string and to include someone’s name in a greeting.”

let number : Float = 3.45
let height = "the height of the tower is \(number)"

let greetings = "Good Morning"
let greetToHim = "sir , \(greetings)"

var shoppingList = ["catfish", "water", "tulips"]
shoppingList[1] = "bottle of water"
shoppingList.append("blue paint")
print(shoppingList)
// creating empty array

