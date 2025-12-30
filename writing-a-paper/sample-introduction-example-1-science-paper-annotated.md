# Sample introduction example 1 (science paper, annotated)

{% hint style="info" %}
Nice declarative title. Not crazy about "suggest" but whatever.
{% endhint %}

### The spatial distributions of pre-mRNAs suggest post-transcriptional splicing of specific introns within endogenous genes

### Abstract

{% hint style="info" %}
Not commenting about abstract in this case, but it's useful because people typically read it before they read the intro.
{% endhint %}

Splicing is the molecular process by which introns are removed from pre-mRNA and exons are joined together to form the sequence of the mature mRNA. Measuring the timing of splicing relative to the transcription of nascent RNA has yielded conflicting interpretations. Biochemical fractionation suggests that RNA is spliced primarily during the process of transcription, but imaging of nascent RNA suggests that splicing happens after the process of transcription has been completed. We use single molecule RNA FISH together with expansion microscopy to measure the spatial distribution of nascent and partially spliced transcripts in mammalian cells, allowing us to infer the delay between when an intron is transcribed and when it is spliced out of a pre-mRNA. We show that 5 out of 5 genes we interrogated exhibit some post-transcriptional splicing, and that introns can be spliced in any order. We also show that completely synthesized RNA move slowly through a transcription site proximal zone while they undergo additional splicing and potentially other processing after transcription is completed. In addition, upon leaving this zone, some genes localize to speckles during the process of splicing but some appear to traffic freely through the nucleus without localizing to any other nuclear compartment. Taken together, our observations suggest that the regulation of the timing and localization of splicing is specific to individual introns, as opposed to the previously surmised immediate excision of introns after transcription.

