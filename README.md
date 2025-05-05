# algorithms-project-4-hashing-solved
**TO GET THIS SOLUTION VISIT:** [Algorithms Project 4-Hashing Solved](https://www.ankitcodinghub.com/product/algorithms-project-4-hashing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98904&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Algorithms Project 4-Hashing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
# Hashing

## Overview

Test each hashing implementation with the following:

1. The total number of elements in the table (N), the size of the table (T), the load factor

(Lambda = N/T), the average number of collisions (M = C/N), and the total number of

collisions (C),

2. check whether each word in another given file, query_words.txt, is in the hash

table, and print corresponding output depending on whether the word is found and not

found, and how many probes it took to find the word, if it exists.

## Thoughts

Within the “create_and_test_hash.cc” file,

setup the “number of items” (int type),

“size of hash table” (int type),

“load factor” (float type),

“average number of collisions” (float type),

“total number of collisions” (int type).

Give the correct equation for load factor

(number of items divide by size of hash table)

and average number of collisions

(total number of collisions divide by number of items).

Within the “spell_check.cc” file,

create a method called “cleanWord”,

which sets all the characters in the lower cases.

Then create three methods called “caseACorrect”, “caseBCorrect”, and “caseCCorrect”.

“caseACorrect” is set to add the missing character,

“caseBCorrect” is set to remove the additional character,

and “caseCCorrect” is set to swap adjacent characters from the word in any possible position.

Complete the “testSpellingWrapper” method,

check if the word is correct or incorrect.

Create a new “linear_probing.h” file,

implement 4 get methods,

“getNumberOfElement”, “getSizeOfTable”, “getNumberOfCollision”, and “getProbe”.

Implement linear probing,

to look up and place the element in the closest flowing empty spot.

Within the “quadratic_probing.h” file,

implement 4 get methods,

“getNumberOfElement”, “getSizeOfTable”, “getNumberOfCollision”, and “getProbe”.

Create a new “double_hashing.h” file,

implement 4 get methods,

“getNumberOfElement”, “getSizeOfTable”, “getNumberOfCollision”, and “getProbe”.

Implement double hashing, and rehashing,

which use a bigger table and create a new table to hash,

then insert the element.

## Run

– To compile on terminal type:

1. make clean

2. make all

– To delete executables and object file type:

1. make clean

– To run with a given file that is redirected to standard input:

1. ./create_and_test_hash words.txt query_words.txt quadratic

2. ./create_and_test_hash words.txt query_words.txt double R

3. ./create_and_test_hash words.txt query_words.txt double
