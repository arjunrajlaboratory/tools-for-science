# Annotated example review of a science paper

\[ALL DETAILS CHANGED TO DEIDENTIFY. CONSEQUENTLY, THE REVIEW MAY NOT MAKE ANY SENSE, SCIENTIFICALLY]

This was a paper about variability in single-cell drug response rates for breast cancer. It had some nice experiments, but the big flaw was that it was trying to claim things that their experiments didn’t actually show.

***

{% hint style="info" %}
The first paragraph should be a summary of what the paper was in your own words. It’s basically to show that you read and understood the paper. I usually do NOT say anything about whether I liked the paper, although if it’s really nice, I’ll sometimes say “In this very nice manuscript…”. I usually aim for around 4-5 sentences. This one is perhaps a bit long.
{% endhint %}

In this manuscript, Rodriguez and colleagues describe a series of experiments that investigate heterogeneity in single-cell drug response rates for breast cancer cells, as well as the functional characterization of a previously undescribed factor in the factor regulating replication in those cells. The authors show that APX23 levels in single cells predict protein accumulation in MCF-7 cells. Using a CRISPR screen for genes that affect APX23 levels, the authors then identify several proteins that affect both the mean in and variability of the accumulation of APX23. They show that knocking out these genes changed the drug response as predicted, and they focused on one in particular NPMX92, which when deleted in MCF-7 cells led to a reduction of heterogeneity in single-cell APX23 levels and a concomitant increase in drug susceptibility. The authors then use time-lapse microscopy and Co-IP to show that NPMX92 is the critical factor regulating replication. Further, they show that deletion of NPMX92 also reduces variability in other phenotypes, such as cell growth rate and cell size.



{% hint style="info" %}
The second paragraph is an overall assessment of the paper and its “impact”. How exciting is the paper, and why? I usually always say something positive here, although how positive might vary. I usually include something about the data being of high quality. The editor is looking for this paragraph to get their overall assessment of whether the paper is interesting enough for their journal.
{% endhint %}

Overall, I think that this paper is quite exciting and timely. Overall, the connection between drug resistance and single cell behavior is an area of considerable interest. Specifically, the clinical implications of understanding such mechanisms in breast cancer only serve to heighten this interest. Furthermore, this paper also reveals some aspects of the mechanism of variability generation, showing that variability in replication can affect variability in single cell growth rates, which is a relatively unexplored area. The experiments themselves are top notch, including a nice blend of genetic screening techniques, immunoprecipitation, and assorted other techniques, all of which appear to be well executed.



{% hint style="info" %}
If I have a major overarching theme to my concerns, then I will have another paragraph describing that concern, along with a general prescription for what to do about it. This paragraph can be relatively general, but should be backed up by specific points (more on that later). This paragraph signals to the editor that this is a big problem with the manuscript and needs to be addressed. If the paper has no major flaws, then you can drop this and go straight to the specific concerns.
{% endhint %}

My primary concern with the paper is with the interpretations the authors make of how heterogeneity is generated and how it mediates drug tolerance. I think that some quantitative analysis of effect sizes could help make these interpretations more concrete, along with some textual changes. Here are a few specific comments and questions:



{% hint style="info" %}
Here’s where we talk about specific concerns. BE SPECIFIC. Not like “the analysis was lacking” or “such and such was unconvincing”. What was lacking? What was unconvincing? And SPECIFICALLY what can the authors do to solve that? This is very important, because sometimes by thinking about that, you realize that it’s not really possible to address the issue. Rather, I try to make them alter the language of what they can claim given the data they have. If the reduction in claims makes the paper way less interesting, then that’s the editor’s call, in my opinion.\
\
I avoid asking for new experiments, but new analyses of existing data is fair game, in my opinion. Oh, and don’t worry about things like grammar and other nitty gritty. Not your job.<br>
{% endhint %}

{% hint style="info" %}
Here’s an example where the authors overclaim something. We were very explicit about exactly what they can say and why, and point out a specific sentence and suggest they alter it.
{% endhint %}

