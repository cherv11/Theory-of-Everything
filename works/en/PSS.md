---
layout: page
title: Probabilistic-Strategic Schemes as the best way to organize information in the Universe
lang: en
---

[2]: ../ABIW
[4]: ../MNES
[6]: ../AEGG
[7]: ../BLA
[11]: ../SI 
[15]: ../TMBM 
[Fool trends]: https://tylervigen.com/spurious-correlations 

## Correlation

Anything that can have definition is a logic object. Anything is a logic object, therefore. But when we say «apple», it has many possible meanings:

1) The apple is on the table;
2) There are bones in the apple;
3) The eyeball (Russian: eye apple) absorbs light;

In the first case, we talk about a certain apple in the set of objects located on the table. In the second, we think about every apple in the Universe. In the last case the eye is an apple metaphor, which has the same *meta*, and the definition of this meta is something spherical. This way we can visualize it:

<p>
    <img class="pimg" src="../../../images/PSS/1.jpg" width=400>
    <p class="pdesc">Figure 1. Three levels of abstraction of an apple</p>
</p>

Double link means «=» sign, and it’s needed for visual readability. You should argue that:

<p>
    <img class="pimg" src="../../../images/PSS/2.jpg" width=400>
    <p class="pdesc">Figure 2. The apple is a part of the table</p>
</p>

Actually, when we think about statement 1, often we consider the apple a part of the table, divided from another space with items lying on it. In this context, the table is also this item, as well as the tablecloth and the dirt on its leg. This is what exactly link in the first figure means: the sets of a certain table and all apples intersect. We call this link *correlation*.

**Correlation is a measure of sets similarity.**

From now on, we consider that any correlation lies in the $[0;1]$ gap instead of the conventional $[-1;1]$. For instance, let's say you wanted to find a correlation between the presence of bulling and poor grades in the schools of your country. For that, you gathered a gender-representative sample, conducted a survey in one particular school and received pure replies to just one question: «Had you ever been bulled?», and also the school scores. What did you find out?

<p>
    <img class="pimg" src="../../../images/PSS/3.jpg" width=400>
    <p class="pdesc">Figure 3. Representativeness in a research</p>
</p>

We may count all correlations between bulling and different grades, but one is enough. Also, we didn't add an abstract student which owns the grades: it was he on whose learning function bulling influences directly. There are *antonyms* — mutually exclusive concepts — in the picture: only one sex in the diagram is enough, because the sum of $x_i$ and $y_i$ correlations equals $1$. Grades are antonyms too: we divided them into good and bad for simplicity, but in general, antonyms are the special case of *types* — the sets representing different values of one parameter (gender, grade), and thus having a $0$ correlation among themselves. Well, you measured $w_2$ correlation and may say it approximately equals $w_1$ by sample representativeness: 

<p style="text-align: center">$x_1≈x_2; y_1≈y_2 ⇒ w_1≈w_2$</p>

But, of course, this is a mistake. If you draw up heatmaps of the schools in the country by factors which are presumably related with the presence of bulling and the level of grades, you will get about the following:

<p>
    <img class="pimg" src="../../../images/PSS/4.jpg" width=400>
    <p class="pdesc">Figure 4. Factors which impact the presence of bulling and the level of grades</p>
</p>

