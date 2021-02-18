1. Pershin Konstantin
2. Email: kostya.pershin007@gmail.com  phone number: 89967340182
3. I am a 2nd year student at the Polytechnic University, I am fond of programming and want to work in this field. Studying web programming (CSS, HTML, JS). I like programming in itself, and the web precisely because you interact most with the visual component of the project
4. CSS, HTML, JS(average level), git, GitHub, VSCode, command line.
5. Code examples: 
    Logic of simple game:
```
    import readlineSync from 'readline-sync';

const sameGameLogic = (question1, answer1, question2, answer2, question3, answer3, userName) => {
  const numbers = [[question1, answer1], [question2, answer2], [question3, answer3]];
  for (let i = 0; i < numbers.length; i += 1) {
    console.log(`Question: ${numbers[i][0]}`);
    const userAnswer = readlineSync.question('Your answer: ');
    if (userAnswer === numbers[i][1]) console.log('Correct!');
    else if (userAnswer !== numbers[i][1]) return console.log(`${userAnswer} is wrong answer ;(. Correct answer was ${numbers[i][1]}. \nLet's try again, ${userName}!`);
  }
  return console.log(`Congratulations, ${userName}!`);
};
export default sameGameLogic;
```
6. Studied at Hexlet courses, made a one-page website and a small console game.
7. Still unfinished courses, bachelor of university
8. English level - B2. There was a practice of spoken English at a university lesson and a restaurant where I worked part-time (communicated with guests)
    
