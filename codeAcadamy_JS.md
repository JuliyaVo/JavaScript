<div align=left>
  <h1>I. Introduction</h1>
  </div>
 <div align=left>
  <h3>Project 1. Kelvin Weather.</h3>
  <p>
    <img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>
    Task. Deep in his mountain-side meteorology lab, the mad scientist Kelvin has mastered weather prediction.
Recently, Kelvin began publishing his weather forecasts on his website. However there’s a problem: All of his forecasts describe the temperature in Kelvin.
With our knowledge of JavaScript, let’s convert Kelvin to Celsius, then to Fahrenheit.
<img src="https://content.codecademy.com/projects/introduction-to-javascript/learn-javascript-introduction/kelvin-weather/Kelvin%20Thermometers.svg">  
 <p>
   <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
 // this is the today's forecast in Kelvin
const kelvin = 293;
// this is the today's forecast in Celsius
let celsius = kelvin - 273;
// this is the today's forecast in Fahrenheit
let fahrenheit = celsius * (9 / 5) + 32;
// round down the Fahrenheit temperature
fahrenheit = Math.floor(fahrenheit);
console.log(`The temperature is ${fahrenheit} degrees Fahrenheit.`);
    </pre>
  </div>

  <div align=left>
  <h3>Project 2. Dog Years.</h3>
  <p>
    <img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>
    Task. Dogs mature at a faster rate than human beings. We often say a dog’s age can be calculated in “dog years” to account for their growth compared to a human of the same age. In some ways we could say, time moves quickly for dogs — 8 years in a human’s life equates to 45 years in a dog’s life. How old would you be if you were a dog?
    <p>Here’s how you convert your age from “human years” to “dog years”:</p>
<ol>
  <li>The first two years of a dog’s life count as 10.5 dog years each.</li>
  <li>Each year following equates to 4 dog years.</li>
    </ol>
<p>Before you start doing the math in your head, let a computer take care of it! With your knowledge of math operators and variables, use JavaScript to convert your human age into dog years.</p>
   <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
 // my age
const myAge = 40;
// number of early years
let earlyYears = 2;
earlyYears *= 10.5;
// myAge - number of earlyYears
let laterYears = myAge - 2;
laterYears *= 4;
console.log(earlyYears, laterYears);
let myAgeInDogYears = earlyYears + laterYears;
let myName = 'Julia'.toLowerCase();
console.log(`My name is ${myName}. I am ${myAge} years old in human years which is ${myAgeInDogYears} years old in dog years.`);
    </pre>
  </div>
  
  <div align=left>
  <h1>II. Conditionals</h1>
  </div>
 <div align=left>
  <h3>Project 1. Magic Eight Ball.</h3>
  <p>
    <img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>
    Task. The user will be able to input a question, then our program will output a random fortune.
    <ol>
      <li>In the first line of the program, define a variable called userName that is set to an empty string. If the user wants, they can enter their name in between the quotation marks.</li>
      <li>Below this variable, create a ternary expression that decides what to do if the user enters a name or not. If the user enters a name — like 'Jane' — use string interpolation to log Hello, Jane! to the console. Otherwise, simply log Hello!.</li>
      <li>Create a variable named userQuestion. The value of the variable should be a string that is the question the user wants to ask the Magic Eight Ball.</li>
      <li>Write a console.log() for the userQuestion, stating what was asked. You can include the user’s name in the console.log() statement, if you wish!</li>
      <li>We need to generate a random number between 0 and 7.

Create another variable, and name it randomNumber. Set it equal to this expression, which uses two methods (Math.floor() and Math.random()) from the Math library.</li>
      <li>Create one more variable named eightBall, and set it equal to an empty string. We will save a value to this variable in the next steps, depending on the value of randomNumber.</li>
      <li>We need to create a control flow that takes in the randomNumber we made in step 5, and then assigns eightBall to a reply that a Magic Eight Ball would return. Think about utilizing if/else or switch statements.</li>
      <li>
Write a console.log() to print the Magic Eight Ball’s answer, the value of the eightBall variable.</li>
 <p>
   <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
 let userName = '';
userName ? console.log ('Hello!') : console.log (`Hello, ${userName}!`);
const userQuestion = 'Please, answer my quastion';
console.log(userQuestion);
console.log(`${userName} asked: ${userQuestion}`);
let randomNumber = Math.floor(Math.random() * 8);
let eightBall = '';
switch (randomNumber) {
  case 0:
  eightBall = 'It is certain';
  break;
  case 1:
  eightBall = 'It is decidedly so';
  break;
  case 2:
  eightBall = 'Reply hazy try again';
  break;
  case 3:
  eightBall = 'Cannot predict now';
  break;
  case 4:
  eightBall = 'Do not count on it';
  break;
  case 5:
  eightBall = 'My sources say no';
  break;
  case 6:
  eightBall = 'Outlook not so good';
  break;
  case 7:
  eightBall = 'Signs point to yes';
  break;
  case 8:
  eightBall = 'Not very probable';
  break;
}
console.log(eightBall);
    </pre>
  </div>
      
      <h3>Project 2. Race Day.</h3>
  <p>
    <img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>
    Task. Codecademy’s annual race is just around the corner! This year, we have a lot of participants. You have been hired to write a program that will register runners for the race and give them instructions on race day.
      <p>As a timeline, registration would look like this:</p>
      <img src="https://content.codecademy.com/projects/introduction-to-javascript/learn-javascript-control-flow/race-day/raceday-timeline.svg">
     <p>Here’s how our registration works. There are adult runners (over 18 years of age) and youth runners (under 18 years of age). They can register early or late. Runners are assigned a race number and start time based on their age and registration.</p>
      <p>Race number:</p>
      <ol>
        <li>Early adults receive a race number at or above 1000.</li>
        <li>All others receive a number below 1000.</li>
      </ol>
      <p>Start time:</p>
      <ol>
        <li>Adult registrants run at 9:30 am or 11:00 am.</li>
        <li>Early adults run at 9:30 am.</li>
        <li>Late adults run at 11:00 am.</li>
        <li>Youth registrants run at 12:30 pm (regardless of registration).</li>
<p>But we didn’t plan for runners that are exactly 18! We’ll handle that by the end of the project.</p>
   <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
    let raceNumber = Math.floor(Math.random() * 1000);
let registerTime = true; // variable that indicates whether a runner registered early or not. Early - true, later - false.
let runnerAge = 27;
if (runnerAge > 18 && registerTime === true){
raceNumber += 1000;
}
if (runnerAge > 18 && registerTime === true){
console.log (`You will race at 9:30 am. Your race number ${raceNumber}`);
}
else if (runnerAge > 18 && registerTime !== true){
console.log (`You will race at 11:00 am. Your race number ${raceNumber}`);
}
else if (runnerAge < 18) {
console.log (`You will race at 12:30 am. Your race number ${raceNumber}`);
}
else if (runnerAge = 18) {
  console.log ("You should see the registration desk.");
}
    </pre>
      </div>