$α_i^{w_i}$ object is any subset in the set of all schools containing the information about correlation between the presence of bulling and poor grades. It can be not only a student as a set of grades (this is why we didn't add him), but also a whole school, city, one class, the influence of other students in the school on one or many grades of a particular student, or the certain pair of students — these are different levels of abstraction. Factors influencing a correlation are factors influencing correlating sets: the presence of student's friends and the level of parent's pressure on the students who inclined to bull the others. By identifying these factors, you can make predictions for the level of bulling and the fairness of giving grades in a particular school and, as a result, predict the $w_i$ correlation. This also allows you to identify theorems: there are less poor grades in the schools where students are more friendly; there are more bulling in the schools where the level of parent's pressure is higher.

If you don't have any hypothesis about gender differences in this system, the gender factor may influence the desired correlation only slightly. Factors giving representativeness are no different from any other factor in the scheme and intended to equalize the sets for the purity of the experiment. However, in addition to gathering representative sample does not help extrapolate data, the amount of dissimilar data is crucial for working with hypothesis and searching for mistakes (see below) in theorems, thus, when you choose between smaller representative and bigger unrepresentative samples, you should always prefer the second. Therefore, representativeness of the sample in base terms is overvalued.

Here is something that you didn't know about correlation. It can be asymmetric: 

<p>
    <img class="pimg" src="../../../images/PSS/5.jpg" width=300>
    <p class="pdesc">Figure 5. Asymmetric correlation</p>
</p>

Let's supplement our definition of correlation: correlation $AB$ means the probability of finding a random element of $A$ in $B$. Correlations $r_{AB}$ and $r_{BA}$ are equal to $\frac{n}{N(A)}$ and $\frac{n}{N(B)}$, respectively, where $n$ is the amount of elements in the intersection of $A$ and $B$. Therefore, correlation is asymmetric when the sets $A$ and $B$ are equally powerful. 

Actually, the amount of students who had been bulled does not equal to the amount of students who were rated bad. But then which correlation is desired? Depends on what we want to find out. The probability that a student will be rated bad if he has been bulled is the correlation (should we call it relation?) directed towards grades.  The operation of calculating the correlation has a direction consequently that we usually call the direction of *time*, and the chain of these operations is called *thought*.

## Efficiency

Let's count how much the probability of rating bad is increased in comparison with students who have never been bulled. To create an antonym of bulling let's use logic negation. Together bulling and its antonym make the same set of students as grades make, because it's two different ways to divide the same set, and hence the correlation between them equals $1$ to the both directions. Let's also sign the amount of elements in the sets and their intersections:

<p>
    <img class="pimg" src="../../../images/PSS/6.jpg" width=400>
    <p class="pdesc">Figure 6. Increase in the probability</p>
</p>

What the sum of correlations in two directions of one link equals $1$ is a coincidence (it turns out when $\frac{n}{N(A)}+\frac{n}{N(B)} = 1 ⇒ n(N(A)+N(B)) = N(A)\*N(B)$, that doesn't have physical sense). But the sum of correlations directed to bulling and non-bulling is a result of a theorem: *the sum of correlations to types from one set equals $1$*. The probability of getting a bad grade is increased by $^2/\_9$, but in no case should we convert it to a percentage. Think of how much the probability of $0.9$ will be increased by if we add $0.09$ to it, more precisely, how many times? For that, we need to calculate how many times it decreased by relative to one. From the law of waning usefulness (see below) follows:

<p style="font-size: 24px; text-align: center">
$κ_A^B = \frac{1-r_{\overset{—}{B}A}}{1-r_{BA}} = \frac{^5⁄_9}{^1⁄_3} = \frac{5}{3}$ or $166.(6)%$
</p>

This is called *efficiency from inclusion of $B$ into $A$*, or *contribution of $B$ for $A$* (denoted by the Greek letter kappa). Equal probabilities impacts equal contribution, and the physical meaning for the $≥ 1$ values of the contribution is: for each $κ_A^B$ events of $A$ there are $κ_A^B-1$ events that don't depend on $B$, and one that does. For each $5$ grades $2$ depends on bulling. But our efficiency is a bit... negative. Bulling is a negative phenomenon, and it's no coincidence that I tied it to poor grades and friendship to good grades. The negative phenomenon always has positive correlation with negative phenomenons, but the laws of efficiency are the same. 

To be honest, talking about efficiency in relation to grades is a bit incorrect. For that we need a *function* (see [nouns of process][7]), learning is great, for example. Learning has an efficiency. But still efficiency of the process is the probability of occurrence of an object. If there are many probabilities impacting the object, the total probability calculates by *the law of waning usefulness*, which follows from regularities of binomial coefficients:

<p>
    <img class="pimg" src="../../../images/PSS/7.jpg" width=400>
    <p class="pdesc">Figure 7. Probability of occurrence of an object</p>
</p>

But there is a little paradox. Negative correlation increases the probability of occurrence, but not the efficiency. The solution of this paradox gives us [*the theorem of fear*][6]: The efficiency of the system reaches its maximum when every object has only positive correlations. In other words, every object is tied only to objects with the same polarity. This let us get rid of emotional mistakes (see [good and evil, genius][6]):

<p>
    <img class="pimg" src="../../../images/PSS/8.jpg" width=400>
    <p class="pdesc">Figure 8. Polarized system</p>
</p>

To describe the system as a whole, without decomposition, there is *the bipolar efficiency equation*:

<p>
    <img class="pimg" src="../../../images/PSS/9.jpg" width=400>
    <p class="pdesc">Figure 9. Strange system</p>
</p>

Such system is called *strange* (see [fear][6]). Here are the entire chains of unknown polar efficiency. By the absence of the minus in the second part of the equation, equal values of efficiency of both polarities gives us *the line of fear* with maximal value of $0.25$ (horizontal) while the opposing values gives *the line of strangeness* (vertical). The function reaches its maximum when the influence of the first component is maximized and the influence of the second is minimized:

<p>
    <img class="pimg" src="../../../images/PSS/10.jpg" width=400>
    <p class="pdesc">Figure 10. The plane of bipolar efficiency</p>
</p>

Of course, the probability of the chain without nodes equals the product of the probabilities. Oddly enough, no matter how many nodes you have, you can calculate any contribution, provided that you know the size of a sample:

<p>
    <img class="pimg" src="../../../images/PSS/11.jpg" width=400>
    <p class="pdesc">Figure 11. The contribution in known system</p>
</p>

And vice versa, to calculate one exact value of the contribution between two sets you need to calculate the share of $B$ in all sets connected to $A$, for what you need to know literally everything within one *reality* (see [reality][15]). And what can we do? Use [*the theorem of anxiety*][6]: it is necessary to pay attention to all probable events regardless of their contribution. But there is a problem: this theorem is not enough to solve problems with a high risk.

## Risk

*Risk of $B$ for $A$* is the relation of contribution of event $B$ to the probability of it, reflecting the potential of $B$ to change the system. For example, suppose there is a roulette with $9$ red, $10$ black and one green field. The wagers are contributions which are equal to $2х$, $1.75х$, and $15х$, respectively. On what would you bet?

<p style="text-align: center">$ρ_A^B = ε_Bκ_A^B$</p>

<p style="text-align: center">$ρ_1=0.45*2=0.9; ρ_2=0.5*1.75=0.875; ρ_3=0.05*15=0.75$</p>

Nothing. Any experienced player will tell you that $15x$ on green is very little. The potential to change your positive balance in the pocket $A$ is negative. This literally means if you place $10$ bets on red, you will get $9$ back. In the system in the figure $12$ there is a function of advancing the balance and the money you won. The probability $^3/\_7$ means that for each $7$ dollars $3$ puts in your wallet (and $4$ covers the costs of the bet). The losses do not correlate with the function of advancing the balance. Let's use the formula of calculating the contribution:

<p>
    <img class="pimg" src="../../../images/PSS/12.jpg" width=400>
    <p class="pdesc">Figure 12. Wagers of the roulette</p>
</p>

To have a gain in this roulette betting on random color (with the probability of $^1/\_3$ each) you need the sum of all risks to be more than $1$. If we change the coefficient only for the green field, each $30$ bets will win you $9+8.75+x=30$ when the sum of the risks equals $1$. Yes, I accidentally invented mathematical expectation and called it *the coefficient of fortune of the system $A$*:

<p style="text-align: center">$K_A^f = \displaystyle\sum_{i:0 < r_{iA} < 1}{ρ_A^i}$</p>

<p style="text-align: center">$ρ_1=0.45*2=0.9; ρ_2=0.5*1.75=0.875; ρ_3=0.05*24.5=1.225$</p>

The $r_{iA} > 0$ statement is equivalent to $\exists r_{iA}$. The $r_{iA} < 1$ condition is needed to exclude $r_{AA}=1$ correlation and everything completely included to $A$ hence isn't depended on $B$ and leads to infinite value of contribution.

There is [*the theorem of hope*][6]: the component look so weak can make significant contribution. It is known to you as butterfly effect. Its combination with the theorem of anxiety gives us [*the theorem of strangeness*][6]: it is necessary to consider both improbable, but significant events, and probable insignificant. You should worry about what you will eat for dinner and how to save the Earth from asteroid falling equally. This is why the concept of risk is needed. It seems like in conditions of limited information you should make a set of values of risks of all related events and use the three-sigma rule.

To analyze strange systems, we need to introduce the concept of polar reflection and positivization. *Polar reflection* is reflection of a number from $1$ in $[0;1]$ and $[1; ∞]$ continuums, simply put, $\underset{—}{\overset{—}{x}} = \frac{1}{x}$. From this point of view, normalization and calculating the reminder in linear interpolation is squeezing, stretching or shift the series of numbers to $[0;1]$ continuum. And *positivization* is polar reflection to $[1; ∞]$ continuum. Let's do the following:

<p style="text-align: center">$\underset{—}{ρ_A^B} = ε_B\underset{—}{κ_A^B}$</p>

All values of $κ_A^B$ becomes more than or equal to $1$. The roulette is polarized, and besides, half-stable system (see below), so nothing changes for it. However, the value of $\underset{—}{ρ_A^B}$ always points to the importance of a component. For the regular coin the risks of heads and tails $≈ 1$, risk of falling on edge is $ε_B\underset{—}{κ_A^B} = \underset{—}{\overset{—}{\dot{∞}}} * 1 = \underset{—}{\overset{—}{\dot{∞}}}$ (infinitely small, or equal to conditional zero), hence it can be neglected. The algorithm of calculating the risks for any event may include recurring calculation of positivizated risk of $B$ for the components of $A$, and then a selection of the most valuable by the three-sigma rule for the next iteration.

To compare two variants of a system there is *the equivalence of efficiency*: for any $A$ and $B$ which are two variants of the system $C$, $A$ is more or equally efficient than $B$ if for each element of $C$ its contribution for $A$ is more than or equal to its contribution for $B$:

<p style="text-align: center">$(∀A,B:A,B∈\{x:x=f(C)\})ε_A≥ ε_В?(∀y:∃r_{yC})κ_A^y≥κ_B^y$</p>

## Chains

Find a correlation between the bulling and the grades. An absurd idea: some novice researchers formulate purposes and hypothesis like that. The correlation between the bulling and the set of all grades is the probability of having bulled in school generally, because all students have grades. This correlation is equal to the correlation between the school itself and bulling: 

<p>
    <img class="pimg" src="../../../images/PSS/13.jpg" width=400>
    <p class="pdesc">Figure 13. Exclusion mistake</p>
</p>

Let's consider the more general case. In the figure below, $μ$ is infinitesimally correlation appearing when we divide objects into an abstract types by some parameter (see [nouns of patterns and adjectives][6]). The amount of items of different colors equals conditional infinity ($\dot{∞}$), and the correlation from it equals $\underset{—}{\overset{—}{\dot{∞}}}$. The correlation calculates by the triangle rule similar to the vector sum. In a particular example, $γ$ is also equal to $\underset{—}{\overset{—}{\dot{∞}}}$ (see [more about $\dot{∞}$ and $\underset{—}{\overset{—}{\dot{∞}}}$ signs][11]). Notice that the $β_i$ probabilities are prior:

<p>
    <img class="pimg" src="../../../images/PSS/14.jpg" width=400>
    <p class="pdesc">Figure 14. The triangle of correlations</p>
</p>

Let's call the links with correlations equal to $1$ to the both directions *stable*, to the one direction *half-stable*, and not in any direction *unstable*. Let's also introduce the notation of link: $l_{ij}=r_{ij}|r_{ji}$. Multiplication is working for the triangle of half-stable links. There is the general case for the triangle of unstable links too:

<p>
    <img class="pimg" src="../../../images/PSS/15.jpg" width=400>
    <p class="pdesc">Figure 15. The theorem of triangle</p>
</p>

The correlation that is close to $1$ points to the probabilistic mistake of division or exclusion (see below): the objects in the basket are included into the set of apples, the grades are included in the set of the school. But this "mistakes" can be used to differentiate the sets:

<p>
    <img class="pimg" src="../../../images/PSS/16.jpg" width=400>
    <p class="pdesc">Figure 16. The intersection of three sets</p>
</p>

The amount of sets is equal to known $2^n-1$, but behind the formula of the amount of the links there is much more entertaining combinatorics. It is equal to the sum of unstable links, which equals the amount of combinations of choosing $2$ sets from $n$ possible, and half-stable links, which equals the sum of the products of the series of quasi orbital numbers and the incomplete series of binomial coefficients. The amount of correlations is twice as much. Look at the scheme for $n=4$:

<p>
    <img class="pimg" src="../../../images/PSS/17.jpg" width=400>
    <p class="pdesc">Figure 17. The intersection of four sets</p>
</p>

Different colors indicate the sets and links with different order. The number of order of the set is the amount of initial sets which this set intersects. The number of the order of the link is the larger of the orders of two sets it is connected to. The initial sets (blue) are $1$-order and has $\frac{n(n-1)}{2}=C_n^2=6$ $1$-order links among themselves. The amount of higher-order sets and links obeys the following regularity:

<p>
    <img class="pimg" src="../../../images/PSS/18.jpg" width=400>
    <p class="pdesc">Figure 18. Quasi orbital numbers</p>
</p>

$56$ links total. The physical sense is: in the $n$ line of the Pascal's triangle the first number is the union of all sets, and is not considered in our problem. The second number is the amount of the initial sets. Their links are unstable, hence the amount of links equals the amount of combinations of choosing $2$ sets from $n$. And the rest numbers in the line are the amounts of higher-order sets, each making $Orb(k)$ half-stable links. Consider the $4$-order set (green), which is only one here. It is connected to every other set, hence it has $2^n-2$ links. I called such numbers quasi orbital because of the similarity (but not match) with numbers of electrons in atom orbitals. 

This means there is $56$ *quanta*, the $1$-length thoughts, binding $4$ unstable sets. They can be divided into categories:

1) $A$ is related to $B$ — $A\sim{B}$ (the $1$-order correlation);
2) The part of $A$ is $B$ — $A⊃B$ (increasing correlation from $n$-order to $n+k$-order set);
3) $A$ is a part of $B$ — $A⊂B$ (decreasing correlation from $n+k$-order to $n$-order set).

