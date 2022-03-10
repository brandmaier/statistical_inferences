

# Effect Sizes {#effectsize}

Effect sizes are an important statistical outcome in most empirical studies. Researchers want to know whether an intervention or experimental manipulation has an effect greater than zero, or (when it is obvious an effect exists) how big the effect is. Researchers are often reminded to report effect sizes, because they are useful for three reasons. First, they allow researchers to present the magnitude of the reported effects, which allow researchers to reflect on the **practical significance** of the  effects they report, in addition to the *statistical* significance. Second, effect sizes allow researchers to draw meta-analytic conclusions by comparing standardized effect sizes across studies. Third, effect sizes from previous studies can be used when planning a new study in an a-priori power analysis.

A measure of effect size is a quantitative description of the strength of a phenomenon. It is expressed as a number on a scale. For **unstandardized effect sizes**, the effect size is expressed on the scale the measure was collected on. This is useful whenever people are able to intuitively interpret differences on a measurement scale. For example, children grow on average 6 centimeters a year between the age of 2 and puberty. We can interpret 6 centimeters a year as an effect size, and many people in the world have an intuitive understanding of how large 6 cm is. Where a *p*-value is used to make a claim about whether there is an efect, or whether we might just be looking at random variation in the data, an effect size is used to answer the question how large the effect is. This makes an effect size estimate an important complement to *p*-values in most studies. A *p*-value tells use we can claim children grow as they age; effect sizes tell us what size clothes we can expect children to wear when they are a certain age, and how long it will take before their new clothes are too small. 

For people in parts of the world that do not use the metric system, if might be difficult to understand what a difference of 6 cm is. To facilitate a comparison of effect sizes across situations where different measurement scales are used, researchers can report **standardized effect sizes**. A standardized effect size, such as **Cohen's d**, is computed by dividing the difference on the raw scale by the standard deviation, and is thus scaled in terms of the variability of the sample from which is was taken. An effect of d = 0.5 means that the difference is the size of half a standard deviation of the measure. This means that effect sizes are determined both by the size of an effect, and the size of the standard deviation, and difference in a standardized effect size can be caused by a difference in the size of the unstanderdized effect, or by a difference in the standard deviation. 

Standardized effect sizes are common when variables are not measured on a scale people are familiar with, or are measured on different scales within the same research area. If you ask people how happy they are, an answer of ‘5’ will mean something very different if you asked people to answer on a scale from 1 to 5 than if you asked them to answer on a scale from 1 to 9. Standardized effect sizes can be understood and compared regardless of the scale that was used to measure the dependent variable. Despite the ease of use of standardized effect size measures, there are good arguments to report and interpret unstandardized effect sizes wherever possible [@baguley_standardized_2009].

Standardized effect sizes can be grouped in two families (Rosenthal, 1994): The d family (consisting of standardized mean differences) and the r family (measures of strength of association). Conceptually, the d family effect sizes are based on the difference between observations, divided by the standard deviation of these observations. The r family effect sizes describe the proportion of variance that is explained by group membership [e.g., a correlation (r) of 0.5 indicates 25% (r2) of the variance is explained by the difference between groups]. These effect sizes are calculated from the sum of squares (the difference between individual observations and the mean for the group, squared, and summed) for the effect divided by the sums of squares for other factors in the design.

## Effect sizes

What is the most important outcome of an empirical study? You might be tempted to say it’s the *p*-value of the statistical test, given that it is practically always reported in articles, and determines whether we call something ‘significant’ or not. However, as Cohen @cohen_things_1990 writes in his 'Things I’ve learned (so far)':

>I have learned and taught that the primary product of a research inquiry is one or more measures of effect size, not *p*-values.

Although what you want to learn from your data is different in every study, and there rarely is any single thing you always want to know, effect sizes are a very important part of the information we gain from data collection. 

A measure of effect size is a quantitative description of the strength of a phenomenon. It is expressed as a number on a scale, and which scale is used depends on the effect size measure that is used. For **unstandardized effect sizes**, we can use a scale that people are very familiar with. For example, children grow on average 6 centimeters a year between the age of 2 and puberty. We can interpret 6 centimeters a year as an effect size. It is obvious an effect size has many benefits over a *p*-value. A *p*-value gives an indication that it is very unlikely children stay the same size as they become older – effect sizes tell us what size clothes we can expect children to wear when they are a certain age, and how long it will take before their new clothes are too small. 

One reason to report effect sizes is to facilitate future research. It is possible to perform a meta-analysis or a power analysis based on unstandardized effect sizes and their standard deviation, but it is easier to work with standardized effect sizes, especially when there is variation in the measures researchers use. But the main goal of reporting effect sizes to reflect on the question whether the observed effect size is meaningful. For example, we might be able to reliably measure that on average 19 years olds will grow 1 centimeter in the next year. This difference might would be statistically significant in a large enough sample, but if you go shopping for clothes when you are 19 years old, it is not something you need care about. Let's look at two examples of studies where looking at the effect size, in addition the its statistical significance, would have improved the statistical inferences. 

## The Facebook experiment

