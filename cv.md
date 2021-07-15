# Alexey Krylov
![photo](Aleksey_Krylov_.png)  

## Contacts
email: turn2river@gmail.com   
discord: ADLINN#9697

## About
About me

## Skills
### Tech stack
- Basic JavaScript
- Basic Node.js
- HTML
- CSS, SCSS
- BEM

### Tools
- VS Code
- GIT, SVN
- Figma 
- Photoshop, Illustrator 

### TeamWork
- Agile, Scrum
- Jira, Confluence

## CodeExamples

### Codewars  

### Task
You will be given an array of numbers. You have to sort the odd numbers in ascending order while leaving the even numbers at their original positions.  

### Solution
```js 
function sortArray(array) {

 let oddNums = array.filter((x) => x % 2).sort((a, b) => a - b);
 return array.map((x) => (x % 2 ? oddNums.shift() : x));

 };
```  
  
### Task
Create a function that takes one positive three digit integer and rearranges its digits to get the maximum possible number. Assume that the argument is an integer. Return `null`  if the argument is not valid.

### Solution
```js
let maxRedigit = function(num) { 

 return num < 100 || num > 999 ? null : +num.toString().split("").map((x) => +x).sort((a, b) => b - a).join(''); 

};
```

## Personal study projects
[TheVikings TVseries website project(GitHub)](https://github.com/turn2river/vikings)  
[TheVikings TVseries website project(hosted)](http://shiny-grandfather.surge.sh/)

[InteriorShop online store project(Github)](https://github.com/turn2river/InteriorShop)	   
[InteriorShop online store project(hosted)](http://interiorshop-krylov.surge.sh/)


## Education
- RS school 
- GeekBrains(1st and 2nd quarter of webdev course)
- Moscow State Print University
	-  almost completed higher education(haven't done the diploma)
	-  quit due to life circumstances

## English level
### Intermediate(B1+)
- Graduated from school with in-depth study of the English language. 