Number $56$ is the amount of links in a complete set of truthful conclusions we can make from the initial sets. The *conclusion* is the creation of new link. The $n$-order conclusion makes $n$-order links:

1) $∃x: x∈A, x∈B ⇒ A\sim{B}$ — $1$-order conclusion;
2) $A\sim{B} ⇒ ∃D: D⊂B, D ⊂А$ — $2$-order conclusion;
3) $D=A∩B, E=A∩C, F=B∩C ⇒ ∃G: G⊂D, G⊂E, G⊂F$ — $3$-order conclusion.
$3$ missing $3$-order links makes as follows: $D⊂А, G⊂D ⇒ G⊂A$.  

And so on. The series of numbers with amounts of possible conclusions from $n$ sets is growing very rapidly: $\{3,15,56,190,617,1953,6078,18696,57047,173107,523316,1578018,4750293,…\}$, and that's just the simplest thoughts.

## Mistakes

The system with a set of conclusions is *complete* if there are all truthful links created in it. It is also *truthful* if every thought in it is truth. *Truth* is a thought not containing mistakes. This mistakes can be probabilistic, [emotional][6], and [linguistic][7]. Here we are talking only about the first. Probabilistic mistakes can be:

<p>
    <img class="pimg" src="../../../images/PSS/19en.jpg" width=400>
    <p class="pdesc">Figure 19. Classification of probabilistic mistakes</p>