In the summer of 2014 there were some concerns about an experiment Facebook had performed on its users to examine ‘emotional mood contagion’, or the idea that people’s moods can be influenced by the mood of people around them. You can read the article [here](http://www.pnas.org/content/111/24/8788.full). For starters, there was substantial concern about the ethical aspects of the study, primarily because the researchers who performed the study had not asked **informed consent** from the participants in the study (you and me), nor did they ask for permission from the **institutional review board** (or ethics committee) of their university.

One of the other criticisms on the study was that it could be dangerous to influence people’s mood. As Nancy J. Smyth, dean of the University of Buffalo’s School of Social Work wrote on her [Social Work blog](https://njsmyth.wordpress.com/2014/06/29/did-facebooks-secret-mood-manipulation-experiment-create-harm/): “There might even have been increased self-harm episodes, out of control anger, or dare I say it, suicide attempts or suicides that resulted from the experimental manipulation. Did this experiment create harm? The problem is, we will never know, because the protections for human subjects were never put into place”.

If this Facebook experiment had such a strong effect on people’s mood that it made some people commit suicide who would otherwise not have committed suicide, this would obviously be problematic. So let us look at the effects the manipulation Facebook used had on people a bit more closely.

From the article, let’s see what the researchers manipulated:

>Two parallel experiments were conducted for positive and negative emotion: One in which exposure to friends’ positive emotional content in their News Feed was reduced, and one in which exposure to negative emotional content in their News Feed was reduced. In these conditions, when a person loaded their News Feed, posts that contained emotional content of the relevant emotional valence, each emotional post had between a 10% and 90% chance (based on their User ID) of being omitted from their News Feed for that specific viewing.

Then what they measured:

>For each experiment, two dependent variables were examined pertaining to emotionality expressed in people’s own status updates: the percentage of all words produced by a given person that was either positive or negative during the experimental period. In total, over 3 million posts were analyzed, containing over 122 million words, 4 million of which were positive (3.6%) and 1.8 million negative (1.6%).

And then what they found:

>When positive posts were reduced in the News Feed, the percentage of positive words in people’s status updates decreased by B = −0.1% compared with control [t(310,044) = −5.63, P \< 0.001, Cohen’s d = 0.02], whereas the percentage of words that were negative increased by B = 0.04% (t = 2.71, P = 0.007, d = 0.001). Conversely, when negative posts were reduced, the percent of words that were negative decreased by B = −0.07% [t(310,541) = −5.51, P \< 0.001, d = 0.02] and the percentage of words that were positive, conversely, increased by B = 0.06% (t = 2.19, P \< 0.003, d = 0.008).

Here, we will focus on the negative effects of the Facebook study (so specifically, the increase in negative words people used) to get an idea of whether there is a risk of an increase in suicide rates. Even though apparently there was a negative effect, it is not easy to get an understanding about the size of the effect from the numbers as mentioned in the text. Moreover, the number of posts that the researchers analyzed was really large. With a large sample, it becomes important to check if the size of the effect is such that the finding is substantially interesting, because with large sample sizes even
minute differences will turn out to be statistically significant (we will look at this in more detail below). For that, we need a better understanding of “effect sizes”.

## The Hungry Judges study

<div class="figure" style="text-align: center">
<img src="images/hungryjudges.png" alt="Proportion of rulings in favor of the prisoners by ordinal position. Circled points indicate the first decision in each of the three decision sessions; tick marks on x axis denote every third case; dotted line denotes food break. From Danziger, S., Levav, J., &amp; Avnaim-Pesso, L. (2011). Extraneous factors in judicial decisions. Proceedings of the National Academy of Sciences, 108(17), 6889–6892. https://doi.org/10.1073/PNAS.1018033108" width="100%" />
<p class="caption">(\#fig:hungryjudges)Proportion of rulings in favor of the prisoners by ordinal position. Circled points indicate the first decision in each of the three decision sessions; tick marks on x axis denote every third case; dotted line denotes food break. From Danziger, S., Levav, J., & Avnaim-Pesso, L. (2011). Extraneous factors in judicial decisions. Proceedings of the National Academy of Sciences, 108(17), 6889–6892. https://doi.org/10.1073/PNAS.1018033108</p>
</div>

We see a graphical representation of the proportion of favorable parole decisions that real-life judges are making as a function of the number of cases they process across the day in Figure \ref{fig:hungryjudges}). This study is mentioned in many popular science books as an example of a finding that shows that people do not always make rational decisions, but that "judicial rulings can be swayed by extraneous variables that should have no bearing on legal decisions" [@danziger_extraneous_2011]. We see that early on in the day, judges start by giving about 65% of people parole, which basically means, "All right, you can go back into society." But then very quickly, the number of favorable decisions decreases to basically zero. After a quick break which, as the authors say, "may replenish mental resources by providing rest, improving mood, or by increasing glucose levels in the body" the parole decisions are back up at 65%, and then again quickly drop down to basically zero. They take another break, the percentage of positive decisions is back up to 65%, only to drop again over the course of the day.

If we calculate the effect size for the drop after a break, and before the next break [@glockner_irrational_2016], the effect represents a Cohen's d of approximately two, which is incredibly large. There are hardly any effects in psychology this large, let along effects of mood or rest on decision making. And this surprisingly large effect occurs not just once, but three times over the course of the day. If mental depletion actually has such a huge real-life impact, society would basically fall into complete chaos just before lunch break every day. Or at the very least, our society would have organized itself around this incredibly strong effect of mental depletion. Just like manufacturers take size differences between men and women into account when producing items such as golf clubs or watches, we would stop teaching in the time before lunch, doctors would not schedule surgery, and driving before lunch would be illegal. If a psychological effect is this big, we don’t need to discover it and publish it in a scientific journal - you would already know it exists. 

We can look at a meta-meta-analysis (a paper that meta-analyzes a large numner of meta-analyses in the literature) by Richard, Bond, & Stokes-Zoota [-@richard_one_2003] to see which effect sizes in law psychology are close to a Cohen’s d of 2. They report two meta-analyzed effects that are slightly smaller. The first is the effect that a jury’s final verdict is likely to be the verdict a majority initially favored, which 13 studies show has an effect size of r = 0.63, or d = 1.62. The second is that when a jury is initially split on a verdict, its final verdict is likely to be lenient, which 13 studies show to have an effect size of r = .63 as well. In their entire database, some effect sizes that come close to d = 2 are the finding that personality traits are stable over time (r = 0.66, d = 1.76), people who deviate from a group are rejected from that group (r = .6, d = 1.5), or that leaders have charisma (r = .62, d = 1.58). You might notice the almost tautological nature of these effects. And that is, supposedly, the effect size that the passing of time (and subsequently eating lunch) has on parole hearing sentencings. 

We see how examining the size of an effect can lead us to identify findings that can not be caused by their proposed mechanisms. The effect reported in the hungry judges study must thefore be due to a confound. Indeed, such confounds have been identified, as it turns out the ordering of the cases is not random, and it is likely the cases that deserve parole are handled first, and the cases that do not deserve parole are handled later [@weinshall-margel_overlooked_2011; @chatziathanasiou_beware_2022]. A additional use of effect sizes is to identify effect sizes that are too large to be plausible. Hilgard [-@hilgard_maximal_2021] proposes to build in 'maximum positive controls', experimental conditions that show the largest possible effect that provides an upper limit on plausible effect size measures. 

## Standardised Mean Differences {#cohend}

Effect sizes can be grouped into two families [@rosenthal_contrasts_2000]: The **d family** (based on standardized mean differences) and the **r family** (based on measures of strength of association). Conceptually, the *d* family effect sizes are based on a comparison between the difference between the observations, divided by the standard deviation of these observations. This means that a Cohen’s *d* = 1 means the standardized difference between two groups equals one standard deviation. The size of the effect in the Facebook study above was quantified with Cohen’s *d*. Cohen’s *d* (the *d* is [italicized](https://blog.apastyle.org/apastyle/2011/08/the-grammar-of-mathematics-writing-about-variables.html)) is used to describe the standardized mean difference of an effect. This value can be used to compare effects across studies, even when the dependent variables are measured with different scales, for example when one study uses 7-point scales to measure dependent variables, while the other study uses 9-point scales. We can even compare effect sizes across completely different measures of the same construct, one study uses a self-report measure, and another study uses a physiological measure. Although we can compare effect sizes across different measurements, this does not mean they are comparable, as we will discuss in more detail in the section on [heterogeneity](#heterogeneity) in the chapter on meta-analysis.

Cohen’s *d* ranges from 0 to infinity. Cohen [-@cohen_statistical_1988] uses subscripts to distinguish different versions of Cohen’s *d*, a practice I will follow because it prevents confusion (without any specification, Cohen’s *d* denotes the entire family of effect sizes). Cohen refers to the standardized mean difference between two groups of independent observations for the *sample* as $d_s$. Before we get into the statistical details, let’s first visualize what a Cohen’s d of 0.001 (as was found in the Facebook study) means. We will use a vizualization from <http://rpsychologist.com/d3/cohend/>, a website made by Kristoffer Magnusson, that allows you to visualize the differences between two measurements (such as the increase in negative words used by the Facebook user when the number of positive words on the timeline was reduced). The vizualization actually shows two distributions, one dark blue and one light blue, but they overlap so much that the tiny difference in distributions is not visible. 

<div class="figure" style="text-align: center">
<img src="images/rpsychd1.png" alt="A vizualization of 2 groups (although the difference is hardly visible) representing d = 0.001." width="100%" />
<p class="caption">(\#fig:rpsychd1)A vizualization of 2 groups (although the difference is hardly visible) representing d = 0.001.</p>
</div>

The four numbers below the distribution express the effect size in different ways to facilitate the interpretation. For example, the probability of superiority expresses the probability that a randomly picked observation from one group will have a larger score than a randomly picked observation from the other group. Because the effect is so small, this probability is 50% - which means that, rounded to one digit after the decimal, people in the experimental and control condition type the same number of positive or negative words. The *number needed to treat* index illustrates that in the Facebook study a person needs to type 3570 words before we will observe one additional negative word, compared to the control condition. I don't know how often you type this amount of words on Facebook, but I think we can agree this effect is not noticeable on an individual level. 

To understand how Cohen’s *d* for two independent groups is calculated, let’s first look at the formula for the *t*-statistic:

$$
t = \frac{{\overline{M}}_{1}{- \overline{M}}_{2}}{\text{SD}_{\text{pooled}} \times \sqrt{\frac{1}{n_{1}} + \frac{1}{n_{2}}}}
$$

Here ${\overline{M}}_{1}{- \overline{M}}_{2}$ is the difference between the means, and $\text{SD}_{\text{pooled}}$ is the pooled standard deviation [@lakens_calculating_2013], and n1 and n2 are the sample sizes of the two groups that are being compared. The *t*-value is used to determine whether the difference between two groups in a *t*-test is statistically significant (as eexplained in the chapter on [*p*-values](#pvalue). The formula for Cohen’s *d*_ is very similar:

$$d_s = \frac{{\overline{M}}_{1}{-\overline{M}}_{2}}{\text{SD}_{\text{pooled}}}$$

As you can see, the sample size in each group (n1 and n2) is part of the formula for a *t*-value, but it is not part of the formula for Cohen’s *d* (the pooled standard deviation is computed by weighing the standard deviation in each group by the sample size, but it cancels out if groups are of equal size). This distinction is useful to know, because in practice it means that the *t*-value (and consequently, the *p*-value) is a function of the sample size, but Cohen's *d* is independent of the sample size. If there is a true effect (e.g., a non-zero effect size in the population) the *t*-value for a null-hypothesis test against an effect of zero will on average become larger (and the *p*-value will become smaller) as the sample size increases. The effect size, however, will not increase or decrease, but will become more accurate, as the standard error decreases as the sample size increases. This is also the reason why *p*-values can not be used to make a statement about whether an effect is *practically significant*, and effect size estimates are often such an important complement to *p*-values when making statistical inferences. 

You can calculate Cohen’s *d* for independent groups from the independent samples *t*-value (which can often be convenient when the result section of the paper you are reading does not report effect sizes) through:

$$d_s = t ⨯ \sqrt{\frac{1}{n_{1}} + \frac{1}{n_{2}}}$$

A d = 001 is an extremely tiny effect, so let's explore an effect size that is a bit more representative of what you would read in the literature. In the meta-meta-analysis mentioned earlier, the median effect size in published studies included in meta-analyses in the psychological literature is *d* = 0.43 [@richard_one_2003]. To get a feeling for this effect size, let's use the online app and set the effect size to d = 0.43.

<div class="figure" style="text-align: center">
<img src="images/rpsychd2.png" alt="A vizualization of 2 groups representing d = 0.43." width="100%" />
<p class="caption">(\#fig:rpsychd2)A vizualization of 2 groups representing d = 0.43.</p>
</div>

One example of a meta-analytic effect size in the meta-meta-analysis that is exactly $d_s$ = 0.43 is the finding that people in a group work less hard to achieve a goal than people who work individually, called *social loafing*. This is an effect that is large enough that we notice it in daily life. Yet, if we look at the overlap in the two distributions, we see that the amount of effort people put in overlaps considerably between the two conditions (in the case of social loafing, working individually versus working in a group). We see in Figure \@ref(fig:rpsychd2) that the **probability of superiority**, or the probability that if we randomly draw one person from the group condition and one person from the individual condition, the person working in a group puts in less effort, is only 61.9%. This interpretation of differences between groups is also called the **common language effect size** [@mcgraw_common_1992]

<div class="figure" style="text-align: center">
<img src="images/rpsychd3.png" alt="A vizualization of 2 groups representing d = 2." width="100%" />
<p class="caption">(\#fig:rpsychd3)A vizualization of 2 groups representing d = 2.</p>
</div>

Based on [this data](http://www.nature.com/pr/journal/v73/n3/full/pr2012189a.html), the difference between the height of 21-year old men and women in The Netherlands is approximately 13 centimeters (in an unstandardized effect size), or a standardized effect size of $d_s$ = 2. If I pick a random man and a random woman walking down the street in my hometown of Rotterdam, how likely is it that the man will be taller than the woman? We see this is quite likely, with a probability of superiority of 92.1%. But even with such a huge effect, there is still considerable overlap in the two distributions. If we conclude the length of people in one group is larger than the length of people in another group, this does not mean everyone in one group is larger than everyone in the other group. 

Sometimes when you try to explain scientific findings at a birthday party, a skeptical aunt or uncle might remark 'well I don't believe that is true because *I* never experience this'. With probabilistic observations, there is a distribution of observed effects. In the example about social loafing, on average people put in less effort to achieve a goal when working in a group than working by themselves. For any individual in the population, the effect might be larger, smaller, absent, or even in the opposite direction. If your skeptical aunt or uncle never experience a finding, that does not contradict that the effect is real on average in the population. Indeed, it is even expected that there is no effect for some people in the population, at least some of the time. Although there might be some exceptions (e.g., almost every individual will experience the Stroop effect, where they are slower naming the ink color of color words when the color word is incongruent with the ink it is written in, than when it is congruent with the ink it is written in), but many effects are smaller, or have sufficient variation, that the effect is not present for everyone in the population. 

Conceptually, calculating Cohen’s *d* for within-subjects comparisons is based on the same idea as for independent groups, where the differences between two observations are divided by the standard deviation within the groups of observations. However, in the case of correlated samples the most common standardizer is the standard deviation of the difference scores. Testing whether two correlated means are significantly different from each other with a paired samples *t*-test is the same as testing whether the difference scores of the correlated means is signicantly different from 0 in a one-sample *t*-test. Similarly, calculating the effect size for the difference between two correlated means is similar to the effect size that is calculated for a one sample *t*-test. The standardized mean difference effect size for within-subjects designs is referred to as Cohen’s $d_z$, where the *z* alludes to the fact that the unit of analysis is no longer *x* or *y*, but their difference, *z*, and can be calculated with:

$$d_z = \frac{M_{dif}}{\sqrt{\frac{\sum{({X_{dif}-M_{dif})}}^2}{N-1}}}$$
The effect size estimate Cohen’s dz can also be calculated directly from the t-value and the number of participants using the formula:

$$d_z = \frac{t}{\sqrt{n}}$$

Given the direct relationship between the *t*-value of a paired-samples *t*-test and Cohen’s $d_z$, it will not be surprising that software that performs power analyses for within-subjects designs (e.g., G*Power) relies on Cohen’s $d_z$ as input. 

Maxwell & Delaney [-@maxwell_designing_2004] remark: ‘a major goal of developing effect size measures is to provide a standard metric that meta-analysts and others can interpret across studies that vary in their dependent variables as well as types of designs.’ BEcause Cohen's $d_z$ takes the correlation between the dependent measures into account, it can not be directly compared with Cohen's $d_s$. Some researchers prefer to use the average standard deviation of both groups of observations as a standardizer (which ignores the correlation between the observations), because this allows for a more direct comparison with Cohen’s $d_s$. This effect size is referred to as Cohen’s $d_av$ [@cumming_understanding_2013], and is simply:

$$d_{av} = \frac{M_{dif}}{\frac{SD_1+SD_2}{2}}$$

## Interpreting effect sizes

A commonly used interpretation of Cohen’s *d* is to refer to effect sizes as small (*d* = 0.2), medium (*d* = 0.5), and large (*d* = 0.8) based on benchmarks suggested by Cohen (1988). However, these values are arbitrary and should not be used. In practice, you will only see them used in a form of circular reasoning: The effect is small, because it is *d* = 0.2, and *d* = 0.2 is small. We see that using the benchmarks adds nothing, beyond covering up the fact that we did not actually interpret the size of the effect. Furthermore, any verbal classification based on benchmarks ignores the fact that any effect can be practically meaningful, such as an intervention that leads to a reliable reduction in suicide rates with an effect size of *d* = 0.1. In other cases, an effect size of *d* = 0.1 might have no consequence at all, for example because such an effect is smaller than the just noticeable difference, and is therefore too small to be noticed by individuals in the real world. 

## Correlations and Variance Explained 

The *r* family effect sizes are based on the proportion of variance that is explained by group membership (e.g., a correlation of *r* = 0.5 indicates 25% (*r*2) of the variance is explained by the difference between groups). You might remember that *r* is used to refer to a correlation. The correlation of two continuous variables can range from 0 (completely unrelated) to 1 (perfect positive relationship) or -1 (perfect negative relationship). To get a better feel correlations, play the game [guess the correlation](http://guessthecorrelation.com/) where you will see a scatterplot, and have to guess the correlation between the variables (see figure \@ref(fig:guesscorrelation). 

<div class="figure" style="text-align: center">
<img src="images/guesscorrelation.png" alt="Screenshot from Guess the Correlation game (the correct answer is r = 0.24)." width="100%" />
<p class="caption">(\#fig:guesscorrelation)Screenshot from Guess the Correlation game (the correct answer is r = 0.24).</p>
</div>

The *r* family effect sizes are calculated from the sum of squares (the difference between individual observations and the mean for the group, squared, and summed) for the effect divided by the sums of squares for other factors in the design. Earlier, I mentioned the median effect size in psychology is $d_s$ = 0.43. However, the authors actually report their results as a correlation, r = 0.21. We can convert Cohen's d into r (but take care that this only applies to $d_s$, not $d_z$):

$r = \frac{d_s}{\sqrt{{d_s^{2}}^{+}\frac{N^{2} - 2N}{n_{1} \times n_{2}}}}$

*N* is the total sample size of both groups, whereas n1 and n2 are the sample sizes of the individual groups you are comparing (it is common to use capital N for the total sample size, and lowercase n for sample sizes per group). You can go to <http://rpsychologist.com/d3/correlation/> to look at a good visualization of the proportion of variance that is explained by group membership, and the relationship between *r* and *r*2. 

As we have seen before, it can be useful to interpret effect sizes to identify effects that are practically insignificant, or effects that are implausibly large. Let’s take a look at a study that examines the number of suicides as a function of the amount of country music played on the radio. You can find the paper [here](https://heinonline.org/HOL/P?h=hein.journals/josf71&i=227) It won an [Ig Nobel prize for studies that first make you laugh, and then think](http://www.abc.net.au/science/articles/2004/10/01/1211441.htm), although in this case, the the study should not make you think about country music, but about the importance of interpreting effect sizes.

The authors predicted the following:

>We contend that the themes found in country music-foster a suicidal mood among people already at risk of suicide and that it is thereby associated with a high suicide rate.

Then they collected data:

> Our sample is comprised of 49 large metropolitan areas for which data on music were available. Exposure to country music is measured as the proportion of radio airtime devoted to country music. Suicide data were extracted from the annual Mortality Tapes, obtained from the Inter-University Consortium for Political and Social Research (ICPSR) at the University of Michigan. The dependent variable is the number of suicides per 100,000 population.

And they concluded:

>A significant zero-order correlation was found between white suicide rates and country music (r = .54, p \< .05). The greater the airtime given to country music, the greater the white suicide rate.

We can again compare the size of this effects with other known effects in psychology. In the database by Richard and colleagues, there are very few effects this large, but some examples are that leaders are most effective if they have charisma (r = 0.54), good leader–subordinate relations promote subordinate satisfaction (r = 0.53), and people can recognize emotions across cultures (r = 0.53). These effects are all large and obvious, which should raise some doubts about whether the relationship between listening to country music and suicides can be of the same size. Is country music really that bad? If we search the literature, we find that [other researchers were not able to reproduce the analysis of the original authors](http://sf.oxfordjournals.org/content/74/1/327.short). It is likely that the results are spurious, or a Type 1 error.

Eta squared $\eta^2$ (part of the *r* family of effect sizes, and an extension of r that can be used for more than two sets of observations) measures the proportion of the variation in Y that is associated with membership of the different groups deﬁned by X, or the sum of squares of the effect divided by the total sum of squares:

$\eta^{2}$ = $\frac{\text{SS}_{\text{effect}}}{\text{SS}_{\text{total}}}$

An $\eta^2$ of .13 means that 13% of the total variance can be accounted for by group membership. Although $\eta^2$ is an efficient way to compare the sizes of effects within a study (given that every effect is interpreted in relation to the total variance, all $\eta^2$ from a single study sum to 100%), eta squared cannot easily be compared between studies, because the total variability in a study ($SS_total$) depends on the design of a study, and increases when additional variables are manipulated (e.g., when independent variables are added). Keppel (1991) has recommended partial eta squared ($\eta_{p}^{2}$) to improve the comparability
of effect sizes between studies, which expresses the sum of squares of the effect in relation to the sum of squares of the effect and the sum of squares of the error associated with the effect. Partial eta squared is calculated as:

$\eta_{p}^{2}$ = $\frac{\text{SS}_{\text{effect}}}{\text{SS}_{\text{effect}} + \text{SS}_{\text{error}}}$

For designs with fixed factors (manipulated factors, or factors that exhaust all levels of the independent variable, such as alive vs. dead), but not for designs with measured factors or covariates, partial eta squared can be computed from the *F*-value and its degrees of freedom [@cohen_statistical_1988]:   

$$\eta_{p}^{2} = \frac{F \times \text{df}_{\text{effect}}}{{F \times \text{df}}_{\text{effect}} + \text{df}_{\text{error}}}$$

For example, for an *F*(1, 38) = 7.21, $\eta_{p}^{2}$ = 7.21 ⨯ 1/(7.21 ⨯ 1 +
38) = 0.16.

Eta squared can be transformed into Cohen’s *d*:

*d* = 2$\times f$ where $f^{2} = \eta^{2}/(1 - \eta^{2})$

## Correcting for Bias

Population effect sizes are almost always estimated on the basis of samples, and as a measure of the population effect size estimate based on sample averages, Cohen’s *d* slighlty overestimates the true population effect. When Cohen’s *d* refers to the population, the Greek letter δ is typically used. Therefore, corrections for bias are used (even though these corrections do not always lead to a completely unbiased effect size estimate). In the *d* family of effect sizes, the correction for bias in the population effect size estimate of Cohen’s δ is known as Hedges’ *g* (although different people use different names – *d_unbiased* is also used). This correction for bias is only noticeable in small sample sizes, but since we often use software to calculate effect sizes anyway, it makes sense to always report Hedge’s *g* instead of Cohen’s *d*  [@thompson_effect_2007].

As with Cohen’s *d*, $\eta^2$ is a biased estimate of the true effect size in the population. Two less biased effect size estimates have been proposed, epsilon squared $\varepsilon^{2}$ and omega squared $\omega^{2}$. For all practical purposes, these two effect sizes correct for bias equally well [@okada_is_2013; @albers_when_2018], and should be preferred above $\eta^2$. Partial epsilon squared ($\varepsilon_{p}^{2}$) and partial omega squared ($\omega_{p}^{2}$) can be calculated based on the *F*-value and degrees of freedom.

$$
\omega_{p}^{2} = \frac{F - 1}{F + \ \frac{\text{df}_{\text{error}} + 1}{\text{df}_{\text{effect}}}}
$$

$$
\varepsilon_{p}^{2} = \frac{F - 1}{F + \ \frac{\text{df}_{\text{error}}}{\text{df}_{\text{effect}}}}
$$
Partial effect sizes $\eta_{p}^{2}$, $\varepsilon_{p}^{2}$) and $\omega_{p}^{2}$ can not be generalized across different designs. For this reason, generalized eta-squared ($\eta_{G}^{2}$) and generalized omega-squared ($\omega_{G}^{2}$) have been proposed [@olejnik_generalized_2003], although they are not very popular. In part, this might be because summarizing the effect size in an ANOVA design with a single index has limitations, and perhaps it makes more sense to describe the pattern of results, as we will see in the section below. 

## Effect Sizes for Interactions

The effect size used for power analyses for ANOVA designs is Cohen's *f*. For two independent groups, Cohen's $f$ = 0.5 * Cohen's *d*. For more than two groups, Cohen's f can be converted into eta-squared and back with $f = \frac{\eta^2}{(1 - \eta^2)}$ or $\eta^2 = \frac{f^2}{(1 + f^2)}$. When predicting interaction effects in ANOVA designs, planning the study based on an expected effect size such as $\eta_{p}^{2}$ or Cohen's *f* might not be the most intuitive approach. 

Let's start with the effect size for a simple two group comparison, and ex effect size to an interaction effect in an ANOVA. Let's assume we predict a mean difference of 1, and know the standard deviation of the measure is 2. This means the standardized effect size is *d* = 0.5. An independent *t*-test is mathematically identical to an *F*-test with two groups. For an *F*-test, the effect size used for power analyses is Cohen's *f*, which is calculated based on the standard deviation of the population means divided by the population standard deviation (which we know for our measure is 2), or: 

\begin{equation}
f = \frac{\sigma _{ m }}{\sigma}
\end{equation}
where for equal sample sizes
\begin{equation}
\sigma _{ m } = \sqrt { \frac { \sum_ { i = 1 } ^ { k } ( m _ { i } - m ) ^ { 2 } } { k } }.
\end{equation}

In this formula *m* is the grand mean, k is the number of means, and m_i is the mean in each group. The formula above might look a bit daunting, but calculating Cohen's f is not that difficult for two groups. 

If we take the expected means of 0 and 1, and a standard deviation of 2, the grand mean (the *m* in the formula above) is (0 + 1)/2 = 0.5. The formula says we should subtract this grand mean from the mean of each group, square this value, and sum them. So we have (0-0.5)^2 and (1-0.5)^2, which are both 0.25. We sum these values (0.25 + 0.25 = 0.5), divide them by the number of groups (0.5/2 = 0.25) and take the square root, we find that $\sigma_{ m }$ = 0.5. We can now calculate Cohen's *f* (using $\sigma$ = 2 for our measure): 

\begin{equation}
f = \frac{\sigma _{ m }}{\sigma} = \frac{0.5}{2} = 0.25
\end{equation}

We confirm that for two groups Cohen's *f* is half as large as Cohen's *d*. 

Now we have the basis to look at interaction effects. Different patterns of means in an ANOVA can have the same Cohen's *f*. There are two types of interactions, as visualized below in Figure \@ref(fig:interactions). In an **ordinal interaction**, the mean of one group ("B1") is always higher than the mean for the other group ("B2"). **Disordinal interactions** are also known as 'cross-over' interactions, and occur when the group with the larger mean switches over. The difference is important, since the disordinal interaction in Figure \@ref(fig:interactions) has a larger effect size than the ordinal interaction.

<img src="06-effectsize_files/figure-html/interactions-1.png" width="100%" style="display: block; margin: auto;" />

Mathematically the interaction effect is computed as the cell mean minus the sum of the grand mean, the marginal mean in each condition of one factor minus the grand mean, and the marginal mean in each condition for the other factor minus grand mean [@maxwell_designing_2004].

Let's consider two cases, one where we have a perfect disordinal interaction (the means of 0 and 1 flip around in the other condition, and are 1 and 0) or an ordinal interaction (the effect is present in one condtion, 0 and 1, but disappears in the other condition, with means 0 and 0). We can calcuate the interaction effect as follows. First, let's look at the interaction between factor A (with two levels) and B (also with two levels) in a 2x2 matrix:


```
##    a1 a2
## b1  1  0
## b2  0  1
```

The grand mean is (1 + 0 + 0 + 1) / 4 = 0.5.

We can compute the marginal means for A1, A2, B1, and B2, which is simply averaging per row and column, which gets us for the A1 row (1+0)/2=0.5. For this perfect disordinal interaction, all marginal means are 0.5. This means there are no main effects. There is no main effect of factor A (because the marginal means for A1 and A2 are both exactly 0.5), nor is there a main effect of B.

We can also calculate the interaction effect. For each cell we take the value in the cell (e.g., for a1b1 this is 1) and compute the difference between the cell mean and the additive effect of the two factors as:

1 - (the grand mean of 0.5 + (the marginal mean of a1 minus the grand mean, or 0.5 - 0.5 = 0) + (the marginal mean of b1 minus the grand mean, or 0.5 - 0.5 = 0)). Thus, for each cell we get:

a1b1: 1 - (0.5 + (0.5 -0.5) + (0.5 -0.5)) = 0.5

a1b2: 0 - (0.5 + (0.5 -0.5) + (0.5 -0.5)) = -0.5

a2b1: 0 - (0.5 + (0.5 -0.5) + (0.5 -0.5)) = -0.5

a2b2: 1 - (0.5 + (0.5 -0.5) + (0.5 -0.5)) = 0.5

Cohen's $f$ is then $f = \frac { \sqrt { \frac { 0.5^2 +-0.5^2 + -0.5^2 + 0.5^2 } { 4 } }}{ 2 } = 0.25$

or in R code: `sqrt(((0.5)^2 +(-0.5)^2 + (-0.5)^2 + (0.5)^2)/4)/2 = 0.25`.

For the ordinal interaction the grand mean is (1 + 0 + 0 + 0) / 4, or 0.25. The marginal means are a1: 0.5, a2: 0, b1: 0.5, and b2: 0.

Completing the calculation for all four cells for the ordinal interaction gives:

a1b1: 1 - (0.25 + (0.5 -0.25) + (0.5 -0.25)) = 0.25

a1b2: 0 - (0.25 + (0.5 -0.25) + (0.0 -0.25)) = -0.25

a2b1: 0 - (0.25 + (0.0 -0.25) + (0.5 -0.25)) = -0.25

a2b2: 0 - (0.25 + (0.0 -0.25) + (0.0 -0.25)) = 0.25

Cohen's $f$ is then $f = \frac { \sqrt { \frac { 0.25^2 +-0.25^2 + -0.25^2 + 0.25^2 } { 4 } }}{ 2 } = 0.125$.

or in R code: `sqrt(((0.25)^2 +(-0.25)^2 + (-0.25)^2 + (0.25)^2)/4)/2 = 0.125`.


We see the effect size of the cross-over interaction (*f* = 0.25) is twice as large as the effect size of the ordinal interaction (*f* = 0.125). 

If the math so far was a bit too much to follow, there is an easier way to think of why the effect sizes are halved. In the disordinal interaction we are comparing cells a1b1 and a2b2 against a1b2 and a2b1, or (1+1)/2 vs. (0+0)/2. Thus, if we see this as a *t*-test for a contrast, it is clear the mean difference is 1, as it was in the simple effect we started with. For the ordinal interaction, we have (1+0)/2 vs. (0+0)/2, so the mean difference is halved, namely 0.5. 

### Power for interactions

All of the above obviously matters for the statistical power we will have when we examine interaction effects in our experiments. Let's use Superpower to perform power analyses for the disordinal interaction first, if we would collect 50 participants in each condition. 


```r
design <- Superpower::ANOVA_design(
  design = "2b*2b", 
  n = 50, 
  mu = c(1, 0, 0, 1), 
  sd = 2)
```

<img src="06-effectsize_files/figure-html/unnamed-chunk-3-1.png" width="100%" style="display: block; margin: auto;" />

```r
Superpower::ANOVA_exact(design, alpha_level = 0.03)
```

```
## Power and Effect sizes for ANOVA tests
##      power partial_eta_squared cohen_f non_centrality
## a    3.000                0.00  0.0000            0.0
## b    3.000                0.00  0.0000            0.0
## a:b 91.055                0.06  0.2525           12.5
## 
## Power and Effect sizes for pairwise comparisons (t-tests)
##                       power effect_size
## p_a_a1_b_b1_a_a1_b_b2 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b1 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b2  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b1  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b2 61.78         0.5
## p_a_a2_b_b1_a_a2_b_b2 61.78         0.5
```

```
## Power and Effect sizes for ANOVA tests
##      power partial_eta_squared cohen_f non_centrality
## a    3.000                0.00  0.0000            0.0
## b    3.000                0.00  0.0000            0.0
## a:b 91.055                0.06  0.2525           12.5
## 
## Power and Effect sizes for pairwise comparisons (t-tests)
##                       power effect_size
## p_a_a1_b_b1_a_a1_b_b2 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b1 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b2  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b1  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b2 61.78         0.5
## p_a_a2_b_b1_a_a2_b_b2 61.78         0.5
```

First let's look at the Power and Effect size for the pairwise comparisons. Not surprisingly, these are just the same as our original t-test, given that we have 50 observations per condition, and our mean difference is either 1, or a Cohen's d of 0.5 (in which case we have 61.78% power) or the mean difference is 0, and we have no power (because there is no true effect) but we wil observe significant results 3% of the time because we set our apha level to 0.03.

Then, let's look at the results for the ANOVA. Since there are no main effects in a perfect crossover interaction, we have a 3% Type 1 error rate. We see the power for the crossover interaction between factor a and b is 91.06%. This is much larger than the power for the simple effects. The reason is that the contrast that is equal to the test of the interaction is based on all 200 observations. Unlike the pairwise comparisons with 50 vs 50 observations, the contrast for the interaction has 100 vs 100 observations. Given that the effect size is the same (*f* = 0.25) we end up with much higher power. 

If you have heard that it is impossible to find a statistically significant interaction without huge sample size, you clearly see this is wrong. Power *can* be higher than for the simpe effect - but this depends on the pattern of means underlying the interaction. If possible, design studies where your theory predicts a perfect crossover interaction.


For the ordinal interaction, our statistical power does not look that good based on an a-priori power analysis. SUperpower tells us we have 33.99% power for the main effects and interaction (yes, we have exactly the same power for all three - if you think about the three contrasts that are tested, these have the same effect size). 


```r
design <- Superpower::ANOVA_design(
  design = "2b*2b", 
  n = 50, 
  mu = c(1, 0, 0, 0), 
  sd = 2)
```

<img src="06-effectsize_files/figure-html/unnamed-chunk-4-1.png" width="100%" style="display: block; margin: auto;" />

```r
Superpower::ANOVA_exact(design, alpha_level = 0.03)
```

```
## Power and Effect sizes for ANOVA tests
##       power partial_eta_squared cohen_f non_centrality
## a   33.9869              0.0157  0.1263          3.125
## b   33.9869              0.0157  0.1263          3.125
## a:b 33.9869              0.0157  0.1263          3.125
## 
## Power and Effect sizes for pairwise comparisons (t-tests)
##                       power effect_size
## p_a_a1_b_b1_a_a1_b_b2 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b1 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b2 61.78        -0.5
## p_a_a1_b_b2_a_a2_b_b1  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b2  3.00         0.0
## p_a_a2_b_b1_a_a2_b_b2  3.00         0.0
```

```
## Power and Effect sizes for ANOVA tests
##       power partial_eta_squared cohen_f non_centrality
## a   33.9869              0.0157  0.1263          3.125
## b   33.9869              0.0157  0.1263          3.125
## a:b 33.9869              0.0157  0.1263          3.125
## 
## Power and Effect sizes for pairwise comparisons (t-tests)
##                       power effect_size
## p_a_a1_b_b1_a_a1_b_b2 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b1 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b2 61.78        -0.5
## p_a_a1_b_b2_a_a2_b_b1  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b2  3.00         0.0
## p_a_a2_b_b1_a_a2_b_b2  3.00         0.0
```

If you have heard people say you should be careful when designing studies predicting interaction patterns because you might have very low power, this is the type of pattern of means they are warning about. Maxwell, Delaney, and Kelley (2018) discuss why power for interactions is often smaller, and note interactions effects are often smaller in the real world, and we often examine ordinal interactions. This might be true. But in experimental psychology it might be possile to think about hypotheses that predict disordinal interactions. In addition to the fact that such predictions are often theoretically riskier and more impressive (after all, many things can make an effect go away, but without your theory it might be difficult to explain why an effect flips around) they also have larger effects and are easier to test with high power.

Some years ago other blog posts by [Uri Simonsohn](http://datacolada.org/17) and [Roger Giner-Sorolla](https://approachingblog.wordpress.com/2018/01/24/powering-your-interaction-2/) did a great job in warning researchers they need large sample sizes for ordinal interactions, and my post repeats this warning. But it would be a shame if researchers would stop examining interaction effects. There are some nice benefits studying interactions, such as 1) making riskier theoretical predictions, 2) greater generalizability (if there is no interaction effect, you might show a main effect operates across different conditions of a second factor) and 3) if you want to study two main effects it is more efficient to do this in a 2x2 design than in two seperate designs (Maxwell, Delaney, & Kelley, 2018). So maybe this blog post has been able to highlight some scenarios where examining interaction effects is still beneficial.


