# Anatoliy Lomakin

Student [RS-Scholl](https://rs.school/)

___
___
___

## Contacts

- **Address**: Ukraine, the city of Oleksandria
- **Phone**: +380972436484
- **E-mail**: lomakin90anatoliy@gmail.com
- **GitHub**: [LomakinAnatoliy](https://github.com/LomakinAnatoliy)

___
___

## My story

Programming is a hobby for me. It all started with free courses on "GeekBrains", from that time my journey into the world of programming began. Now, I spend almost all my free time learning something new.

___
___

## Skills

- HTML (HTML Semantic Elements, BEM methodology, Validate code)
- PageSpeed ​​Insights (Page speed statistics)
- CSS (Preprocessor SASS)
- JS (Fundamentals)
- GULP (Аutomation of frequently used tasks)
- GitHub (Development version control system)
- Figma, Photoshop, Illustrator

___
___

## Code examples

The idea is that when the page is updated, three blocks of figures constantly change their position on the website page. Strong for work ["Lamp"](https://github.com/LomakinAnatoliy/TestWork-Lamp/blob/main/build/js/script.js)

`const circle = document.querySelector('.circle');
const rhombus = document.querySelector('.rhombus');
const triangle = document.querySelector('.triangle');

let arrayImg = [circle, rhombus, triangle];

for(let j=0; j<=arrayImg.length - 1; j++) {
  let element = arrayImg[j];
  for(var i = 0; i < 6; i++){
    let min = Math.ceil(10);
    let max = Math.floor(35);
    let widthMax = Math.floor(document.documentElement.scrollWidth - 40);
    let heightMax = Math.floor(document.documentElement.scrollHeight - 40);

    let getWidth = Math.floor(Math.random() * (widthMax - min + 1)) + min;
    let getHeight = Math.floor(Math.random() * (heightMax - min + 1)) + min;
    let getValue = Math.floor(Math.random() * (max - min + 1)) + min;

    element.style.top = getHeight + 'px';
    element.style.left = getWidth + 'px';
    element.style.width = getValue + 'px';
    element.style.height = getValue + 'px';

    let clone = element.cloneNode(false);
    document.body.insertAdjacentElement('beforeEnd', clone);
  };
  document.body.removeChild(element);
};`

___
___

## Education

- **[HTML academy](https://htmlacademy.ru/profile/id593313)
- **[freeCodeCamp](https://www.freecodecamp.org/ukrainian/lomakin-1990-06-01)
- **ITDVN (front-end developer, just started)

___
___

## Experience

One freelance job

___
___

## Languages

The level of English is elementary, but I am working on it.