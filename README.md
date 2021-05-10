# Array-Methods

.Map()
map method does a function once for each element in an 
array and creates a new array without modifying the original. 
*time complexity of O(n)
Examples:
console.log('Map Method')
console.log(array.map(element => element * 2))
console.log(arrayTwo.map(element => element.toUpperCase()))



.reduce()
reduce method does a function for each element in an array, 
reducing it to a single value. 
*time complexity of O(n)
Examples:
console.log('Reduce Method')
console.log(array.reduce((acc, val) => acc * val, 1))
console.log(arrayTwo.reduce((acc, val) => acc + val))



.filter()
filters the array using a function provided given that it is true. 
*time complexity of O(n)
Examples:
console.log('Filter Method')
console.log(array.filter(element => element % 2 === 0))
console.log(arrayTwo.filter(element => arrayTwo.indexOf(element) !== arrayTwo.lastIndexOf(element)))



.forEach()
method does a function once for each element in an array, 
modifies the original array. 
*time complexity of O(n)
Examples:
console.log('ForEach Method')
array.forEach(element => { console.log(element - 1) })
arrayTwo.forEach(element => { console.log(element.toUpperCase()) })



.sort() 
method sorts the array, modifying it. If not specified, it will modify
by the unicode values. 
*time complexity of O(n * log n)
Examples:
console.log('Sort Method')
console.log(array.sort((a,b) => b - a))
console.log(arrayTwo.sort((a,b) => b - a))



.slice() 
method slices the array/string from one point to
another and returns the sliced part. 
*time complexity of O(n)
Examples:
console.log('Slice Method')
console.log(array.slice(2,4))
console.log(arrayTwo.slice(1,2))



.pop() 
method removes the last element in an array 
and returns that element. *
time complexity of O(1)
Examples:
console.log('Pop Method')
console.log(array.pop())
console.log(arrayTwo.pop())



.shift()
method removes the first element in an array and returns
that element. 
*time complexity of O(n)
Examples:
console.log('Shift Method')
console.log(array.shift())
console.log(arrayTwo.shift())



.push()
method adds an element to the end of an array
and returns the new length.  
*time complexity of O(1)
Examples:
console.log('Push Method')
console.log(array.push(5))
console.log(arrayTwo.push('!','!'))



.unshift()
unshift method adds an element to the beginning of an array
and returns the array. 
*time complexity of O(n)
Examples:
console.log('unshift Method')
console.log(array.unshift(0))
console.log(arrayTwo.unshift('!'))



.includes()
includes method is a boolean that checks if an
element exists in an array. 
*time complexity of O(n)
Examples:
console.log('includes Method')
console.log(array.includes(4))
console.log(arrayTwo.includes('l'))



.indexOf()
indexOf method looks for the index of the target element, 
returns -1 if not found. 
*time complexity of O(n)
Examples:
console.log('indexOf Method')
console.log(array.indexOf(3))
console.log(arrayTwo.indexOf('e'))



.every()
every method boolean that checks if every element passes a test.
*time complexity of O(n)
Examples:
console.log('every Method')
console.log(array.every(element => typeof(element) === 'number'))
console.log(arrayTwo.every(element => typeof(element) === 'boolean'))















