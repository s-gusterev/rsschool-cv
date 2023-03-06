# Sergey Gusterev

## Contacts

- Location: Yaroslavl, Russia
- Email: frontend.sg@gmail.com
- Telegram: @se_gus
- Github: s-gusterev

## About Me

I am a highly motivated and detail-oriented individual with a passion for web development. While I may not have any professional experience in this field, I have been actively learning and honing my skills through online courses and personal projects. As an introvert, I thrive in a focused and quiet work environment where I can channel my creativity and problem-solving abilities to deliver high-quality results. I am known for my strong work ethic, punctuality, and ability to work well both independently and as part of a team.

## Skills

- HTML
- CSS
- Javascript (Basic)
- REACT (Basic)
- GIT
- Figma (Basic)
- NODEJS (Basic, Framework Express.js)
- MONGODB (Basic, Mongoose)

## Code example

**DESCRIPTION**:
Digital root is the recursive sum of all the digits in a number.

Given n, take the sum of the digits of n. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.

```js
function digitalRoot(n) {
  function addArray(number) {
    return (number = number.toString().split(''));
  }

  function sumArray(array) {
    const sum = array.reduce((a, b) => +a + +b, 0);
    console.log(sum);
    return sum;
  }

  const numbers = addArray(n);
  let sum = sumArray(numbers);
  if (sum >= 10) {
    const newNumber = addArray(sum);
    sum = sumArray(newNumber);
    return digitalRoot(sum);
  }
  return sum;
}
```

## Courses

- Yandex Prakticum Course "Web developer" (completed)

- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

## Languages

- English (Beginner)
- Russian (Native)
