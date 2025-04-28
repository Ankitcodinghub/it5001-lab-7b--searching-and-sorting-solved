# it5001-lab-7b--searching-and-sorting-solved
**TO GET THIS SOLUTION VISIT:** [IT5001 Lab 7b- Searching and Sorting Solved](https://www.ankitcodinghub.com/product/it5001-week-7b-searching-and-sorting-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119264&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IT5001 Lab 7b- Searching and Sorting Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Part 1 Sorting

Given a list lst of n numbers and an index i where 0 &lt; i &lt; n, we can compare the two numbers lst[i-1] and lst[i]. If the two numbers are different, the bigger one should be swapped to the right such that lst[i] &gt; lst[i-1] after the swap.

Write a function bubble(lst) which uses a simple loop to perform the above task from i = 1 to i = n-1. (Note that the number of iterations is n-1 and not n.)

Did you notice something? What happens if bubble() is applied to a list many times?

How many times do I need to apply bubble() to a list in order to make the list fully sorted?

Write a function bubbleSort(lst) which returns a list that is sorted from the elements of lst. Here is some sample output in which you should be able to change n to a larger number and the sorting will still work.

Final Thoughts

Do you really need to…

• …apply bubble() so many times…

• …and to the entire list?

Part 2 Searching

The bisection method in mathematics is a root-finding method that repeatedly bisects an interval and selects a subinterval in which a root must lie for further processing. Given a function 𝑓𝑓(𝑥𝑥), we want to solve for 𝑥𝑥 when 𝑓𝑓(𝑥𝑥)=0.

In this question, we assume that the function 𝑓𝑓 is continuous. Given two numbers 𝑎𝑎 and 𝑏𝑏 such that 𝑓𝑓(𝑎𝑎)&gt;0 and 𝑓𝑓(𝑏𝑏)&lt;0, we repeat the following:

 Compute 𝑥𝑥𝑠𝑠 =(𝑎𝑎+𝑏𝑏)/2.

 If 𝑓𝑓(𝑥𝑥𝑠𝑠)&lt;0, then the solution lies on the left of 𝑥𝑥𝑠𝑠. So, 𝑏𝑏 =𝑥𝑥𝑠𝑠.  Otherwise, 𝑎𝑎 =𝑥𝑥𝑠𝑠.

We stop the above when the absolute value of 𝑓𝑓(𝑥𝑥𝑠𝑠) is smaller than a constant “error”. After we exit the loop, the value of 𝑥𝑥𝑠𝑠 should be very close to the actual solution of 𝑓𝑓(𝑥𝑥)=0. If 𝑓𝑓(𝑎𝑎)&lt;0 and 𝑓𝑓(𝑏𝑏)&gt;0, we just need to reverse the above inequality. If both 𝑓𝑓(𝑎𝑎) and 𝑓𝑓(𝑏𝑏) have the same sign, we can just “give up” as there might not be a solution which means the bisection method might run in an infinite loop.

You are given two functions 𝑓𝑓 and 𝑔𝑔:

Write a function bisection(start,end,f) to solve for 𝑥𝑥 in both 𝑓𝑓(𝑥𝑥)=0 and 𝑔𝑔(𝑥𝑥)=0 using the bisection method. (In general, you should be able to solve any continuous function f with f(start) and f(end) having different signs.) You can set “error” to a small number e.g. 0.00000001.

The roots of 𝑓𝑓(𝑥𝑥)=0 and 𝑔𝑔(𝑥𝑥)=0 are -3.3459632955491543 and 63.39649252593517 respectively. (Your numbers can be a little off but abs(f(x)) should be less than “error”.)

Part 3 Advanced Sorting (Extra)

This part is totally extra (for this course), but it would be interesting to try different sorting methods.

We are given a list lst of n numbers. To simplify the problem, we assume every number in the list is unique. (However, it is not difficult to solve the problem even if there are duplicate numbers in the list.)

We pick any number from lst, say x. For the rest of the numbers, we then separate them into two lists: lsta which contains all the numbers smaller than x, and lstb which contains the rest of the numbers. Let’s give a name to this functionality: partition.

Then we apply some “magic” to lsta and lstb such that they become sorted after the “magic”. Finally, we output the list lsta + [x] + lstb.

What is this “magic”? And what is the magic that we have performed?
