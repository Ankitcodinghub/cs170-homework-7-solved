# cs170-homework-7-solved
**TO GET THIS SOLUTION VISIT:** [CS170 Homework 7 Solved](https://www.ankitcodinghub.com/product/cs170-homework-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96697&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS170 Homework 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
DP solution writing guidelines:

Try to follow the following 3-part template when writing your solutions.􏰎

</div>
</div>
<div class="layoutArea">
<div class="column">
Define a function f(·) in words, including how many parameters are and what they mean, and tell us what inputs you feed into f to get the answer to your problem.

Write the “base cases” along with a recurrence relation for f.

Prove that the recurrence correctly solves the problem.

Analyze the runtime and space complexity of your final DP algorithm.

Counting Targets

</div>
</div>
<div class="layoutArea">
<div class="column">
We call a sequence of n integers x1,…,xn valid if each xi is in {1,…,m}.

(a) Give a dynamic programming-based algorithm that takes in n, m and “target” T as input and outputs the number of distinct valid sequences such that x1 + · · · + xn = T . Your algorithm should run in time O(m2n2).

(b) Give an algorithm for the problem in part (a) that runs in time O(mn2).

Hint: let f(s,i) denotes the number of length-i valid sequences with sum equal to s. Consider defining the function g(s, i) := 􏰅st=1 f (t, i).

3 Knightmare

Give an algorithm to find the number of ways you can place knights on an N by M (M &lt; N) chessboard such that no two knights can attack each other (there can be any number of knights on the board, including zero knights). Clearly describe your algorithm and prove its correctness. The runtime should be O(23M M · N ).

(Please provide a 3-part solution)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
4 Geometric Knapsack

Suppose we a rectangular paper of side lengths X, Y , where X, Y are positive integers, and a set of n products that can be made of the paper. Each product is a rectangle of dimensions ai × bi and of value ci, where all these numbers are positive integers. Suppose we can only cut the paper horizontally and vertically.

Describe and analyze an algorithm that determines the maximum value of the products that can be made out of the single X × Y paper. You may produce a product multiple times, or not at all if you wish.

5 GCD annihilation

Let x1, . . . , xn be a list of positive integers given to us as input. We repeat the following procedure until there are only two elements left in the list:

Choose an element xi in {x2,…,xn−1} and delete it from the list at a cost equal to the greatest common divisor of the undeleted left and right neighbors of xi.

We wish to make our choices in the above procedure so that the total cost incurred is minimized. Give a poly(n)-time dynamic programming-based algorithm that takes in the list x1, . . . , xn as input and produces the value of the minimum possible cost as output. You may assume that we are given an n × n sized array where the i, j entry contains the GCD of xi and xj, i.e., you may assume you have constant time access to the GCDs.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
