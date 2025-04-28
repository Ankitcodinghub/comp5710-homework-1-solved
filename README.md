# comp5710-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [COMP5710 Homework 1 Solved](https://www.ankitcodinghub.com/product/comp5710-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117878&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5710 Homework 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
For each of the four problems below:

(15 pts) 1. Draw the program graph. You must use line numbers to label all nodes in the graph. Do not use the statements or statement fragments themselves as nodes labels.

(5 pts) 2. Compute the cyclomatic number using each of the three methods discussed in class. Show your work.

(5 pts) 3. Calculate the P* using the given conditions under each problem. Show your work.

Hint:

1 if (C1 &amp;&amp; C2) 2 S1; 3 else 4 S2;

For the program slice above, the program graph should be drawn as below:

Problem 1:

1 void Q1(){

2 S1;

3 if(C1){

4 S2;

5 if(C2){

6 S3;

7 }

8 else{

9 S4;

10 }

11 }

12 else if(C3&amp;C4){

13 S5;

14 }

15 else{

16 S6;

17 }

18 S8;

19 }

1 void Q2(){

2 S1;

3 if(C1) {

4 if(C2 &amp;&amp; C3) {

5 S2;

6 If(C4){

7 S3;

8 }

9 } else {

10 S4;

11 }

12 } else {

13 do{

14 S5;

15 if(C5) {

16 S6;

17 }

18 } while(C6)

19 }

20 S7;

21 }

For P*, suppose the do loop (line 13) executed exactly 4 times.

1 void Q2(){

2 S1;

3 if(C1 &amp;&amp; C2){

4 S2;

5 }

6 else{

7 for(S3;C3;S4){

8 S5;

9 if(C4){

10 S6;

11 }

12 }

13 }

14 if(C5){

15 for(S7;C6;S8){

16 S9;

17 }

18 }

19 else{

20 S10;

21 }

22 S11;

23 }

1 void Q4(){

2 S1;

3 while(C1){

4 if(C2 &amp;&amp; C3){

5 S2;

6 }

7 else{

8 S3; 9 }

10 while(C4){

11 S4;

12 if(C5&amp;C6){

13 S5; 14 }

15 while(C7){

16 S6;

17 }

18 }

19 S7;

20 }

21 S8;

22 }

For P*, suppose the while loop in line 3, 10, and 15 are executed exactly 2, 2, and 3 times.