</p>

There are not all possible links created in our system. For $n=3$, $C_{2^n-1}^2-N(l_{ij})$ are missing. These are false links:

<p>
    <img class="pimg" src="../../../images/PSS/20.jpg" width=400>
    <p class="pdesc">Figure 20. False links</p>
</p>

False links make creation mistakes. In addition, the creation mistake can be an increased correlation. If the pair of correlations becomes half-stable $1|\overset{—}{k}$ ($\overset{—}{k}$ means $0\le n \le1$) instead of $\overset{—}{n}|\overset{—}{k}$, this will be an inclusion mistake. The transformation in reverse order is an exclusion mistake. The questions can define the type of the mistake are «Which type of link?» and «What happened?», and possible answers are the first column and row of the table, respectively.

The $1|1$ link is a fusion mistake if it is false, $0|0$ is likewise division mistake. The fusion mistake made from $\overset{—}{n}|\overset{—}{k}$ is called *stereotype*. «All Italians eat pizza» is false, because there are Italians who don't like it and non-Italians who do. Now we fixed two inclusion mistakes. Actually, stereotypes are [stereopatterns][7] (it's a pun).

Mistakes can be made not only by false conclusions (for example, in the result of [madness][6]), but also by gaining experience. Let's consider an example (there will be one more below).

