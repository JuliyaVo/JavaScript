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
  <p><img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>Task. You are planning a vacation in August. You are given a program that takes the month as input.Complete the code to output "vacation", if the given month is August. Don't output anything otherwise.</p>
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
  <p><img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>Task. The current world record for high jumping is 2.45 meters. You are given a program that receives as input a number that represents the height of the jump.
<p>Complete the code to:</p>
<ol>
  <li>output to the console "new record" if the number is more than 2.45</li>
  <li>output to the console "not this time" in other cases.</li>
  </ol>
<p><b>Sample Input:</b>2.49<p>
<p><b>Sample Output:</b>new record<p>
  </p>
  <p>
   <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
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
  <h3>16.2. The if else Statement Practice</h3>
  <h5>Exam Results</h5>
  <p><img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>Task.Тhe result of an exam will be determined as follows։</p>
<p>If the score is</p>
<p><b>88 and above</b> => excellent</p>
<p><b>40-87</b> => good</p>
<p><b>0-39</b> => fail</p>
<p>You are given a program that takes the score as input.</p>
<p>Complete the code to output the corresponding result (excellent, good, fail) to the console.</p>
<img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
    var score = parseInt(readLine(), 10)
if (score >=88){
    console.log("excellent");
}
else if (score >=40 && score <88){
    console.log("good");
}
else {
    console.log("fail");
}
    </pre>
  </div>
  <h3>17.2. The Switch Statement Practice</h3>
  <h5>Dark Them</h5>
  <p><img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>Task.The user can choose the color theme for the browser:</p>
  <ol>
    <li>Light</li>
    <li>Dark</li>
    <li>Nocturne</li>
    <li>Terminal</li>
    <li>Indigo</li>
  </ol>
<p>You are given a program that takes the number as input. Complete the program so that it will output to the console the theme according to input number.</p>
  <p><b>Sample Input</b></p>
  <p>2</p>
  <p><b>Sample Output</b></p>
  <p>Dark</p>
  <img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
    function main() {
    var themeNumber = parseInt(readLine(), 10)
    switch (themeNumber){
        case 1:
        console.log("Light");
        break;
        case 2:
        console.log("Dark");
        break;
        case 3:
        console.log("Nocturne");
        break;
        case 4:
        console.log("Terminal");
        break;
        case 5:
        console.log("Indigo");
    }
    </pre>
  </div>
   <h3>19.2. The While Loop Practice</h3>
  <h5>Time's Up</h5>
  <p><img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>Task. Write a program-timer, that will take the count of seconds as input and output to the console all the seconds until timer stops.</p>
<br><b>Sample Input</b></br>
<br>4</br>
<br><b>Sample Output</b></br>
<br>4</br>
<br>3</br>
<br>2</br>
<br>1</br>
<br>0</br>
  <p><img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
    function main() {
    var seconds = parseInt(readLine(), 10)
    while (seconds >=0){
        console.log (seconds);
        seconds--;
    }
}
 </pre>
  </div> <h3>21.2. The While Loop Practice</h3>
  <h5>Break and continue</h5>
  <p><img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>Task. Many tall buildings, including hotels, skip the number 13 when numbering floors -- often going from floor 12 to floor 14. It is thought that the number 13 is unlucky.
Write a program that will number 15 rooms starting from 1, skipping the number 13. Output to the console each room number in separate line.</p>
  <p><img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
    var countOfRooms = 15;
for(i=1; i<=16; i=i+1){
if (i==13)
continue;
    console.log (i);
}
 </pre>
  </div>
 </div> <h3>Code Project</h3>
  <h5>The Snail in the Well</h5>
  <p><img src="https://cdn-icons-png.flaticon.com/512/3524/3524335.png" width=20 heigh=20>Task. The snail climbs up 7 feet each day and slips back 2 feet each night.</p>
<br>How many days will it take the snail to get out of a well with the given depth?</br>
<br><b>Sample Input:</b></br>
<br>31</br>
<br><b>Sample Output:</b></br>
<br>6</br>
<br><b>Explanation:</b> Let's break down the distance the snail covers each day:</br>
<br>Day 1: 7-2=5</br>
<br>Day 2: 5+7-2=10</br>
<br>Day 3: 10+7-2=15</br>
<br>Day 4: 15+7-2=20</br>
<br>Day 5: 20+7-2=25</br>
<br>Day 6: 25+7=32</br>
<br>So, on Day 6 the snail will reach 32 feet and get out of the well at day, without slipping back that night.</br>
<p><img src="https://cdn-icons-png.flaticon.com/128/556/556690.png" width=10 heigh=10>Solution:</p> 
  <div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir=auto>
    <pre>
  
 </pre>
  </div>
  
  
  
  
    
    
    
    
    
    
    
  
 
