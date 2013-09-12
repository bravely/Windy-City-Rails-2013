# Data Science: New Snake Oil, Same Old Machine Learning
by Randall Thomas at Thunderbolt Labs

[us@thunderboltlabs.com](mailto:us@thunderboltlabs.com) to get in touch

**"We call it machine learning, because Statistics Ain't Cool"
…so we make up new words to get pay raises.**

Pair programming per half of the keyboard

bestjoke: Doesn't work in Vim, but Emacs!

by careful bringing it up at work because no one knows what Data Scientist means

"Odds are anyone using 'Data Scientist' is an idiot"

##### This is too young to be a science
* marketing BS gogogogogogogo

### Tactical Data 101
Statistics in Nouns & Verbs
3 types of nouns

* Continuous
* Discrete(not continuous!)
* Count\*
* Time Series\*\*

"Statistics is lying a little bit less every time you do something"

**What we can do:**

* Describe What Happened
* Guess What Might Happen

### Words that Statisticians Like

* Factors: Labels, tags, if it isn't a number and it's categorical, it's a Factor
* Distribution: Pictures of data, what it looks like on paper, graphed etc
* Mean & Median: Measures of central tendency, 'about the average'
* Variance: AnaNova, AnaCova: "How wide is the data?" How much spread is there

### Stats Words for Humans
The Lexicon is bullshit

#### Distributions
You can make a whole bunch of assumptions
How much variance of the mean
"Most people get Cs, a few people get Ds, a few get Bs, and even fewer As."

** Who Cares?**

~Lazy~ Smart Developers

**VimGolf**

###### Common Distributions:
* Uniform
* Normal
* Binomial: Either/Or Trials, like flipping coins
* Geometric
* Hypermetric Geometric
* Poisson/Erlang: Describes a random arrival at an endpoint(How telephone calls come into a switch, how they can come to your service. Good for load distribution)
* Beta
* Log Normal

###### Uncommon Distributions(Who the hell invited you?)
* Zipf's Law
* Bose-Einstein
* lost the rest qqqqqqqq

**Fermie-Dyrac Thing:** For why electrons don't jump out and kill you

Distributions!

A lot of these assume data is distributed normally

** Central Limit Theorem** Saves our Normal bacon

Sampling: If you sample enough of anything, you end up with a normal distribution
** With Replacement**
** Without Replacement**

Sampling + Central Limit Theorem = The recipe for lazy

### Answering Important Questions with Statistics
6 Easy Steps for Analyzing Data

1. GET THE DATA
2. Look at the Data
	1.  Look at the Data… Again. Something could be wrong, something might be missing, there might be places things don't line up.
	2. AGAIN: 90% you're screwing up because you didn't check the data enough for inconsistencies
3. Draw pictures(distributions!)
4. Can you answer the question with what you've got?
	6. Are you sure?
5. Answer questions
6. Lose sleep worrying whether you answered correctly or not

Deployed Staging to Production, lost $450 million, Knight Ventures

### 5 Number Summary

* Box Plots: As in, MAKE GRAPHS
* Check the distribution again
	* Histogram: Bump in the middle
* Can we say anything about the data(are we there yet?)

**Support Vector Machine**
Fit the data
Use it

### So where's the BD/ML connection?
There's no secret sauce
Machine Learning: Statistics we're too lazy to do ourselves that's really hard to get right