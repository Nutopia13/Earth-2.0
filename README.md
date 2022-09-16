# Earth-2.0

![](./public/Screenshot%202022-09-16%20at%2012-02-02%20Earth%202.0.png)

This is a random generator project which is themed around a possible habitat planets.

Live: https://nutopia13.github.io/Earth-2.0/

Mobile/Desktop

## General Information

The intention of this project is to practice using git, github, markdown and visual studio code to create a project outside of the codeacademy environment.

## Programming Tools

- Javascript
- Node v14.18.1
- HTML/CSS
- Git
- Visual Studio Code v1.61.1

## Implemented

- Generated random numerical values for each planet
- Generated random numerical value based on length of each planet list. Fully scaleble
- Responsive Design. Mobile-first approach
- Mouse Tracker Function
- First time used AddEventListener

### Setup
- vite Development Environment 
- Vanilla JS

## Logic

- Created an object 'planets' which contain 15 key:value pairs. As a value -> an array with title[0] and description[1]
- Images are in the different object 'pics'contains sigle array where second part of the img path was implemented. Creted loop which iterate though an array and add first parts of the path. 

```javascript
const pics = [
  "5466 4.svg",
  "5466 5.svg",
  "5466 6.svg",
  .....
];

document.canvas.src = "./assets/" + pics[generateRandomNumber];
```

- The most struggle was to divide Headind, Description and Img elements, while they are in the object. So came up with a solution: Changed to one object and several keys who hold title as a first index and description as a second index. Then looped and .push to new array



Would appreciate feedback and improvements
