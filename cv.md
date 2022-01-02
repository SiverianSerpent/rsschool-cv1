# Denis Kopych 

![Image](https://i.ibb.co/k4CnDV0/IMG-9414.jpg)

### Junior Frontend Developer
___

### Contact information:
**Phone:** +38 063 5667966
**E-mail:** denis.kopich@gmail.com
**Telegram:** @siverianserpent

___

### Briefly About Myself:
I am 22 years old, living in Ukraine Chernihiv city. I have been studying at Chernihiv National University of Technology for (the past) 4 years. After my education I realized that I want to do something another in my lifetime. And that's why i started learning programming: viewing YouTube, reading books about it. After few month I found the RS-School Courses, and now I'm here.

___
### Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code, 
* Adobe Photoshop

___
### Code Example:
**Peak array index KATA from CODEWARS:** *Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*
```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```

___
### Courses:
* JavaScript Manual on learnjavascript.ru (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

___
### Languages:
* English - Intermediate
* Russian - Native
* Ukrainian - Native


