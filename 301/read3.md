## React Docs - lists and keys ..

**What does .map() return ?**

- return new array with modified data .

**If I want to loop through an array and display each value in JSX, how do I do that in React ?**

- You can build collections of elements and include them in JSX using curly braces {}.
-  we loop through the elements array using the JavaScript map() function.

**Each list item needs a unique ____.**

- Key .

**What is the purpose of a key ?**

- Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

## The Spread Operator ..

**What is the spread operator?**

- The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functionβs arguments.

**List 4 things that the spread operator can do.**

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments

**Give an example of using the spread operator to combine two arrays.**

- using the β¦ spread operator is a convenient way to copy an array or combine arrays, and it can even add new items.
> const fruits = ['π','π','π','π','π']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "π", "π", "π", "π", "π" ]
fruits[0] = 'π'
console.log(...[...fruits,'...',...moreFruits]) //  π π π π π ... π π π π π

**Give an example of using the spread operator to add a new item to an array.**

- the spread operator can add an item to an another array with a natural, easy-to-understand syntax.
> const fewFruit = ['π','π','π']
const fewMoreFruit = ['π', 'π', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "π", "π", "π", "π", "π" ]

**Give an example of using the spread operator to combine two objects into one.**

- he spread syntax is useful for combining the properties and methods on objects into a new object.
> const objectOne = {hello: "π€ͺ"}
const objectTwo = {world: "π»"}
const objectThree = {...objectOne, ...objectTwo, laugh: "π"}
console.log(objectThree) // Object { hello: "π€ͺ", world: "π»", laugh: "π" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("π".repeat(5))}}
objectFour.laugh() // πππππ