{% hint style="info" %}
An introduction is not a review article. Concisely introduce just the concepts and literature you need, making sure they are all directed to the questions YOU WILL ANSWER (and not ones you don't answer).
{% endhint %}

### Introduction

The mRNA transcribed by most eukaryotic genes are spliced, a process in which the intronic RNA sequence is removed and the exonic RNA are joined together to form the ultimate mature mRNA sequence. [<mark style="background-color:orange;">A major question in the field</mark>](#user-content-fn-1)[^1] is how tightly associated the process of transcription and splicing are, with some work suggesting that splicing occurs very shortly after the RNA polymerase transcribes a particular splice junction [(Beyer, Bouton, and Miller 1981; Carrillo Oesterreich et al. 2016)](https://paperpile.com/c/Ltwq9O/F32w+8rmh), while other work suggests that many pre-mRNAs are fully transcribed before splicing occurs [(Tsai et al. 1980; Drexler, Choquet, and Churchman 2019; Coulon et al. 2014)](https://paperpile.com/c/Ltwq9O/AiWg+7ykT+aOA1). [<mark style="background-color:orange;">The relative spatial</mark>](#user-content-fn-2)[^2] locations of nascent pre-mRNA, fully transcribed pre-mRNA, and mature mRNA species have the potential to directly reveal where—and consequently in what order—the processes of transcription and splicing are occurring. [<mark style="background-color:orange;">However</mark>,](#user-content-fn-3)[^3] to date, using molecular imaging to systematically measure the locations of these partially processed RNA intermediates has been limited in scope (interrogating single intron reporter genes or single introns within endogenous genes) [(Waks, Klein, and Silver 2011; Vargas et al. 2011; Coulon et al. 2014)](https://paperpile.com/c/Ltwq9O/AyXd+Q7F4+aOA1). This limitation in scope is due largely to lack of probes designed to target specific splicing intermediates of endogenous genes.

[<mark style="background-color:orange;">In lieu of direct visualization</mark>](#user-content-fn-4)[^4], many have turned to biochemical fractionation to infer the location of various intermediates [(Tilgner et al. 2012; Wuarin and Schibler 1994; Bhatt et al. 2012; Pandya-Jones et al. 2013; Pandya-Jones and Black 2009; Drexler, Choquet, and Stirling Churchman 2019; Mayer et al. 2015)](https://paperpile.com/c/Ltwq9O/dwqb+69DP+dzkk+VA6l+pVSI+zKKOV+7x9xQ). Fractionation methods separate cellular RNA into different compartments, such as the putatively chromatin associated RNA, nucleoplasmic RNA, and cytoplasmic RNA, by centrifuging the cellular components in different lysis buffers and sedimentation gradients [(Mayer and Churchman 2017)](https://paperpile.com/c/Ltwq9O/tg8d). [<mark style="background-color:orange;">The implicit assumption</mark>](#user-content-fn-5)[^5] made by such fractionation based methods is that the RNA species in the “chromatin fraction” represent nascent pre-mRNA that are still tethered to the gene body by the RNA polymerase II itself, and that once the pre-mRNA are fully transcribed, the pre-mRNA move immediately and directly into the nucleoplasm. Under these assumptions, any splicing observed in the chromatin fraction would be assumed to be co-transcriptional. However, this assumption may not hold: it is possible that the pre-mRNA remains in a chromatin associated compartment for some time after transcription completes, and thus splicing observed in chromatin compartment may in fact still be post-transcriptional. Some groups have tried testing this assumption explicitly by isolating nascent RNA via metabolic labeling or by using RNA Polymerase II antibodies, but these methods are still prone to contamination by nearby RNA [(Nojima et al. 2015; Harlen et al. 2016; Harlen and Churchman 2017)](https://paperpile.com/c/Ltwq9O/R3y7+Uxh1+3T18). [<mark style="background-color:orange;">Ultimately</mark>](#user-content-fn-6)[^6], such alternative explanations are difficult to eliminate without an independent and explicit verification of which RNA intermediates reside in particular compartments.

[<mark style="background-color:orange;">Meanwhile</mark>](#user-content-fn-7)[^7], advances in RNA imaging have enabled researchers to image RNA intermediates with single molecule resolution, both in fixed and living cells [(Waks, Klein, and Silver 2011; Zhang et al. 1994; Coulon et al. 2014; Martin et al. 2013; Levesque and Raj 2013; Vargas et al. 2011)](https://paperpile.com/c/Ltwq9O/AyXd+KLYZB+aOA1+lihMJ+gQof+Q7F4). Imaging using probes targeting both exonic and intronic regions of RNA has revealed bright nuclear foci that represent nascently transcribing RNA [(Levesque and Raj 2013; Vargas et al. 2011)](https://paperpile.com/c/Ltwq9O/gQof+Q7F4). The general lack of intronic signal away from these transcription sites has been taken as evidence for co-transcriptional splicing, with notable cases of post-transcriptional splicing at speckles being observed in special cases [(Vargas et al. 2011)](https://paperpile.com/c/Ltwq9O/Q7F4). [<mark style="background-color:orange;">However, owing to the diffraction limit for optical microscopy</mark>](#user-content-fn-8)[^8], it has been difficult to visualize RNA intermediates in the immediate vicinity of the gene undergoing transcription, thus making it difficult to see whether RNA are still actively being transcribed during splicing or remain at the site of transcription for some time after transcription is complete. [<mark style="background-color:orange;">Since splicing would appear to occur in the “chromatin fraction” in both of these scenarios, it is possible that much splicing is actually occurring in this transcription proximal region. Indeed, recent live imaging methods showed that the splicing of a reporter gene is 85% post-transcriptional, suggesting the latter, but as RNA from endogenous genes may be processed differently, the use of reporter genes leaves open the question of when endogenous genes undergo splicing relative to their transcription.</mark> ](#user-content-fn-9)[^9]

{% hint style="info" %}
The final paragraph is typically a short description of the work (often omitted in short form "letter" type articles).\
\
Highlight key results here. Do NOT just reiterate the abstract. Instead, try and keep it higher level and focus on the answers we found specifically for the questions raised earlier in the intro.
{% endhint %}

Here, we designed probes to comprehensively interrogate the [<mark style="background-color:orange;">spatial localization of several RNA intermediates using a combination of RNA FISH and expansion microscopy</mark>](#user-content-fn-10)[^10] [(F. Chen et al. 2016; F. Chen, Tillberg, and Boyden 2015)](https://paperpile.com/c/Ltwq9O/WBa0+KbDK). We revealed the ordering of transcriptional and splicing processes with single molecule resolution. We found that the proportion of splicing that occurs post-transcriptionally varies from intron to intron within a single gene, but that all endogenous genes we tested displayed some degree of post-transcriptional splicing. We also employed expansion microscopy to demonstrate that newly synthesized RNA dwell and undergo continuous splicing near the site of transcription after transcription is complete. These RNA are untethered to the site of transcription and eventually diffuse into either the nucleoplasm or near nuclear speckles.

<br>

[^1]: Sets up the question in broad terms, highlighting a broad controversy in the field.

[^2]: This sentence foreshadows what we will do.

[^3]: End first paragraph with a big picture statement of the gap that needs to be filled.

[^4]: Here, start to get into more detail. We wanted to contrast two different approaches: fractionation/sequencing vs. imaging. Start with fractionation.

[^5]: Highlight potential issue with literature.

[^6]: End with a description of what is not resolved by these methods—with an eye to what we WILL resolve.

[^7]: Similar to previous, just this time about imaging.

[^8]: Highlight what others haven't been able to do because they didn't have the ability… specifically telegraphing what we WILL do.

[^9]: Gap, along with alternative explanations for existing data.

[^10]: Briefly describe approach.
