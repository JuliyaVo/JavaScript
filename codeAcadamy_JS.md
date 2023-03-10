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
