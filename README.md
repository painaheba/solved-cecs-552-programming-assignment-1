Download Link: https://assignmentchef.com/product/solved-cecs-552-programming-assignment-1
<br>



Estimating Probabilities via Monte Carlo Simulation

<h1>Program User Interface</h1>

The deliverable for this programming assignment (and all subsequent assignments) should consist of a single program whose user interface consists of a command-line main menu (GUI’s are appreciated, but not necessary). The final menu option allows the user to quit the program. For any other selected option, the program should complete the associated computation, print the results (and nothing more) in a clear, readable manner, and return the user to the main menu. Note: the programmer may assume that the user will supply sensible input. Thus, input-error checking is not required.

<h1>The Synchronicity of Lecture and Leisure</h1>

In late December Professor Markov began a daily regimen of watching exactly one epsisode from either of his two favorite sitcoms: “Seinfeld” and “I Love Lucy”. Starting with the first episodes of each, and following the order of the episodes, each day Markov randomly selected the sitcom that he would watch for that day. Since he preferred Lucy somewhat more than Seinfeld, he selected from Lucy with a probability of 0<em>.</em>6, and from Seinfeld with a probability of 0<em>.</em>4. Note that his daily selections were independent of each other. On day 255 of this regimen, Markov selected from Lucy, and the next episode happened to be episode 152, and titled “Lucy Goes to Monte Carlo”. Coincidentally, that very evening Markov was to give a lecture on Monte Carlo simulation. So he wondered, “what is the likelihood that I would watch this episode on the same day as giving this lecture? I know, I’ll have class answer this with a Monte Carlo simulation!”

For Option 1, of your program, have the user input the number <em>n </em>of times your program should simulate Markov’s regimen. Then simulate the regimen <em>n </em>times and report on the fraction of simulations

1

that result in watching Lucy’s episode 152 on day 255. Assume that both sitcoms have an infinite number of episodes, so there is no concern about exhuasting either episode.

<strong>What’s in a Name?</strong>

From an example in lecture, we know that, assuming a family has two children, the probability that both children are girls on condition that at least one child is a girl equals one third. Use Option 2 to estimate the probability <em>p </em>that both children are girls on condition that at least one child is a girl named Tabatha. Assume that the probability that any newborn girl is named Tabatha is equal to 0<em>.</em>001, and that all girl namings are independent. Assume also that, for a two-child family, having a girl is equally likely as having a boy, and that genders of both children are independent. To estimate <em>p</em>, continuously generate two-child families, where each girl of the family has the Boolean attribute of being named Tabatha. When a <strong>relevant </strong>family having a girl named Tabatha is generated, keep track of how often the other child is also a girl. Generate a total of <em>n </em>relative families, where <em>n &gt; </em>0 is input by the user. Report on the fraction of relevant families that have two girls. Provide a paragraph explaining why the simulation result makes intuitive sense.


