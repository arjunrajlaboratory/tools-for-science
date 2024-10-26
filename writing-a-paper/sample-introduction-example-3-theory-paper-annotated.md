# Sample introduction example 3 (theory paper, annotated)

## Gene Networks with Transcriptional Bursting Recapitulate Rare Transient Coordinated High Expression States in Cancer

### Summary

Non-genetic transcriptional variability is a potential mechanism for therapy resistance in melanoma. Specifically, rare subpopulations of cells occupy a transient pre-resistant state characterized by coordinated high expression of several genes and survive therapy. How might these rare states arise and disappear within the population? It is unclear whether the canonical models of probabilistic transcriptional pulsing can explain this behavior, or if it requires special, hitherto unidentified mechanisms. We show that a minimal model of transcriptional bursting and gene interactions can give rise to rare coordinated high expression states. These states occur more frequently in networks with low connectivity and depend on three parameters. While entry into these states is initiated by a long transcriptional burst that also triggers entry of other genes, the exit occurs through independent inactivation of individual genes. Together, we demonstrate that established principles of gene regulation are sufficient to describe this behavior and argue for its more general existence.

### Introduction

{% hint style="info" %}
Sets general tone and level of detail. This paper is clearly geared towards single cell biologists, but also is trying to draw in a somewhat broader audience.\
\
This paper has a tough task: it's introducing a specific phenomenology (rare cell expression leading to drug resistance) that is pretty new conceptually, so it has to squeeze in a lot of results quickly but without overwhelming. I think it does a decent job of it.
{% endhint %}