*Fusion mistake*: math is actually math and logic. I devoted to this mistake [a whole article][4]. At the first glance it seems like it is an inclusion mistake, but actually we consider that any mathematical system has logic, and also there can be logic without math. It's not clear why we can't mistakenly call it all logic. Separately, math is a field of knowledge studying non-discrete values. And we think otherwise because we invented logic first, integers then, their regularities (arithmetic) next, and only then irrational and complex numbers.

All probabilistic mistakes that were made by gaining experience are special cases of survivorship bias: you need to get more new information to fix it. The knowledge of regularities, stable correlations, eliminates this need. The laws of logic are these regularities, too.

## Recursions

To consider another mistake, we need to take a step back to the apples first. The statement «There are bones in the apple» lets us decompose the set of apples different ways. This opens *the theorem of fractality* of logic: if several subsets of the set contains the same subset, it is useful to consider them as a separate set.

<p>
    <img class="pimg" src="../../../images/PSS/21.jpg" width=400>
    <p class="pdesc">Figure 21. Every apple contains a bone</p>
</p>

It is the consequence of *the fundamental theorem* of logic: things can be combined on the basis of common features. We can abstract from a particular object and consider the bones of all apples in the Universe as one object because of the property of fractality. In the other hand, we can unite apples with the other objects and form metas. Metaphor is moving (see. [operations][15]) links to another object in a set of common feature called meta. This is why the fact the eyeball is called eyeapple in Russian is not surprising:

