# rsschool-cv

# Pavel Yudenka

## Frontend developer

## Contact
* Minsk, Belarus
* +37529-306-75-09
* [p.yudenko@gmail.com](mailto:p.yudenko@gmail.com)

## Socials
* [https://www.linkedin.com/in/PavelYudenka](https://www.linkedin.com/in/PavelYudenka/)
* [https://github.com/Pavelvl21](https://github.com/Pavelvl21)

## About me
Hello! I'm Pavel. I work in the field of e-commerce as a Lead Procurement Manager. In my spare time I study javascript development. There are 4 projects in my portfolio. Plans for the near future to write a pet-project "Online-store". I'm always looking for a new knowledge. I like to work in a team and for the result.

## Experience
04.2022 - Present
### Training in the online school of programming "Hexlet"
* Study project: [**"Brain Games"**](https://github.com/Pavelvl21/frontend-project-lvl1) - is a set of five console games;  
[https://github.com/Pavelvl21/frontend-project-lvl1](https://github.com/Pavelvl21/frontend-project-lvl1)
* Study project: [**"Difference Finder"**](https://github.com/Pavelvl21/frontend-project-lvl2) - is a cli-app that determines the difference between two data structures;  
[https://github.com/Pavelvl21/frontend-project-lvl2](https://github.com/Pavelvl21/frontend-project-lvl2)
* Study project: [**"RSS Reader"**](https://github.com/Pavelvl21/frontend-project-11) - is a service for aggregating RSS feeds, with which it is convenient to read various sources, such as blogs. It allows you to add an unlimited number of RSS feeds, updates them itself and adds new entries to the general feed;
[https://github.com/Pavelvl21/frontend-project-11](https://github.com/Pavelvl21/frontend-project-11)
* Study project: [**"Chat"**](https://github.com/Pavelvl21/frontend-project-12) - real-time SPA with React.js (in progress);  
[https://github.com/Pavelvl21/frontend-project-12](https://github.com/Pavelvl21/frontend-project-12)  

## Hard Skills
* JS ES6 (Intermediate)
* HTML 5 (Intermediate)
* CSS 3 (Intermediate)
* React.js (Intermediate)
* Node.js (Novice)
* Figma (Novice)
* Photoshop (Novice)
* PostgreSQL (Novice)

## Soft Skills
* Time management
* Adaptable
* Flexible
* Problem-solving
* Analytical
* Innovative
* Creative

## Codewars Solutions
* #### 5 kyu: Pete, the baker
```
const cakes = (recipe, available) => {
  const checkCount = (ingr) => {
    if (available[ingr] && recipe[ingr]) {
      return Math.floor(available[ingr] / recipe[ingr]);
    }
    return 0;
  };
  
  const cakeCount =  Object
    .keys(recipe)
    .map((ing) => checkCount(ing))
    .filter((num) => num >= 0);
  
  return Math.min(...cakeCount);
};
```
* #### 6 kyu: Sum of Digits / Digital Root
```
const digitalRoot = (n) => {
  const arr = n.toString().split('').map((num) => Number(num));
  const result = arr.reduce((num, acc) => acc + num, 0);
  if (result.toString().length === 1) {
    return result;
  }
  return digitalRoot(result);
};
```
## Education
* 04.2022 - Present  
**Hexlet.io**: Frontend Developer
* 02.2021 - 03.2021  
**MANAGYM**: Management skills course
* 2013 - 2016  
**International University MITSO**: Bachelor's degree, Management

## Languages
* English: **A1**
* Belarusian: **Native**
* Russian: **Native**