1\. I think the authors have made a solid case in Figure 1 that variability in APX23 accumulation is strongly associated with resistance to targeted therapy. The authors then show, convincingly, the NPMX92 KO leads to increased drug susceptibility. However, I think that the results currently suggest, but do not conclusively prove, that the way NPMX92 leads to increased resistance is through the change in CV of APX23 levels. In Fig. 2c, there are several KOs that lead to increased or decreased median fluorescence (including NPMX92), and in general, this increase or decrease reflects decreased or increased survival in drug (Fig. 3x). Notably, of the KOs with increased median fluorescence, some have increased CV and some decreased, but either way, the survival decreases. The authors have carefully avoided saying anything explicitly making the connection between changes in heterogeneity and resistance in the abstract, but the overall impression given is that the cells are creating heterogeneity through the activity of NPMX92 that directly affects resistance, which is not clear from my reading of the data. For example: “[<mark style="background-color:orange;">Our results show that MCF-7 cells express a protein that controls cell proliferation in a way that results in a heterogeneous population that is in total better able to survive stress.</mark>](#user-content-fn-1)[^1]” It is true that NPMX92 controls proliferation, and that it results in a more heterogeneous population, and that the resulting population is better able to survive stress, but I don’t think the authors have provided direct evidence that increased variability itself allows the population to better survive stress, which the abstract implies. I think rephrasing this line and related statements in the abstract would solve the problem.



{% hint style="info" %}
Often, people will make a claim that is statistically significant, but pretty weak sauce biologically. So what I do in this case is ask them to make explicit the effect size with hard numbers. Like, if you’re going to say “XYZ affects expression levels” when the effect is like 5%, make them say 5%.
{% endhint %}

2\. Along those lines, it seems that the reduction of CV in APX23 levels in the NPMX92 KO is relatively modest (perhaps around 10% or so?). I think it’s important to state that number explicitly in the results section and the abstract. However, proliferate rate and granularity change by considerably larger amounts. Can the authors provide some sort of quantitative estimate of what amount of the change in APX23 heterogeneity is due to these secondary differences in the NPMX92 KO? Also, it would be helpful to have some sort of model for how such changes lead to APX23 heterogeneity or resistance. Pending this analysis, I suggest reevaluating the following line from the abstract: “NPMX92 KO inhibits proliferation and consequent heterogeneity.” I don’t believe the authors have made the case for “consequent heterogeneity”; I suggest removing that from the abstract, or at least more clearly define exactly what sort of heterogeneity the authors are referring to: in growth? APX23 accumulation? Resistance? Whatever they choose, I think it’s important to explicitly state the effect size.



{% hint style="info" %}
If there’s some apparent discrepancy, I usually just ask the authors to explain it rather than saying this is evidence of a big problem. They may have a good explanation or not, but give them the benefit of the doubt.
{% endhint %}

3\. In Fig. 12y, what is the highest dose data point? It looks like there is \~100% survival of the WT but <10% survival for two mutants. Can the authors discuss why this might be happening and how that affects their interpretations of drug resistance?



{% hint style="info" %}
Again, ask to explain details for things that seem weird/shady.
{% endhint %}

4\. In Fig. 18m,n, the authors claim that there is a statistically significant change in the reduction of the rate of replication fork assembly. Please clarify the assumptions underlying the rate calculation and their distributions. By eye there seems to be a significant bias in the rate variability in the experimental and control groups (violating Fisher test assumptions, which appears to be what the authors performed).



{% hint style="info" %}
Minor point.
{% endhint %}

5\. Fig. 28p has 19 bars drawn, but 21 are indicated..



{% hint style="info" %}
Minor point. Can comment on points of clarity.
{% endhint %}

6\. It would be helpful to  have more details on the statistical analysis introduced on page 83, paragraph 2.



{% hint style="info" %}
Minor point. Can comment on points of clarity.
{% endhint %}

7\. I couldn’t figure out how the KO distributions were generated in Fig. 52j. Without the full equations used, it was hard for me to evaluate the result in Fig. 52k.



{% hint style="info" %}
I will sometimes ask them to cite relevant papers, but not very often. Only if it’s really egregious. Or if it’s our paper ;).
{% endhint %}

8\. It may be worth discussing Dr. McStuffins lab’s work on MCF-7 cells and therapy resistance (Biorxiv 2026).



{% hint style="info" %}
I sign my reviews but you don’t have to.
{% endhint %}

Arjun Raj

<br>

[^1]: Quoting specific sentences is very specific and is a good thing.