<p>
    <img class="pimg" src="../../../images/PSS/22.jpg" width=400>
    <p class="pdesc">Figure 22. Eyemelons</p>
</p>

*Division mistake*: probability and correlation are one and the same. This mistake was made because we approached to this discovery from two sides, inventing these concepts separately, and have not connected all links yet. This is why we use the laws of probability so easily when we talk about correlations. So there is the famous Bayes' theorem:

<p>
    <img class="pimg" src="../../../images/PSS/23.jpg" width=400>
    <p class="pdesc">Figure 23. Bayes' theorem</p>
</p>

*Chance* $c$ is a fractional part of half-stable link. We talk about chances when all considered links are related to one system, because $c_i = r_{Si}$. This is the reason why chance can be related only to types. The Bayes' theorem contains one another theorem in the denominator, which allows simplifying the formula: knowing the chance of unstable set and correlations from it and its antonym to the other unstable set, you can calculate a chance of this set in a system.

Half-stable correlations from a system create types with the sum of chances equal to $1$, combinations of parameters make patterns, and unstable sets connected to the other systems allow calculating an efficiency of this system. This implies a few types of recursion.

*Stable recursion* allows uniting many objects into one. If there are no links between this object and any other, this means it doesn't depend on external parameters. [Reality][15] can be the example. The system containing only stable links is called formal (see [The caterpillar of formality][2]).

<p>
    <img class="pimg" src="../../../images/PSS/24.jpg" width=400>
    <p class="pdesc">Figure 24. Stable recursion</p>
</p>

*Half-stable recursion* is the classical recursion of the sets — recursion of types:

<p>
    <img class="pimg" src="../../../images/PSS/25.jpg" width=400>
    <p class="pdesc">Figure 25. Half-stable recursion</p>
</p>

And the examples of *unstable recursion* we have seen above, when discussed the bones of the apples and the objects with one link that can lie between students, schools, cities and countries:

<p>
    <img class="pimg" src="../../../images/PSS/26.jpg" width=400>
    <p class="pdesc">Figure 26. Unstable recursion</p>
</p>

The combination of these types of recursion makes [linguistic model][7], from which all the parts of speech follow (green and purple colors of the links denote its creation and destruction, respectively):

