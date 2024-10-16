# Annotated example of a specific aims page

## How to approach a specific aims page

There are many ways to write a good specific aims page. Below is one example, annotated with what I think are strengths. The aims page is particularly important because it’s the part of your application that gets read by far the most. While the reviewers will read the whole thing (hopefully), they will be armed with this particular bit of paper when they are trying to defend your grant to all the other people who just have this aims page in front of them. It sets the tone for the whole thing. So spend some time on it!

**A couple things to note:**

1. You can do 2 or 3 aims. I’ve seen good arguments either way. Both can work.
2. Emphasize the gap in knowledge. More important than the details of what you do is the motivation for why you are doing it. If you are able to convince someone that the problem is important and unsolved, then you’re on the right track.
3. Once the problem is set up, then briefly give an overview of your approach and why it is the right one, and either implicitly or explicitly say why nobody has done it before and why you are the person to do it.
4. Be clear! Make sure you are writing to a general audience. Aim for your non-scientist relative and you’ll probably end up hitting the target, roughly. Remember that the people who read your application may or may not be experts in your area. If they are an expert, they should be able to recognize why it’s important anyway despite the generalist writing—don’t worry about trying to “impress” them with fancy words you may or may not know.

Anyway, on to the aims…

## Specific Aims

{% hint style="info" %}
This application received a 10, which is a perfect (!) score. Much of that had to do with the stellar applicant, but also, this proposal is very compelling. (Yes, I'm biased.)
{% endhint %}

Several phenomena in cancer, including drug-resistance and metastasis, are driven by the unique behavior of rare cells, and identifying what is different about these cells at the molecular level can [<mark style="background-color:orange;">inspire development of novel therapeutics</mark>](#user-content-fn-1)[^1]. For example, we and others have shown that rare single-cell differences in chromatin state, gene expression and protein signaling can contribute to therapy resistance in diverse cancers, and targeting these processes improves drug sensitivity. [<mark style="background-color:orange;">However</mark>](#user-content-fn-2)[^2], as disease progresses these cells evolve new characteristics that may be unrelated to what initially allowed them to survive treatment or seed metastases. Therefore, profiling cancer cells after treatment or metastasis, as is currently done, may miss fundamental drivers of cancer progression. [<mark style="background-color:orange;">Instead,</mark> <mark style="background-color:orange;"></mark><mark style="background-color:orange;">**we require a method that can go back in time and characterize those initial cells that give rise to drug resistant and invasive cells.**</mark>](#user-content-fn-3)[^3]

[<mark style="background-color:orange;">By</mark>](#user-content-fn-4)[^4] [<mark style="background-color:orange;">combining RNA FISH with single-cell barcoding</mark>](#user-content-fn-5)[^5], we aim to develop this biological time machine and isolate the initial rare cells that give rise to targeted-therapy resistant and metastatic melanoma. We will leverage our recently developed lentivirus library capable of labeling millions of cells with unique transcribed barcodes along with a novel technique for amplifying RNA FISH signal beyond the threshold for cell sorting. [<mark style="background-color:orange;">In our preliminary data</mark>](#user-content-fn-6)[^6], we have demonstrated that these barcodes can be detected by sequencing and RNA FISH, setting the stage for isolating a clonal progenitor based on its unique barcode. Our approach begins by transducing cancer cells with the lentivirus library, culturing labeled cells for a few cell divisions, then splitting the population to create a “carbon-copy” frozen in time. With the unfrozen cells, we then select for a phenotype, such as drug-resistance or invasiveness, and sequence the barcodes in cells exhibiting these behaviors. Returning to the carbon copy, we use RNA FISH to fluorescently label cells carrying these same barcodes. After amplifying the specific fluorescent signal, we will sort out this rare cell population and directly measure the gene-expression and epigenetic profile of cells fated to become drug-resistant or metastatic. In turn, we will identify gene expression markers and regulators driving these cell behaviors, then validate them functionally via an iterative approach. [<mark style="background-color:orange;">More generally</mark>](#user-content-fn-7)[^7], through completion of these aims, we will establish a method for characterizing the molecular state of a cell based on its ultimate phenotype and enable a new approach for studying cancer, development and cellular differentiation.&#x20;

[<mark style="background-color:orange;">**Aim 1**</mark>](#user-content-fn-8)[^8]**:** [<mark style="background-color:orange;">**Isolate**</mark>](#user-content-fn-9)[^9] **and profile the initial drug-naive melanoma cells giving rise to drug resistant colonies.**

[<mark style="background-color:orange;">1A)</mark>](#user-content-fn-10)[^10] Identify the drug-naive melanoma cells that give rise to BRAF and MEK inhibitor resistance using RNA FISH targeting specific barcodes shared with drug resistant colonies. Characterize their gene expression state and gene expression variability using multiplexed single-molecule RNA-FISH.

1B) Use RNA FISH amplification to sort rare, drug-naive melanoma cells giving rise to drug resistant colonies. Perform RNA-seq and ATAC-seq on sorted cells to characterize gene-expression and epigenetic profiles underlying the initial drug-resistant cell state. [<mark style="background-color:orange;">Functionally validate</mark>](#user-content-fn-11)[^11] these states by sorting on markers identified in the RNA-seq and testing for drug resistance. Then use the combination of RNA-seq and ATAC-seq to predict epigenetic regulators of drug-resistance and experimentally test these predictions using chemical and CRISPR-based perturbations in patient-derived melanoma cell lines.&#x20;

[<mark style="background-color:orange;">**Aim 2**</mark>](#user-content-fn-12)[^12]**:** [<mark style="background-color:orange;">**Characterize**</mark>](#user-content-fn-13)[^13] **the subpopulation of cells that seed melanoma metastases in animal models.**&#x20;

2A) Using barcodes integrated into human xenograft and syngeneic mouse models, determine the fraction of cells capable of metastasis and whether there are stable differences in a clone’s propensity to metastasize to specific tissues and across animals. &#x20;

2B) Determine the gene expression changes that occur during the course of metastasis using barcodes to connect clonal lineages in primary and metastatic tumors. Using these data, identify markers that predict metastasis and tissue tropism, then isolate cell populations expressing these markers for functional characterization. &#x20;

\


[^1]: Important for NIH to set up disease relevance. Less so for NSF.

[^2]: There should always be a "However, …" statement in this paragraph. Once the background/importance is set up, then it is critical to emphasize the problem and the gap in knowledge.

[^3]: End first paragraph with a discussion of the gap/unmet need. Then, go on to say what we will do to address that gap.

[^4]: Once you've described the gap, give a quick one sentence summary of how you are going to fill that gap.

[^5]: Using the word "combine" is good, especially if you can emphasize a combination of experimental and computational approaches.\
    \
    This particular combination (imaging and sequencing) helps to emphasize here that not everyone can do this work because most people don't have both sets of expertise (at least implicitly).

[^6]: Quick description of preliminary data helps to establish plausibility and that you are the person for the job.

[^7]: End with a broad statement of the impact that your solution to this problem will have.

[^8]: Aims should not be "interdependent". In this case, we used the preliminary data to establish feasibility of the method. The two aims are then two applications of the method. This approach does put a LOT of pressure on the preliminary data to be solid, though.

[^9]: This proposal is more of a methods one, so the aims are not as explicit about testing a particular hypothesis. If your proposal is more science oriented, then these should typically be more hypothesis oriented.

[^10]: Sometimes good to do subaims, but not necessary.

[^11]: Describe validation studies and controls in the aim if possible.

[^12]: This aim is clearly more challenging than the other. Aims don't have to be equal in scope or difficulty or even in terms of how much you write about them. If 1 of the 2 aims is really solid, then other can be more speculative.

[^13]: Characterizing (instead of hypothesizing) as long as you can make a good argument for the importance of what you are measuring.
