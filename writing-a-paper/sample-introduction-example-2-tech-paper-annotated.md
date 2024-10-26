# Sample introduction example 2 (tech paper, annotated)

{% hint style="info" %}
Nice declarative title. Perhaps a bit long.
{% endhint %}

## Retrospective identification of rare cell populations underlying drug resistance connects molecular variability with cell fate&#x20;

### Abstract

Molecular differences between individual cells can lead to dramatic differences in cell fate following an applied treatment, such as the difference between death versus survival of cancer cells upon receiving anti-cancer drugs. However, current strategies to retrospectively identify the cells that give rise to distinct rare behaviors and determine their distinguishing molecular characteristics remain limited. Here we describe Rewind, a methodology that combines genetic barcoding with an RNA-based readout to directly capture rare cells that give rise to cellular behaviors of interest, specifically the emergence of resistance to targeted cancer therapy. Using Rewind, we analyzed over 5 million cells (!) to identify differences in gene expression and MAP-kinase signaling in single melanoma cells that mark a rare subpopulation of drug-naive cells (initial frequency of \~1:1000-1:10,000 cells) that ultimately gives rise to drug resistant clones. We further show that even within this rare subpopulation, molecular differences between single cells before the application of drug predict future differences in drug resistant behavior. Similarly, we show that treatments that modify the frequency of resistance can allow otherwise non-resistant cells in the drug-naive population to become resistant, and that these new populations are marked by the variable expression of distinct genes. Together, our results reveal the presence of cryptic variability that can underlie a range of distinct rare-cell phenotypic outcomes upon drug exposure. Applying Rewind to other rare biological phenomena, such as cancer metastasis, tissue regeneration, and stem cell reprogramming, may provide a means to map rare cellular states to the unique cellular fates to which they give rise.

### Introduction

{% hint style="info" %}
Start with a general introduction to the field. This sentence sets the "level"; in this case, it's about single cell biology, and at a pretty high level (i.e., not assuming much detailed knowledge).
{% endhint %}

