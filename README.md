# cse102-assignment-7-a-word-puzzle-solved
**TO GET THIS SOLUTION VISIT:** [CSE102 Assignment 7-A word puzzle Solved](https://www.ankitcodinghub.com/product/cse102-assignment-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101990&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE102 Assignment 7-A word puzzle Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
A word puzzle is a word game that consists of the letters of words placed in a grid, which usually

</div>
</div>
<div class="layoutArea">
<div class="column">
has a rectangular or square shape. The objective of this puzzle is to find and mark all the words

</div>
</div>
<div class="layoutArea">
<div class="column">
hidden inside the box. The words may be placed horizontally, vertically, or diagonally. Many word

</div>
</div>
<div class="layoutArea">
<div class="column">
search puzzles have a theme related to all the hidden words, such as food, animals, or colors.

</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
7×7 Example board

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Example Founded Words: Meal [0,0] -&gt; [0,3]

Scene [4,4] -&gt; [4,0]

Row [3,2] – &gt; [1,1]

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Part 1 (Board Build Part): Build a 15×15 board randomly chosen from given “wordlist.txt” file. You need to take random 7 words. The words may be placed horizontally, vertically, or diagonally (8 directions). It should be changed each run. Fill the gaps with random characters.

Part 2 (Game Part):

<ul>
<li>The player should enter the first coordinates of a word and word that the player found.</li>
<li>If a word is founded in this coordinate, you need to replace the word with X and give 2 points to the user. If the word is not founded, you need to give a warning message like “Wrong choice! You have only 2 lefts.” The player can only make three mistakes.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
• The player can terminate the game by writing the “:q” command, three mistakes, or finding all the words. If the game is terminated, you need to write the total points that the player got.

•

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
A common strategy for finding all the words is to go through the puzzle left to right (or right

</div>
</div>
<div class="layoutArea">
<div class="column">
to left) and look for the word’s first letter. After finding the letter, one should look at the eight

</div>
</div>
<div class="layoutArea">
<div class="column">
surrounding letters to see whether the following letter of the word is there. One can then

</div>
</div>
<div class="layoutArea">
<div class="column">
continue this method until the entire word is found.

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
General Rules:

Obey the style guidelines.

Do not change the provided function prototypes (you will not get any credits).

The program must be developed on Ubuntu using GCC compiler (version provided in class), compilation problems due to the use of another OS or compiler is your responsibility (you will not get any credits).

Your program should work as expected. Do not expect partial credit if your code works only in some cases but not in all cases as expected.

You can ask your questions about the homework by posting on the forum in Teams. Handing in your work:

Hand in your work using the appropriate class Teams assignment site. No

late submissions will be accepted.

Pack this directory into a zip file named 20180000001_X_Z.zip

When unpacked as above in Ubuntu (version provided in class) it should allow executing the following commands in a shell:

▪ “$make clean” removes everything except makefile, source code (.c ) and other resource files (if any) – all compiling results and intermediate files should be removed.

▪ “$make compile” should compile the code.

▪ “$make run” should run the code along with any parameters needed.

</div>
</div>
</div>
