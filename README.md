# cmsc388-project-1-python-practice-solved
**TO GET THIS SOLUTION VISIT:** [CMSC388 Project 1-Python practice Solved](https://mantutor.com/product/cmsc388-p1-python-practice-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115294&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC388  Project 1-Python practice Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Description

You will be implementing some basic functions in Python as practice, including using iterators and built-in functions.

Setup

Make sure Python 3.10 is installed on your computer.

You should work on this project (and the other projects in this course) in a virtual environment. Navigate to the root of a directory you will use for this class. You should use the same environment for all projects in this course; you don’t need more than one. To create and activate one, enter the following commands in your terminal:

For Mac/Linux: bash $ python3 -m venv venv # creates environment $ source ./venv/bin/activate # enters environment

For Windows: bash $ py -m venv venv # creates environment $ ./venv/Scripts/activate # enters environment

These instructions can also be found in the Week 1 slides.

Testing this project with our public tests requires a package called pytest. To install it, run either of the following in your terminal while in your virtual environment: bash $ pip3 install -r requirements.txt bash $ pip3 install pytest Again, you must be in your virtual environment when installing packages with pip.

Project

In practice.py, implement the following functions:

1. hello_world()

Return the string Hello, World!

1. sum_unique(l)

Given a sequence of integers, return the sum of the integers, not counting duplicates, i.e. if you have two or more copies of an integer, it should be added to the final sum once. Examples: “`python

sum_unique([]) 0 sum_unique([4, 4, 5]) 9 sum_unique([4, 2, 5]) 11 sum_unique([2, 2, 2, 2, 1]) 3 “`

1. palindrome(x)

Given an integer or a string x, determine if x has the same value as x reversed. Examples: “`python

palindrome(1331) True palindrome(‘racecar’) True palindrome(1234) False palindrome(‘python’) False “`

2. sum_multiples(num)

Given a positive integer num, find the sum of all multiples of 3 and 5 upto and not including num. Examples: “`python

sum_multiples(10) # Multiples: [3, 5, 6, 9] 23 sum_multiples(3) # Multiples: [] 0 sum_multiples(5) #

Multiples: [3] 3 sum_multiples(16) # Multiples: [3, 5, 6, 9, 10, 12, 15] 60 “`

3. num_func_mapper(nums, funs)

Given a sequence of numbers nums and a sequence of functions funs, apply each function to nums and store the result in a list. Return the list of results.

Hint: The list of results should be the same length as funs. Example: “`python

f_list = [sum_unique, sum] num_list = [2, 2, 2, 4, 5] num_func_mapper(num_list, f_list) [11, 15] “`

4. pythagorean_triples(n)

Finds all pythagorean triples where a, b, and c (side lengths of a triangle) are all less than n units long. This function should not return distinct tuples that still represent the same triangle. For example, (3, 4, 5) and (4, 3, 5) are both valid pythagorean triples, but only the first should be in the final list.

The tuple elements should be sorted in ascending order, and the list of tuples should be sorted in ascending order by the last element of the tuple.

Examples: “`python

pythagorean_triples(10) [(3, 4, 5)] pythagorean_triples(11) [(3, 4, 5), (6, 8, 10)] pythagorean_triples(20) [(3, 4, 5), (6, 8, 10), (5, 12, 13), (9, 12, 15), (8, 15, 17)] “

7.custom_sort(lst)`

Use Python’s built-in sort function to sort the list so that the odd numbers (in the same order as in the original list) come first, and then the even numbers (also in the same order). Examples: “`python

custom_sort([1, 2, 3, 4, 5]) [(1, 3, 5, 2, 4)] “` (Hint: use a lambda function)

Testing

Navigate into the p1/ directory and run the command pytest. You should see your test results in the terminal.

Submission &amp; Grading

Compress a p1 directory into a .zip file containing practice.py and test_practice.py and submit it on ELMS after testing thoroughly; all of your work should be in this module. Do not include your virtual environment in your submission.

There are 130 possible points: 13 public tests worth 10 points each.

If your submission doesn’t have the practice.py and test_practice.py files, 20 points will be deducted from your score. If you include your virtual environment in your submission, 20 points will be deducted from your score.
