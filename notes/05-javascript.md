# JavaScript

<!-- SECTION Array Methods -->
  let variable = array.find(object => conditional) --> finds the first object that meets condition
  let variable = array.findIndex(object => conditional) --> returns the object's index that meets condition
  let variable = array.filter(object => conditional) --> creates array with all objects that meet condition
  let variable = array.sort((a, b) => a.key - b.key) --> creates array that sorts objects based on key
  let variable = array.map(object => operation) --> combines all content with said operation
  let variable = array.shift() --> removes first item from array and stores it
  let variable = array.pop() --> removes last item from array and stores it
  let variable = array.slice(firstPosition, lastPosition) --> returns section from firstPosition to last
  let variable = array.includes(variable) --> returns a boolean if array contains variable
  let variable = array.join(between each item) --> creates a string from array
  let variable = array.reverse() --> reverses array order
  array.forEach(object => {do something to each object}) --> changes each object
  array.unshift(variable) --> puts variable at beginning of array
  array.push(variable) --> pushes variable to end of array
  array.splice(index, number of elements, replace) --> removes value at said index and can replace
  ...array --> removes brackets from array

<!-- SECTION Object Methods -->
  Object.values(object) --> returns values in an array
  Object.keys(keys) --> returns keys in an array
  ...object --> removes curly braces from object

<!-- SECTION Math Methods -->
  Math.random()
  Math.floor(number) --> rounds number down
  Math.ceil(number) --> rounds number up

<!-- SECTION String Methods -->
  let variable = string.toUpperCase() --> uppercase all character
  let variable = string.toLowerCase() --> lowercase all character
  let variable = string.split(when to split) --> breaks up objects into array

<!-- SECTION Number Methods -->
  variable.toString() --> turns number to strings
  variable.toFixed(number) --> adds required amount of numbers after decimal

<!-- SECTION Window Methods -->
  window.alert(text) --> window with text
  window.confirm(text) --> allows window to have option
  window.prompt(text) --> allows user to type in window
  window.location.reload(text) --> refreshes page
  window.event.preventDefault() --> prevents the default action

<!-- SECTION Date Methods -->
  new Date('date') --> returns specified date else current date
  Date.toLocaleString() --> formats date and time into standard format
  Date.toLocaleDateString() --> formats just date into standard format
  Date.toLocaleTimeString() --> formats just time into standard format

<!-- SECTION Special Functions -->
  setInterval(function or {() => code}, ms) --> runs function repeatedly every ms
  let function = (condition) => {} --> equivalent to a function
  let variable = condition ? val1 : val2 --> if true return var1 if false return val2

<!-- SECTION Errors -->
  try {
    throw new Error()
  } catch (error) {
    runs when error is thrown
  }

  <!-- SECTION HTML Editor -->
  let tag = document.tag
    tag.style.property = ''
  let elem = document.getElementById('id') --> gets the id of teg
    elem.querySelector('tag'). gets said tag within the elem 
    elem.innerHTML('HTML') --> replaces HTML within tag with HTML
    elem.innerText('string') --> replaces text within tag with string
    elem.setAttribute('attribute', 'value') --> adds attribute to tag with set value
    elem.removeAttribute('attribute') --> removes attribute from tag
    let class = elem.classList --> gets class list within tag
      class.add('class') --> adds a class to tag
      class.remove('class') --> removes a class from tag