## Plenary session: BILCAP and dichotomania

*Disclosure: the BILCAP trial was run by the unit where I currently work, though I had no involvement in it.*

Plenary Session podcast number 1.52 ([here](https://soundcloud.com/plenarysession)) was about the BILCAP trial ([Capecitabine compared with observation in resected biliary tract cancer (BILCAP): a randomised, controlled, multicentre, phase 3 study](https://www.thelancet.com/journals/lanonc/article/PIIS1470-2045(18)30915-X/fulltext)), which was published recently in Lancet Oncology.  The podcaster (is that a word?), Dr Vinay Prasad, really didn’t like it, but it raises a few interesting issues about interpretation of trials.  Here I'm not aiming to rebut all of the points or defend BILCAP particularly, but more to discuss the general issues (although I do think that some of the criticisms levelled at the trial are not very reasonable).

The main objections raised in the podcast were around interpretation of the result for overall survival, which found a hazard ratio of 0.81 (95% CI 0.63 to 1.04) in favour of capecitabine, with a p-value of 0.097.  So, if you're a fan of null hypothesis significance tests, that's a non-significant result, and if you like spurious dichotomies, it's what some people like to call a "negative" trial.  However, the paper suggests that capecitabine could be beneficial and used as a standard of care, based on the apparent size of the beneficial effect, the per-protocol analysis (which was "significant"), benefit in recurrence-free survival, and lack of alternative therapies. Apparently a lot of the publicity around this trial in the clinical world has generally viewed it as a positive result and potentially a useful treatment. Dr Prasad takes issue with this interpretation, arguing that this should be seen as a "negative" study. Here's a quote from the podcast:

>"if one looks at the totality of the evidence of biliary tree cancer in the adjuvant space, one would conclude overwhelmingly that this is a negative trial. All of the active agents, of which no-one would think that one is better than the other, have failed in randomised controlled trials. One of them has a p-value of 0.49, one of them has a p-value of 0.7, and one of them has a p-value of 0.09 (sic).  That because of the play of chance, that's not because capecitabine is the miraculous drug among the group, OK. You're interpreting it incorrectly."

So the argument is that there have been other trials of agents used in a similar way to capecitabine, which have not shown any suggestion of benefit, and there isn't any a priori reason to think that capecitabine is going to be better than any of these others.  So the fact that it's come out with a p-value that's close to significance is probably just chance; non effective therapies will sometimes have effects that look promising, just by chance, and he thinks we're looking at one of those here.

Well, maybe. That's certainly one possibility. But it's also possible that the observed differences aren't just chance, and patients (or at least some patients) really do better with capecitabine - like the results suggest.  The problem is that it's not easy to distinguish between these possibilities; it's quite plausible that the same data could result from capecitabine being helpful, at least for some people, or doing very little, but looked reasonably promising by chance.  I don't think it's very reasonable to say definitively that one of those explanations is incorrect - we really don't know.  The problem here is that we're trying to impute something - the probability that capecitabine has a useful treatment effect - from something else - the p-value, which is the probability of getting a difference at least as big, if the true difference is zero.  It's the old old problem - p-values and significance testing just isn't addressing the question that we want to answer.




Now a point about statistical analysis plans. One of the issues mentioned was the lack of a prespecified statistical analysis plan; the podcast quotes the paper as saying "there was no prespecified statistical analysis plan when the study started," (which it does) and, later on, says "they don't have a pre-planned statistical plan - they're playing fast and loose with that."  This is taken as evidence that the study wasn't conducted rigorously, with the suggestion that the analyses presented may have been selected to make the study as positive as possible.  But I don't think that's correct.  There may not have been a statistical analysis plan when the study started, but there definitely was one before the data were analysed - it's referred to in the paper and is included in the appendix.  It's actually not at all unusual for a statistical analysis plan to be written while the study is going on, but before the data are finalised.  In fact, I'd say this is normal practice, and it would be unusual to write the analysis plan before starting data collection - for the very sensible reason that if you try to anticipate all of the issues that will arise that need to be taken into account during the analysis, you will fail, and will have to make extensive modifications to the analysis plan later.  It is in any case a bit of fantasy to think that the analysis can be prespecified in exhaustive detail in advance. For example, what happens if the analysis method that you prespecified turns out not to work very well for the data that the trial collects?  Should you plough on regardless, using a poor method, because that's what was prespecified, or change to something else that works better?  To my mind, getting sensible answers is the goal here, and it's fair enough to change the approach with that aim in mind, if what you originally intended to do is going to be misleading.




The podcast refers to a paper in the BMJ a few years ago that showed why the common description of results that didn't quite attain statistical significance as having a "trend towards significance" is erroneous.  The usual belief is that a p-value close to 0.05 is likely to get over the threshold if you add more data - the reason that you didn't get the magic p<0.05 first time could be due to a smaller than expected sample size, lower than expected power, or something like that.  But in fact that's wrong - if you get a p-value of 0.097 in one experiment, it doesn't necessarily mean that there's a "significant" effect in there trying to get out.  If you add more data or do the experiment again, it's quite likely that you'll get a p-value that's further from significance.  So quite right that p=0.097 doesn't mean that p < 0.05 would be attained if only we had more data.  But what the podcast doesn't say is that this also applies to significant p-values.  If you do a trial and get a "significant" result, it's actually much more likely than most people would think that a replication will be non-significant (see for example this paper).  The point is that p-values are noisy (as Andrew Gelman says very often), and p-values for replications can be very different from the original study.  So whether or not we get significance in one replication of an experiment doesn't really tell us much about whether there is a "real" effect there.  So the important point is that while it's correct that a p-value close to 0.05 doesn't necessarily mean that any additional data or replication are likely to hit p<0.05, it's also true that achieving p<0.05 doesn't necessarily mean that any additional data or replication will find the same.  P<0.05 isn't proof of anything but people often behave as though one instance of p<0.05 should settle a question for ever.  It doesn't.




Here's another quote from the podcast.

>they [the study authors] seem to have a habit of saying that an effect size is large when it's non significant and thus, should not really be commented upon.

Ugh.  He probably doesn't really mean this, but once again: non-significance doesn't mean an effect size is zero, or unimportant, or anything like that.  That's one of the fundamental misinterpretations of significance testing. Effect sizes can easily be huge and "non-significant," or tiny and "significant." The p-value is just about the probability of getting more extreme data in a long sequence of replicates, if there is really no difference between the treatments.  That really is all.  It doesn't give us anything like the probability of any underlying treatment effect, although frequently misinterpreted in that way.

Listening to the podcast, it struck me that it came very close, without saying it, that what was really needed here was Bayesian analysis. The podcast comes tantalisingly close (at around 9'15'' and onwards) to talking about priors for trials in this setting (it speaks of pre-test probabilities of effectiveness of drugs).  I think Bayesian methods could help here, in two ways.  First, they could quantify the probability of benefit. Without doing the analysis you can't say for sure, but it's likely that a Bayesian reanalysis would give something like a 90% probability that the effect of capecitabine was positive (it would depend on the prior, covariates, model used, etc).  I think everyone would say that was pretty positive, but whether it's positive enough to use, given side effects and so on, I don't know.  I guess there would be a range of views and some people would think it worthwhile, others wouldn't.  And that's fine - it seems an entirely reasonable interpretation, much better than having to force it into one of the extremes of "should be standard of care and used universally" or "ineffective," which is exactly where interpretation based on statistical significance leads us.

This also raises an important point for clinical practice.  The results of BILCAP suggest that capecitabine was better. Not "significantly" (i.e. it wasn't better by enough to get a p-value of less than 0.05) but a pretty high probability of superiority (someone needs to do the Bayesian analysis to quantify it).  So are you going to choose capecitabine or standard care, which you are now pretty sure is inferior? (leaving aside the issues of toxicity and effects on other outcomes, for the sake of simplicity).  Are we failing to introduce improvements to treatments by requiring that new interventions have to have p<0.05 to be considered worthwhile?

The other way Bayesian analysis would be helpful is by including information from previous trials, via an informative prior.  There were two earlier trials (both "negative"), which were mentioned in the quote above.  I don't know anything about the drugs or whether it is reasonable to expect their treatment effect to be related to that of capecitabine, but that seems to be the implication of the podcast; a couple of drugs have already been tried, they weren't effective, so that lowers our expectation that the next drug will be beneficial.  If that's the case, it makes sense to incorporate the existing trial information into the prior for the new trial.  The existence of so-called "negative" trials would probably make the prior more sceptical - that certainly seems to be Dr Prasad's view - which would attenuate any benefit in the next trial conducted.  I don't know if this would be at all sensible in this example, or how much difference it would make to BILCAP's results; maybe the underlying biology makes a sceptical prior sensible, maybe it doesn't, I don't know enough to say.  But my point is just that Bayesian analytical methods give us a formal way of incorporating into the analysis the informal thought processes that we all apply to results anyway - as the podcast illustrates.

Towards the end of the podcast, Dr Prasad talks about the recent “abandon statistical significance” paper by Amrhein, Greenland and McShane.  He argues, as did John Ioannidis, that if we take away the standard of statistical significance and don’t have any “objective” standard for considering a finding “real,” it will allow anyone to claim any result as an important finding that should be used to determine clinical practice.  So if we keep the p<0.05 standard, despite the well-known problems with it, at least we will know that the treatment achieved a baseline standard of evidence sufficient for it to be used.  Or I think that’s the argument.

I have to say that I find it surprising that people are seriously using that argument.  One of the biggest problems with statistical significance is the dichotomisation of evidence, and this is exactly my biggest issue with the Plenary Session dissection of BILCAP.  Over and over again, BILCAP is referred to as a "negative study," because it didn’t achieve a p-value of less than 0.05. But how does it make sense for there only to be two possible interpretations of a clinical trial - "negative" and "positive"?  All clinical trials are complex things that are trying to find out stuff about a complex world.  Of course there are going to me many shades of grey in their interpretation.  I think we would all agree that results of BILCAP were more positive than if it had found, say, a hazard ratio for overall survival of 1.10 with 95% compatibility interval 0.74 to 1.64 - but both of these results would be "non-significant" and "negative studies."  And, as mentioned above, p-values are noisy, so a study that gets p=0.097 one time around might easily get p=0.04 in the next replicate. Or p=0.20.  Those could all result from exactly the same underlying treatment effect. Dichotomising the results based on a p-value really isn't helping us to get at that.

One of the main issues here is that we are trying to make decisions about something we care about (whether the treatment effect of capecitabine is big enough to be clinically useful) using a completely different piece of information (the probability of getting a treatment effect as big or bigger than the one we actually got, if the true difference is zero).  Like trying to eat soup with a fork, or something.  Possible, but maybe not the best way of going about it.

Anyway, if you've made it to the end, thanks for reading. If you have any comments please add them below.