Individual cells—even those of ostensibly the same cell type—can differ from each other in a number of ways. Some of these differences can result in a “primed” cellular state that can, in a particular context, ultimately lead to biologically distinct behaviors [(Symmons and Raj 2016; Raj and van Oudenaarden 2008)](https://paperpile.com/c/2H9smt/KNtN+UuKB). This cellular priming underlies a number of important single cell phenomena. [<mark style="background-color:orange;">For instance</mark>](#user-content-fn-1)[^1], when anti-cancer therapeutics are applied to clonally derived cancer cells, most of the cells die; however, a small number of cells survive and proliferate, and these cells drive therapy resistance [(Gupta et al. 2011; Sharma et al. 2010; Roesch et al. 2010; Shaffer et al. 2017)](https://paperpile.com/c/2H9smt/evLt+p1TZ+rXbk+6V9m). [<mark style="background-color:orange;">Yet, while this phenomena implies the existence of rare, primed cells in the initial population, it remains unclear what distinguishes these cells at the molecular level from the rest of the population.</mark>](#user-content-fn-2)[^2]

[<mark style="background-color:orange;">We and others have shown that rare cells within an isogenic population can exhibit fluctuations in expression of several genes simultaneously, which predict rare-cell phenotypes and persist through multiple cell divisions</mark>](#user-content-fn-3)[^3] [(Shaffer et al. 2018; Gupta et al. 2011)](https://paperpile.com/c/2H9smt/cV2z+evLt). What remains largely unknown, outside of a few cases [(Shaffer et al. 2017; Cohen et al. 2008; Spencer et al. 2009)](https://paperpile.com/c/2H9smt/6V9m+h7dc+qKbu), is how this variability maps to distinct cellular outcomes following a treatment. As a result, several questions remain unanswered. Is molecular variability in the initial state of cells inconsequential because all cells ultimately funnel into the same cell fate? Can different cell fates arise from otherwise indistinguishable initial molecular states? Or can most differences in ultimate fate be traced back to measurable differences in the initial states of cells? [<mark style="background-color:orange;">These questions remain largely unanswered because of our limited ability to longitudinally track and profile cells (especially rare ones) from initial state to final fate.</mark>](#user-content-fn-4)[^4]

[<mark style="background-color:orange;">Currently, the two general methodologies for longitudinal tracking and profiling are direct visualization by time lapse microscopy and genetic encoding of lineage information</mark>](#user-content-fn-5)[^5] (i.e., “barcoding”) [(Sigal et al. 2006; Cohen et al. 2008; Biddy et al. 2018; Raj et al. 2018)](https://paperpile.com/c/2H9smt/iPUp+h7dc+fNJL+MsoZ). Time lapse microscopy allows one to directly follow cells over time, providing a definitive cellular lineage, high resolution temporal information, and a direct connection to fate [(Sigal et al. 2006; Cohen et al. 2008)](https://paperpile.com/c/2H9smt/iPUp+h7dc). [<mark style="background-color:orange;">However</mark>](#user-content-fn-6)[^6], monitoring the molecular processes occurring in these cells by time-lapse remains challenging: fluorescent reporters of gene expression and signaling activity are difficult to introduce and validate, and the ability to multiplex them is generally limited. Barcoding, in which cells are labeled by unique and sometimes mutable nucleic acid sequences [(Frieda et al. 2016; Raj et al. 2018; Alemany et al. 2018; McKenna et al. 2016; Kalhor et al. 2018)](https://paperpile.com/c/2H9smt/mB1d+MsoZ+pAro+81cr+QFpi), allows one to track cells by sequencing. When combined with single cell RNA sequencing methods, one can connect cellular lineages to transcriptomic profiles [(Biddy et al. 2018; Weinreb et al. 2020; Al’Khafaji et al. 2019; Hurley et al. 2020)](https://paperpile.com/c/2H9smt/fNJL+zpx7+wbU5+dpf4). These techniques, however, are difficult to combine with assays that measure molecular features outside of gene expression levels, which may be important to distinguish key subpopulations [(Weinreb et al. 2020; Wu et al. 2020)](https://paperpile.com/c/2H9smt/zpx7+ImPU). A key challenge for both of these methodologies is the detection of rare cells (1:1000 or even more rare), for which neither time-lapse nor single cell RNA sequencing is particularly effective (new techniques aim to circumvent these limitations; [(Al'Khafaji et al. 2018; Feldman et al. 2019)](https://paperpile.com/c/2H9smt/DGJo+N1p9). [<mark style="background-color:orange;">Yet, many biological phenomena, such as therapy resistance in cancer cells, occur in subpopulations that are at least that rare.</mark>](#user-content-fn-7)[^7]

{% hint style="info" %}
Usually a short description of the work here. Shorter and different than abstract. Keep it focused on answering precisely the questions posed in the introduction. Highlight the single most important point.
{% endhint %}

Here, we combine cellular barcoding with RNA Fluorescent In Situ Hybridization (RNA FISH) to selectively isolate rare cells that adopt distinct cellular fates. We apply this methodology, which we call Rewind, to targeted therapy resistance in melanoma, revealing prospective expression markers of cells primed for resistance upon BRAFV600E inhibition. Further, we show that differences in resistance outcome can be traced to distinct cell subpopulations that can be discriminated on the basis of their transcriptome profiles. These findings suggest that cryptic single cell variability within otherwise homogeneous cells can lead to important differences in ultimate cellular behavior in response to a treatment.

\


[^1]: Simple description of an instance of the question. In this case, we wanted to pitch the method as general, but also bring up this specific example, which will be the focus of the paper.

[^2]: Clear statement of the big picture gap in knowledge.

[^3]: Drill down into exposition on this particularly relevant bit of background. Then get into the questions that are raised, elaborating on the question from the end of the above paragraph.

[^4]: Set up precisely the gap—and ONLY the parts of it that we will directly address.

[^5]: Here we talk about other methods. We had a bit of a tightrope to balance on here. Our goal in this paper was to emphasize the cool biology, but the technique is also clearly very cool. We elected to go with the biology first (above paragraph), but one could very easily have pushed this as a methods paper and gone with this paragraph first.

[^6]: Always have "however" statements in these paragraphs. That's how you distinguish your work from others. Contrast is key.

[^7]: End with a succinct statement about what the limitations of the field is, focusing on precisely the things that WE WILL ADDRESS.
