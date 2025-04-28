# cs6700-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS6700 Assignment #1 Solved](https://www.ankitcodinghub.com/product/cs6700-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117989&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6700 Assignment #1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Instructions

1. Work on your own. You can discuss with your classmates on the problems, use books orweb. However, the solutions that are submitted must be your own and you must acknowledge all the sources (names of people you worked with, books, webpages etc., including class notes.) Failure to do so will be considered cheating. Identical or similar write-ups will be considered cheating as well.

2. In your submission, add the following declaration at the outset:

“I pledge that I have not copied or given any unauthorized assistance on this assignment.”

3. The assignment has two parts. The first part involves theoretical exercises, while thesecond part requires programming. For the first part, write/typeset the solutions, and upload it on moodle. For the second part, you are required to submit your work in a separate interface (check the details in Section II below).

1

I. Theory exercises

Problem 1.

Consider the finite horizon MDP setting, as formulated in Section 1.2 of the course notes. In place of the expected cost objective defined there, consider the following alternative cost objective for any policy π and initial state x0:

!#

Jπ(x0) = Egk(xk, µk(xk), xk+1) ,

(a) Show that an optimal cost and an optimal policy can be obtained by the following DPalgorithm variant:

JN(xN) = exp (gN(xN)) , Jk(xk) = min Exk+1 (exp (gk(xk, ak, xk+1)) Jk+1(xk+1)) .

ak∈A(xk)

(b) Let Vk(xk) = log Jk(xk). Assume that the single stage cost gk is a function of xk and ak only (and does not depend on xk+1). Then, show that the DP algorithm, which is specified above, can be re-written as

VN(xN) = gN(xN),

Vk(xk) = min gk(xk, ak)+ logExk.

ak∈A(xk)

(c) Recall the “oven problem” which was a linear system with quadratic cost problem overtwo stages. Using the notation from this problem, consider the following ‘exponentiated cost’ objective: For a given scalar θ, define

Ja , (1)

where xk+1 = (1 −α)xk +αak +wk, for k = 0,1.

In the above, wk is a Gaussian random variable with mean zero and variance σ2.

Solve problem (1) using the DP algorithm from the part above. Identify the optimal policy, and the optimal expected ‘exponentiated’ cost.

Problem 2.

You are walking along a line of N stores in a shopping complex, looking to buy food before entering a movie hall at the end of the store line. Each store along the line has a probabi1ity p of providing the food you like. You cannot see what the next store (say k+ 1) offers, while you are at the kth store and once you pass store k, you cannot return to it. You can choose to buy at store k, if it has the food item you like and pay an amount N − k (since you have to carry this item for a distance proportional to N−k). If you pass through all the stores without buying, then you have to pay 1−1 p at the entrance to the movie hall to get some food.

(a) Formulate this problem as a finite horizon MDP.

(b) Write a DP algorithm for solving the problem.

Problem 3.

A machine is either running or broken. If it runs for a week, it makes a profit of 1000 INR, while the profit is zero if it fails during the week. For a machine that is running at the start of a week, we could perform preventive maintenance at the cost of 200 INR, and the probability of machine failing during the week is 0.4. In case the preventive maintenance is not performed, the failure probability is 0.7. A machine that is broken at the start of a week can be repaired at a cost of 400 INR, in which case the machine would fail with probability 0.4, or replaced at a cost of 1500 INR. A replaced machine is guaranteed to run through its first week.

(a) Formulate this problem as an MDP with the goal of maximizing profit for a given numberof weeks.

(b) Find the optimal repair/replace/maintenance policy under a horizon of four weeks, assuming a new machine at the start of the first week.

Problem 4.

Suppose you want to travel from a start point S to a destination point D in minimum average time. You have the following route options:

1. A direct route that requires α time units.

2. A potential shortcut that requires β time units to get to a intermediate point I. From I, you can do one of the following: (i) go to D in c time units; or (ii) head back to S in β time units. The random variable c takes one of the values c1, . . . , cm, with respective probabilities p1, . . . , pm. The value of c changes each time you return to S, independent of the value in the previous time period.

(a) Formulate the problem as an SSP problem. Write the Bellman’s equation (J = TJ) and characterize the optimal policy as best as you can.

(b) Are all policies proper? If not, why does the Bellman equation hold?

(c) Solve the problem for α = 2, β = 1, c1 = 0, c2 = 5, and p1 = p2 =. Specify the optimal policy.

(d) Consider the following problem variant, where at I, you have the additional option of waiting for d time units. Each d time units, the value of c changes to one of c1, . . . , cm with probabilities as before, independently of the value at the previous time period. Each time c changes, you have the option of waiting extra d units, return to the start or go to the destination. Write down the Bellman equation and characterize the optimal policy.

II. Simulation exercises

The students are required to do the following:

2. You only need to open the starter notebook in colab, and make a personal copy. You canwork on everything in colab itself.

For submission status, check on the submissions tab.
