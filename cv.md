# Natallia Motuz
***Junior Software Engineer***

**Adress:** Minsk, Belarus   
**Email:** natalia.motuz@gmail.com   
**Phone:** +375 29 3965969   
**Telegram:** @natalkamotuz

## Summary of Qualifications
>I am in the earlier stage of my journey as a software developer, have a small yet delightful portfolio of launched projects, and I’am hungry to learn more.

## Technical skills
- HTML - 5/10
- CSS - 4/10
- JavaScript - 2/10
- ReactJS - 1/10

>As a junior developer, I am able to craft clean and correct code with some supervision and guidance. Also I can execute on well specified or documented tasks by breaking them down into reasonable subtasks, and complete them.

## Code Example
``` javascript
module.exports = function solveEquation(equation) {
    const parsedEquation = equation.split(' ');
    const op1 = parsedEquation[3];
    const op2 = parsedEquation[7]; 
    const a = parsedEquation[0];
    const b = parsedEquation[4] * (op1 === '-' ? - 1 :1 );
    const c = parsedEquation[8] * (op2 === '-' ? - 1 :1 );
    const D = Math.sqrt(b * b - 4 * a * c);
    const x1 = Math.round((-b + D) / (2 * a));
    const x2 = Math.round((-b - D) / (2 * a));
  
    return [x1, x2].sort(function (a, b) {return a - b};
};
```

## Education
- *2008-2010* MA in Belarusian Linguistics, University of Warsaw, Poland
- *2008-2010* BA in Visual Cultural Studies, University of Warsaw, Poland
- *2003-2006* Belarusian State Pedagogical University, Belarusian Linguistics

## Informal Education
**Basics of Computer Science**, IT-Academy, 2017

**Online courses:** Basic course in Java programming, The Basics of Object Oriented Programming, Database, Regular expressions.

## English skills
I have successfully completed a 160-hours General English course at the **Intermediate level** in Streamline Language School.