<p>
    <img class="pimg" src="../../../images/PSS/27.jpg" width=400>
    <p class="pdesc">Figure 27. Parts of speech</p>
</p>

Accordingly, the Probabilistic-Strategic Schemes are the combination of stable and unstable, rational and irrational, which lets us think, and also reflecting all the laws of information systems, many of which I will reveal in the next articles.

## Summary and miscellaneous

PSS has many properties of perception neural networks with its own differences:

1) Despite the chaotic, the direction of time is explicitly stated and can be reversed;
2) Any group of neurons can be comprehended as a set (hence *neuron* is an atom of the information system);
3) Any sets can be linked, and the connections or the memory of its absence is what creates the experience; 
4) It seems like creation of static network solving problems, like text recognition in a photo, is a simple task: you have to define a system of distinguishing different symbols, the rules of reading, and also create [*the focus algorithm*][15]: find what is a text, divide it into paragraphs, find the first line and the first letter;
5) To solve more difficult tasks, like estimation of probabilities of scenarios of the future, meaningful speech, and solving everyday problems, you need [*the algorithms of thinking*][15], requiring much more power.  

I think that besides combining several branches of mathematics and logic, PSS combine different thickness graphs and the way of thinking which is using by detectives to investigate crimes in cool films (and not just), when they hang photos and notes crossed by red threads.

There is another way to graphically denote correlations, where every type of link is clearly defined, and there is no need for so much arrows: 

<p>
    <img class="pimg" src="../../../images/PSS/28.jpg" width=600>
    <p class="pdesc">Figure 28. Two ways of denoting</p>
</p>

Also, we need to talk about the common thesis «Correlation is not causation». I even saw «Correlation means coincidence». You have all seen this [website][Fool trends]. This is not correlations. This is the plots of trends coincidence. The whole chains of coincidences of the slopes of the segments between two points. Well, yes, this is possible by the law of averages, and the statement that two objects are linked because of the same number sounds numerological. Moreover, the axis have different units of measurement, and the plots can be squeezed or stretched, what allows making coincidences. True correlations make sense. Applicable to the Bayes' theorem, if we know the apple belongs to $A$, and $r_{AB}$ correlation, this means the probable appearance or non-appearance of some Schrödinger's apple in the $B$ set. The probability rules the world:

<p>
    <img class="pimg" src="../../../images/PSS/29.jpg" width=400>
    <p class="pdesc">Figure 29. Schrödinger's apple</p>
</p>

Causal relationship doesn't exist. I mean, thinking of one thing as a reason and the other one as a result is a bit incorrect, because the skill of reversing the time is extremely useful. Let's consider a quite difficult example: the trees sway because the wind blows. It seems like the reversed conclusion «The wind blows because the trees sway» is absurd, but, firstly, this conclusion is possible in case of stereotype (that is how it works) hence it can be generated by the lack of experience, and secondly, fixing of survivorship bias goes to show that the conclusion sounds different: «If the trees sway, the reason is most probably wind». Our knowledge of the wind also speaks that the trees always sway when the wind is blowing, but it doesn't mean stereotype. Why? We confuse wind as a noun and its blowing as a verb, and there is a stable link between two actions in contrast from the objects, which creates a function (see [time][7]): 

<p>
    <img class="pimg" src="../../../images/PSS/30.jpg" width=400>
    <p class="pdesc">Figure 30. Action link</p>
</p>

And already inside this function the direction of time can be set, what makes [functional dependence][15].

## Homework

In this part, I want to ask professionals and interested people questions which are important to answer.

1) It is known that to solve tasks facing PSS, analog computers can be used. Digital computers took its attention because of better applicability to the tasks of the mid-20th century, but now analog computers are encouraging and multitasking. How can we specify operations described in the article on analog computer? Can we operate the sets, in other words, make a Turing machine, using only an analog computer? How can the effect of accumulation of measurement errors can be minimized?
2) Can we merge analog and digital computers? How this system will be organized? How the command transmission from one computer to another will be organized? By the way, can video cards accelerate analog calculations, and if they can, how much?
3) What minimal power is tentatively needed to make systems described in paragraphs 4 and 5 of the list of differences from neural networks on a computer?
4) How can we use different algorithms of graph optimization here? What other laws of statistics are applicable to PSS?
