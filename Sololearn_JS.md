<div align=left>
  <h1>2.Basic Concepts</h1>
  </div>
 <div align=left>
  <h3>13. Code project</h3>
  <h5>Trip Planner</h5>
  <p>
    <img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>
    Task. You need to plan a road trip. You are traveling at an average speed of 40 miles an hour.
Given a distance in miles as input (the code to take input is already present), output to the console the time it will take you to cover it in minutes.
  <p><b>Sample Input:</b>150</p>
<p><b>Sample Output:</b>225</p>
<p><b>Explanation:</b>It will take 150/40 = 3.75 hours to cover the distance, which is equivalent to 3.75*60 = 225 minutes.</p>
  </p>
 <p>
   <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
    function main() {
    var distance = parseInt(readLine(), 10);
    //your code goes here
    var hours = distance / 40;
    console.log(hours * 60)
}
    </pre>
  </div>
  <h1>3.Conditionals and Loops</h1>
  </div>
 <div align=left>
  <h3>14.2. The if Statement Practice</h3>
  <h5>Vacation Month</h5>
  <p>
    <img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>
    You are planning a vacation in August.
You are given a program that takes the month as input.
<p>Task. Complete the code to output "vacation", if the given month is August. Don't output anything otherwise.</p>
  <p><b>Sample Input:</b>August</p>
  <p><b>Sample Output:</b>vacation</p>
  </p>
  <p>
   <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
    var month = readLine()
if (month == "August"){
console.log ("vacation");
}
    </pre>
  </div>
  <h3>15.2. The if else Statement Practice</h3>
  <h5>Set A World Record</h5>
  <p>
    <img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>
    The current world record for high jumping is 2.45 meters.
You are given a program that receives as input a number that represents the height of the jump.
<p>Task</p>
<p>Complete the code to:</p>
<ol>
  <li>output to the console "new record" if the number is more than 2.45</li>
  <li>output to the console "not this time" in other cases.</li>
  </ol>
<p><b>Sample Input:</b>2.49<p>
<p><b>Sample Output:</b>new record<p>
  </p>
  <p>
   <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Решение</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
    var height = parseFloat(readLine(), 10)
if (height > 2.45){
    console.log("new record");
}
else {
    console.log("not this time");
}
    </pre>
  </div>
  
  
  
  
  
  
    
    
    
    
    
    
    
  
 
