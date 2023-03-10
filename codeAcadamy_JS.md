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
<img src="https://content.codecademy.com/projects/introduction-to-javascript/learn-javascript-introduction/kelvin-weather/Kelvin%20Thermometers.svg" width=50 heigh=50>  
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
