[This](https://www.sciencedirect.com/science/article/pii/S2213260018302790) paper, in which John Laffey and Brian Kavanagh discuss some of the issues in critical care trials, was published recently in Lancet Respiratory Diseases.  Their main point, which seems sound, is that one of the reasons for the large number of "negative" (urgh) trials in critical care is that conditions that trials seek to address, such as sepsis and acute respiratory distress, are syndromes with very heterogeneous populations, which result from a variety of mechanisms.  Hence any single treatment, which targets one physiological pathway, is unlikely to be beneficial to all patients.  That means that a trial recruiting the whole population will contain a lot of people who have no chance of benefitting from the intervention, which will reduce the number of people who have good outcomes and reduce the trial's ability to find a difference.

What I wanted to comment on, though, was some of the statistical aspects.

First, the title.  We should really stop talking about "negative" trials.  For one thing, it's bad terminology because they don't mean trials where the treatment effect was negative, they mean trials that didn't find "statistical significance" (almost always p < 0.05).  (I won't get into whether p < 0.05 is a sensible criterion or goal for a trial now - you can probably guess what I think) For another, we need to stop inappropriately dichotomising evidence.  Trials aren't positive or negative; there is a whole range of possible results with different implications for clinicians and patients.   And in the real world, treatments don't "work" or "not work"; they might help some patients a lot, some a little and others not at all (as Laffey and Kavanagh argue later in this very paper).  Reducing a potentially complex situation to a naive dichotomy helps nobody.  So I really don't like the idea of talking about "true" and "false" hypotheses, treatments "working" and "not working," and "positive" and "negative" trials.  For convenience, though, I'm going to stick with it for this post.  Just keep in mind that it's a simplification, but it serves to illustrate a point.

So, on to what I actually wanted to say.  The second paragraph of the paper begins:

On a statistical basis, it is unlikely that most negative RCTs represent fair conclusions...

That's a surprising statement. They go on to give their basis for saying it:

... if each hypothesis tested had the same a priori probability that was as low as a coin toss, we would expect 50% of RCTs to be positive. The likelihood that 19 out of 20 consecutive such coin tosses would be negative is less than 1 in half a million (1 ÷ 219 ).

They then argue that the proportion of correct hypotheses that are tested should be higher than 50%:

In fact, most a priori hypotheses should have substantially better than even odds of success, as it seems implausible that a hypothesis refined through extensive testing should have only the same chance of being effective as a coin toss.

Starting from the beginning of this, the statement that if 50% of hypotheses tested are true, then 50% of RCTs should be positive is just wrong.  We definitely wouldn't expect to see that.  The important thing they are ignoring is the error rates in statistical testing.  Typically, studies are designed around a null hypothesis significance test with something like Type I error rate of 5%, and (hoped-for) Type II error rate of 20%.  That means when the null hypothesis is true (i.e. exactly zero difference in reality between the treatment arms), we expect 5% of a long run of replications to yield a significant result.  So you'll get 5% positive regardless of the proportion of hypotheses that are actually true.  Of the hypotheses that are tested that are actually true, you'll get a significant result in a proportion equal to the power of the test.  So that's always going to be less than 100%, and sometimes a lot less.  And remember, this is about the power of the test with the treatment effect that actually exists, not the one that was assumed in the sample size calculation.  We know that lots of trials overestimate the treatment effect in their sample size calculation, so power is often lower than they claim.  So if 50% of hypotheses are actually true, and you run 1000 trials with power 80%, and a 5% Type I error rate, you'll get something like this:


	
	Reality	Total

	
	Treatment works	Doesn’t work	

Test	Significant	400	25	425

	Non significant	100	475	575
Total	
	500	500	1000

So that's 425/1000 positive, which is not 50%, and 25/425 of those are false positives.  You're always going to get them because of the Type I error rate - when the treatment has no effect you're still going to find some positives.  But in reality, many trials have less than 80% power, sometimes a lot less, because the sample size may be smaller then planned, outcomes may be rarer than expected and treatment effects smaller.  So if the trials have 50% power, we get something like:


	
	Reality	Total

	
	Treatment works	Doesn’t work	

Test	Significant	250	25	275

	Non significant	250	475	725
Total	
	500	500	1000

That's 27.5% "positive," a lot less than 50%, but might be a bit more like what we might expect in the real world, if 50% of hypotheses are correct - which they probably aren't.

Second major point: Laffey and Kavanagh seem to think that it's unlikely that the proportion of correct hypotheses is as low as 50%.  My intuition is the opposite: to me, 50% sounds way too high.  There are lots of ways that interventions can get to look interesting enough for someone to propose evaluating them in a trial.  Usually there is some combination of animal and laboratory studies, a plausible-sounding mechanism, observational studies and preliminary trials (maybe with a meta-analysis).  But we know there are huge problems with a lot of the medical literature - publication bias, p-hacking, forking paths and researcher degrees of freedom, and poor research and statistical practices - so it wouldn't be surprising to me if a lot of the "hypotheses refined through extensive testing" are actually wrong.  I should say I'm thinking more of academic trials here than the pharmaceutical industry, where drug development programmes are typically more structured.  I'm not aware of any good estimates of how many hypotheses might be true (for one thing, defining "true" is hard, maybe impossible, for the reasons given above) but I'd be interested to hear of any.  [my crude back-of-an-envelope attempt from a while back is here]

So, finally, to the title.  They're arguing the opposite of John Ioannidis's famous 2005 paper; Ioannidis said a lot of positive studies were false positives, whereas Laffey and Kavanagh maintain that most negative studies are false negatives.  Probably they can't both be right simultaneously!  I suspect that in fact that false negatives are a smaller problem than they think, because the proportion of truly effective treatments that get tested is probably low. But I think Laffey and Kavanagh's major point, about the heterogeneity of populations and treatment responses, is sound, and is an important challenge for the design of trials in this area.  Off-the-shelf traditional designs probably aren't going to work well.  Instead, we need the design of trials to be informed by understanding of the biological mechanisms involved, how interventions are likely to affect them, what that means for patients' clinical outcomes, and how patients with different underlying disease processes can be identified.  That all sounds very challenging.
