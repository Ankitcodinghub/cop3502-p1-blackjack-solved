# cop3502-p1-blackjack-solved
**TO GET THIS SOLUTION VISIT:** [COP3502 P1: Blackjack Solved](https://www.ankitcodinghub.com/product/cop3502-p1-blackjack-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;29477&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;COP3502  P1: Blackjack Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
<h1>Overview</h1>
In this project students will simulate a simplified version of the game Blackjack. Students will implement random card drawing, calculation, state tracking, and console input systems. The project is designed to be a playful yet practical opportunity to practice data types, console I/O, control structures, and libraries.

&nbsp;

<h1>Rules of the Road</h1>
<em>Forewarning: this specification does NOT follow the rules of casino Blackjack. Don’t drop out of your studies and move to Vegas just because you can beat your own randomized AI! </em>

&nbsp;

A typical game will play out as follows:

&nbsp;

The player will be dealt one card at the start of the game (where a game is one round of play). The player, based on the value of his cards, can either ask for another card (a hit) or choose to hold (stand). The dealer will then begin his turn and try to beat the player’s hand. The player is competing against the dealer, who has his own hand. Whomever is closer to 21 at the end of the game (as long as they don’t exceed 21) wins the game.

&nbsp;

<ol>
<li><em>Player’s turn</em>: Player tries to reach or come close to 21 without going over (as 21 is the highest hand).</li>
<li><em>Dealer’s turn</em>: Dealer tries to beat exceed the player’s hand without going over 21.</li>
<li>Determine the winner at the end of the game and increment the win count.</li>
<li>Repeat!</li>
</ol>
&nbsp;

You will need a while loop in your program. The loop will allow you to play successive games without restarting the program each time; it will also allow you to keep a win count over multiple games.

&nbsp;

Here is the basic syntax of a while loop:

&nbsp;

<strong>while</strong> (boolean expression)

{

// Statements }

&nbsp;

If the boolean expression evaluates to true, the loop continues. If/when it ever evaluates to false, then the loop terminates (we skip over the loop block) and continue with the program.

&nbsp;

Here is an example of a while loop:

&nbsp;

<strong>int</strong> x= 0; <strong>while</strong> (x &lt; 17)

{

x += 10;

}

The variable <strong><sub>x</sub></strong> is initialized to zero and the conditional statement is checked. Since <sub>0</sub> is less than <sub>17</sub>, the expression evaluates to <sub>true</sub> and the statement in the while loop block will be executed. The number <sub>10</sub> is added to the value of <strong><sub>x</sub></strong>, so <strong><sub>x</sub></strong> is now <sub>10</sub>. We’ve reached the end of the loop, so we jump back up to the conditional statement. The expression evaluates to true since <sub>10</sub> is less than <sub>17</sub>, so we execute the statement in the loop again. Now <strong><sub>x</sub></strong> is equal to <sub>20</sub>. Once more the loop block ends and we jump back up to the conditional statement. Since <sub>20</sub> is not less than 17, the expression evaluates to <sub>false</sub> and the loop block will be skipped, and we jump to the code after the loop.

&nbsp;

In this project, you will need to loop until the player chooses the exit option from the menu.

&nbsp;

<h1>Structure</h1>
<em>Now that you have a general overview, here are the nitty gritty details. </em>

&nbsp;

When the program starts it should print “<strong><sub>START GAME #1</sub></strong>” to the console, and the player should automatically be dealt their first card. With each new game played it should print the corresponding game number in this way.

&nbsp;

To determine what card the player is dealt, a random number must be generated between 1 and 13; it is then added to the player’s hand. The range of random generation will be from 1-13. The values correspond to these cards:

&nbsp;

<u>Value</u>&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <u>Card</u>

1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ACE!

2-10 &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (correspond to their face values)

<ul>
<li>JACK!</li>
<li>QUEEN!</li>
<li>KING!</li>
</ul>
&nbsp;

Face cards (King, Queen, Jack) are worth a value of 10. If the player is dealt a King (generated as 13), the value 10 should be added to the player’s hand value rather than a 13. Aces have a value of 1. Every other card will be worth its face value.

&nbsp;

Whenever a card is dealt, print the value of the card and the total value of your hand. (See sample output for format). If the card you were dealt was a face card or an ace then print the type of card. For example, if you were dealt a King you would print “<strong>Your card is a KING!</strong>” If the card was not a face card or an ace print the value of the card. For example, “<strong>Your card is a 2!</strong>”.

&nbsp;

After the card is dealt, print the menu to the screen. The menu should look like this:

&nbsp;

<ol>
<li>Get another card</li>
<li>Hold hand</li>
<li>Print statistics</li>
<li>Exit</li>
</ol>
&nbsp;

If the player chooses option 1, the player will be dealt another card. If the player has a hand of 21, they automatically win and “<strong>BLACKJACK! You win!</strong>” is printed; then a new game is started. If the player’s hand exceeds 21, the dealer automatically wins; print, “<strong>You exceeded 21! You lose.</strong>”, then start a new game.

&nbsp;

If the player chooses to hold their hand (option 2), then the dealer will be dealt his hand. To determine the dealer’s hand, generate a random number between 16 and 26 (both inclusive).

&nbsp;

If the dealer’s hand is above 21, the player automatically wins. If both the dealer and player have the same value hand then no one wins. In this case print “<strong>It’s a tie! No one wins!</strong>”. Otherwise, whoever has the higher hand value wins the round. If the player wins, print “<strong>You win!</strong>”. If the dealer wins print “<strong>Dealer wins!</strong>” After the winner (or tie) has been determined, a new game is started.

&nbsp;

If the player chooses option 3, you will print the statistics of the game. Throughout your program you will need to keep track of the number of games played, the player’s number of wins, the dealer’s’ number of wins and the number of ties. Print out all these values as well as the percentage of player wins to the total number games played. Format your percentage value to one decimal point. See sample output for format.

&nbsp;

If option 4 is selected, exit the program.

&nbsp;

If any other input is entered, print the following text:

&nbsp;

Invalid input! Please enter an integer value between 1 and 4.

&nbsp;

Then redisplay the menu. You can assume that the input will be numeric for this project (but not future projects.)

&nbsp;

<h1>Random Numbers</h1>
For random numbers, you <strong>must use</strong> the <sub>P1Random</sub> class provided:

&nbsp;

<strong>P1Random rng = new P1Random(); </strong>

&nbsp;

You can get a new int value between zero (<sub>0</sub>) and some number (exclusive!) using the <sub>nextInt()</sub> method:

&nbsp;

<strong>int myNumber = rng.nextInt(10); </strong><em>// Yields a random number in range [0,9]</em>

&nbsp;

To get a number in a specific range, use these commands:

&nbsp;

<strong>int myNumber = rng.nextInt(13) + 1; </strong><em>// A random number in range [1,13]</em>

&nbsp;

<strong>int myValue = rng.nextInt(11) + 16; </strong><em>// A random number in range [16,26]</em>

&nbsp;

<strong>NOTE: you must only pull random numbers as you need them, and you must use them in that order.</strong>

&nbsp;

Do not get random values and throw them away!

Do not get clever with how you generate random numbers!

&nbsp;

If you do, your output will diverge, and it could <strong>seriously impact</strong> your grade.

<strong>&nbsp;</strong>

<h1>Submissions</h1>
<strong>NOTE</strong>: Your output must match the example output *exactly*. If it does not, <strong><em>you will not receive full credit for your submission</em></strong>!

&nbsp;

File: &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; BlackJack.java

Method: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Submit on ZyLabs

&nbsp;

&nbsp;