Cellular heterogeneity has been reported to arise from non-genetic transcriptional variability, even in clonal, genetically homogeneous cells grown in identical conditions [(Spencer et al., 2009; Sharma et al., 2010, 2018; Gupta et al., 2011; Pisco and Huang, 2015; Fallahi-Sichani et al., 2017; Shaffer et al., 2017; Su et al., 2017)](https://paperpile.com/c/irYHSb/yZ8lF+Qtjjm+g8CaI+abqFi+AeKQ9+g9FQl+U3AaD+wzsKC). Cells exhibiting these non-genetic deviations are resistant to anti-cancer drugs (e.g., Ras pathway inhibitors) and may lead to relapse in patients. For example, in a drug-naive melanoma population, a small fraction (\~1 in 3000) of cells are pre-resistant, meaning they are able to survive targeted drug therapy, resulting in their uncontrolled cellular proliferation [(Shaffer et al., 2017)](https://paperpile.com/c/irYHSb/g8CaI). These rare pre-resistant cells are marked by transient and coordinated high expression of dozens of marker genes. In other words, several genes are highly expressed simultaneously in a rare subset of cells, while the rest of the population have low or zero counts of mRNAs for these genes, resulting in a distribution of steady state mRNA counts per cell that peaks at or close to zero and has heavy tails.&#x20;

{% hint style="info" %}
Normally, I like to have the first paragraph end with a statement of the gap in knowledge. In this case, I think there's just too much exposition for that to be reasonable, although it would have been fun to try.\
\
Nevertheless, it does end with a strong statement of the interesting phenomenology that is the direct topic of this paper, so good!
{% endhint %}

[<mark style="background-color:orange;">The rare cells</mark>](#user-content-fn-1)[^1] in the tails, which transiently arise and disappear in the population by switching their gene expression state (Figure 1A), are much more likely to develop resistance to targeted therapies. The rare and coordinated large fluctuations in the expression of multiple genes persist for several generations. [Classical probabilistic models of gene expression](#user-content-fn-2)[^2] have predicted the possibility of various types of mRNA expression distributions across a population, including normal, log-normal, gamma, or heavy-tail distributions [(Thattai and van Oudenaarden, 2001; Golding et al., 2005; Raj et al., 2006; Raj and van Oudenaarden, 2008; Iyer-Biswas, Hayot and Jayaprakash, 2009; So et al., 2011; Chen and Larson, 2016; Corrigan et al., 2016; Symmons and Raj, 2016; Antolović et al., 2017; Ham, Brackston and Stumpf, 2019; Ham et al., 2020)](https://paperpile.com/c/irYHSb/i5061+x38mi+J2CU6+m1PVf+Ctz3w+evm0B+gtOHq+lUW4P+fhiKI+dHX8r+5yz0g+RLvf1). [<mark style="background-color:orange;">It is unclear if such models can recapitulate the non-genetic variability characterized by rare and transient high expression states for several genes simultaneously (from now on referred to as “rare coordinated high states”), and if so, under what conditions.</mark>](#user-content-fn-3)[^3]

[<mark style="background-color:orange;">Might a stochastic system of interacting genes inside the cell facilitate transition in and out of the rare coordinated high state?</mark>](#user-content-fn-4)[^4] One hypothesis is that only a rare set of unique (and perhaps complex) networks can facilitate reversible transitions into the rare coordinated high states. Alternatively, relatively generic gene regulatory networks may be capable of producing such behaviors, suggesting that a large ensemble of such networks may admit rare-cell formation. Both of these scenarios have different implications—for instance, the latter hypothesis suggests that this behavior could be more common in biological systems than hitherto appreciated. The alternatives described above can also be posed in terms of the nature of model parameters—whether the set of values that give rise to rare coordinated high states are constrained to lie within a narrow window of parameter space or whether such behavior may occur across broad swaths of parameter space. Yet another possibility is that stochastic gene expression alone fails to produce rare coordinated high states in the absence of additional regulation. [<mark style="background-color:orange;">In that case, one may argue that the reversible transition into the rare coordinated high state is driven by highly specialized processes (e.g. initiated by a master regulator) or other unknown mechanisms.</mark>](#user-content-fn-5)[^5]&#x20;

{% hint style="info" %}
This paragraph describes what we do in the paper. Normally, this is the last paragraph of the introduction. In this case, it's still expositional because it's describing the model. Still kinda hybrid.
{% endhint %}

Here we describe a mathematical framework to test the hypotheses proposed above for the appearance and disappearance of rare coordinated high states (Box 1). Recent studies from our lab suggest that no particular molecular pathway is solely responsible for the formation of these rare cells [(Shaffer et al., 2018; Torre et al., 2019)](https://paperpile.com/c/irYHSb/kd68w+r8bsQ). Specifically, in these rare cells, a sequencing and imaging based scheme identified a collection of marker genes, which are targets of multiple signaling pathways ranging from type 1 interferon to PI3K-Akt signaling. The implication is that instead of a single signaling pathway leading to the observed behavior, a network of interacting genes appears to be responsible. Accordingly, we used network modeling to see whether genes interacting within a network were capable of producing transitions to coordinated high expression states. We systematically formulated and simulated networks of increasing size and complexity defined by a broad range for all independent parameters (Box 1 and 2; and STAR Methods, section Networks & section Parameters).&#x20;

{% hint style="info" %}
This next paragraph is a continuation of the above, elaborating on what was done in the paper itself, but with more details. I think this paragraph could probably be a bit less detailed and start with a stronger topic sentence, but it gets the job done.
{% endhint %}

Computational screens on more than 96 million simulated cells reveal that many networks with interactions between genes are capable of producing rare coordinated high states. Critically, transcriptional bursting, a ubiquitous phenomenon in which genes flip between transcriptionally active and inactive states, is necessary to produce these rare coordinated high states within the context of our models. Subsequent quantitative analysis shows that rare coordinated high states occur across networks of all sizes investigated (up to 10 nodes), but that (i) they depend on three (out of seven) independent model parameters and (ii) their frequency of occurrence decreases monotonically with increasing network connectivity. The transition into the rare coordinated high state is initiated by a long transcriptional burst, which, in turn, triggers the entry of subsequent genes into the rare coordinated high state. In contrast, the transition out of rare coordinated high state is independent of the duration of transcriptional bursts, rather it happens through the independent inactivation of individual genes. We also confirm model predictions using experimental gene expression data (RNA FISH data) taken from melanoma cell lines. Together, we demonstrate that the standard model of stochastic gene regulation with transcriptional bursting is capable of producing rare coordinated high states in the absence of additional regulation.&#x20;

\


[^1]: This paragraph provides more detailed context for the aficionado in the field of single cell gene expression.

[^2]: Contrast (quickly) our observations with the models that exist in the literature already.

[^3]: Here is the statement of the gap in knowledge.

[^4]: In this paragraph, we outline several alternative hypotheses.

[^5]: This paragraph could probably have ended more strongly with a question of some sort.
