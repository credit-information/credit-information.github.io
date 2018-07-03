---
layout: default
title: Home
---

<header>
<h1>The Equilibrium Effects of Asymmetric Information:<br />
Evidence from Consumer Credit Markets</h1>
<p>We combine machine learning techniques with a large-scale policy change to study the equilibrium effects of information asymmetries in credit markets. In 2012, Chilean credit bureaus were forced to stop reporting past defaults for 2.8 million individuals with relatively low default amounts. These individuals made up 21% of the country's adult population and approximately 67% of borrowers in default. Using panel data of the universe of bank borrowers in Chile and access to the deleted registry information, we measure exposure to the deletion policy by constructing cost predictions with and without the deleted data. We then estimate the effects of exposure to changes in predicted costs using a difference-in-differences design that compares changes in borrowing over time for borrowers at different points in the exposure distribution. We find that deletion reduces predicted costs the most for poorer defaulters with limited borrowing histories, and raises predicted costs the most for non-defaulters with similar backgrounds. Borrowing is negatively and monotonically related to increases in predicted costs, with an elasticity of -0.14. Losers from the policy outnumber winners, and in aggregate, the effect of deletion was a sustained reduction in borrowing by 9% relative to baseline. We use our procedure to simulate the effects of counterfactual deletion policies such as the elimination of data on gender or additional default records, and show that both types of deletion reduce overall borrowing with largest drops for lower-income individuals and women.</p>
</header>

<ul class="actions fit">
<li><a href="http://faculty.chicagobooth.edu/seth.zimmerman/research/papers/LNOZ_2017_06_15.pdf" class="button special fit">Article</a></li>
<li><a href="http://faculty.chicagobooth.edu/seth.zimmerman/research/papers/LNOZ_Online_Appendix.pdf" class="button fit">Online Appendix</a></li>
</ul>

<hr>


# Motivation

**Credit registries collect and disseminate repayment histories, but with *limits***. For example, there is limited duration of bankruptcy and default flags.
The reasons behind this include privacy, fairness and insurance against defaults, among others.
Recent research on this topic shows that **borrowing increases for beneficiaries of these limits.**

Is there a free lunch?
What happens to non-beneficiaries and in aggregate?


# This paper

**What are the aggregate and distributional effects of limits to credit information on consumer borrowing?**

In order to tackle this question, we exploit a large scale "clean-slate" policy change in Chile, where credit registries were forced to stop reporting defaults for most defaulters (21% of adults).
This meant that banks were unable to tell if a person was in default.
Using data on the universe of bank borrowers, we apply machine learning techniques and a difference-in-difference strategy to answer the main question.
We find that:

1. Policy increases (decreases) expected costs for borrowers not in default (in default)
2. Reduced (increased) borrowing among non-defaulters (defaulters), with a net effect of a 4% aggregate drop in new borrowing
3. Interpret with simple adverse selection framework, welfare loss under several assumptions for banking sector mark-ups.


# Dive deeper

{% include tiles.html %}
