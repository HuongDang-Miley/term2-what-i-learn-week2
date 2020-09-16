# Wednesday
## Object Methods
Object.keys: Create an array that contain all keys in the object
Object.values: Create an array that contain all value in the object
Object.entries: Create an array that contain entries from an object
Object.fromEntries: Create an Object from an Array of entries

let fruits = {
    apple: 20,
    orange: 50,
    pear: 10,
}


const fruitName = Object.keys(fruits)
fruitName
const quantity = Object.values(fruits)
quantity
const fruitEntries = Object.entries(fruits)
fruitEntries
const fruits2 = Object.fromEntries(fruitEntries)
fruits2
