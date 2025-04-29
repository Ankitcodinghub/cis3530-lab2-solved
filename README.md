# cis3530-lab2-solved
**TO GET THIS SOLUTION VISIT:** [CIS3530 Lab2 Solved](https://www.ankitcodinghub.com/product/lab2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115330&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIS3530 Lab2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Assume that a tools company called GMT stores data on different parts they manufacture and on suppliers who supply these parts. The database is called SP (Supplier-Parts) and consists of 3 tables:

S (SNo, SName, Status, City) P (PNo, PName, Colour, Weight, City) SP (SNo, PNo, Qty)

Note that

– All PKs are underlined

– SNo in SP is a FK that references table S, PNo in SP is a FK that references table P Step 1. Connect to linux.socs.uoguelph.ca and Postgres (see tutorial1 for details).

Step 2. download scripts to create tables S, P and SP. You will find them on moodle. Tutorial1 has details on how to download and run them

Step 3. Write SQL queries to do the following. Submit the queries as a SQL script file (e.g. lab2.sql). This file must include all your SQL queries. It must have an extension of sql.

1a. Find supplier names for suppliers who supply at least one red part. Use Cartesian product for this query.

1b. Find supplier names for suppliers who supply at least one red part. Use inner join for this query.

1c. The following SQL query uses natural join to find supplier names for suppliers who supply at least one red part (same as 1a), but it gives incorrect result. Why do you think that it gives incorrect result (answers such as “because it is invalid” or “because it is incorrect” will not be accepted ):

SELECT sname

FROM S NATURAL JOIN SP NATURAL JOIN P

WHERE P.color = ‘RED’;

2. Get all pairs of supplier numbers such that the two suppliers live in a CITY that contains the letter ‘N’ in its spelling.

3. Find supplier names for suppliers who supply at least one of the parts supplied by S2. You must use subqueries using IN operator.

Ritu Chaturvedi

4a. Write a subquery to find all supplier names for suppliers who do not supply part P2.

4b. Repeat 4a using set operator EXCEPT

5a. Given below is a query and its result. Why do think it displays duplicate supplier numbers? Fix the query so that it eliminates the duplicate values.

SELECT sno Result:

FROM sp NATURAL JOIN p

WHERE weight &gt; 12;

5b. Rewrite the query in 5a as a nested query such that the duplicate supplier numbers are eliminated, and the supplier numbers are displayed in ascending order.

Expected Result:

sno —–

S2

S3

S4

S5

(4 rows)

Ritu Chaturvedi
