# Annotated review of tech paper

\[ALL DETAILS CHANGED TO DEIDENTIFY. CONSEQUENTLY, THE REVIEW MAY NOT MAKE ANY SENSE, SCIENTIFICALLY]

This was a technology paper about nanopore sequencing applied to viral populations. It was generally pretty strong, but the analysis had some issues.

***

{% hint style="info" %}
The first paragraph should be a summary of what the paper was in your own words. It’s basically to show that you read and understood the paper. I usually do NOT say anything about whether I liked the paper, although if it’s really nice, I’ll sometimes say “In this very nice manuscript…”. I usually aim for around 4-5 sentences. This one is perhaps a bit long.
{% endhint %}

In this manuscript, McPaperFace and colleagues describe a new method of nanopore sequencing of viruses (NVIR-seq), enabling researchers to sequence individual viruses directly in their natural context. They describe their workflow and focus on their graphene synthesis and chemical functionalization methods. They validated their method on a defined viral community, and obtained read counts and genome coverage for each virus. The calculate a metric of plasticity for each individual virus, indicating the degree of variation in the genome. Using NVIR-seq, they show the viral composition of a soil sample from the wild, finding several interesting genes within these various genes.



{% hint style="info" %}
The second paragraph is an overall assessment of the paper and its “impact”. How exciting is the paper, and why? I usually always say something positive here, although how positive might vary. I usually include something about the data being of high quality. The editor is looking for this paragraph to get their overall assessment of whether the paper is interesting enough for their journal.
{% endhint %}

Overall, I think that this paper is very exciting. The method represents an innovative combination of genomics and material synthesis. Moreover, the scale of the method, being able to sequence large numbers of virions, is sufficient for most applications, and their application was an excellent demonstration of this capacity. One can imagine applications outside of this original area, potentially to the genomes of microbial communities or tumor cells. The data are all of very high quality.

<br>

{% hint style="info" %}
If I have a major overarching theme to my concerns, then I will have another paragraph describing that concern, along with a general prescription for what to do about it. It can be general, but should be backed up by specific points (more on that later). This paragraph signals to the editor that this is a big problem with the manuscript and needs to be addressed. If the paper has no major flaws, then I will sometimes drop this paragraph entirely and just go straight to the specific concerns.
{% endhint %}

My main comment is that the method could benefit from a more precise quantification of the output. I fully believe that the technique itself is accurate and is valid, but shoring up the quantification would help make their conclusions more solidly supported. More specifically:



{% hint style="info" %}
Here’s where we talk about specific concerns. BE SPECIFIC. Not like “the analysis was lacking” or “such and such was unconvincing”. What was lacking? What was unconvincing? And SPECIFICALLY what can the authors do to solve that? This is very important, because sometimes by thinking about that, you realize that it’s not really possible to address the issue. Rather (and this is generally true) I try to make them alter the language of what they can claim given the data they have. If the reduction in claims makes the paper way less interesting, then that’s the editor’s call, in my opinion.

I avoid asking for new experiments, but new analyses of existing data is fair game, in my opinion. Oh, and don’t worry about things like grammar and other nitty gritty. Not our job.
{% endhint %}

{% hint style="info" %}
Here’s an example of a technical issue with the analysis. I have tried to be quite specific and prescriptive.
{% endhint %}

1\. The plasticity metric is reasonable when the number of genes in the genome is unknown. But in cases where they are known (Fig. 4h), I think normalizing by the number of reads would make this metric more easy to interpret.



{% hint style="info" %}
Be sure to explain clearly exactly what the potential issue is. Try to phrase in terms of a question and discussion with the author. This is nice, because it makes it feel like more of a discussion.
{% endhint %}

2\. It would be nice to have a bit more quantitative analysis of the issue of genes being erroneously assigned to the wrong genome. From the data (Table 2), it seems that around 82% of genes are likely assigned to the right genome. For the remaining 18%, can the authors give the next best guess genome that it should be assigned to? If to another known virus, then it would naively make sense to me to make a cutoff of 70% based on the data shown in Fig. 82g. Estimating what cutoff to use would be important for the interpretation in a host of applications.



{% hint style="info" %}
Trying to help the authors out on the above point.
{% endhint %}

3\. As per above, do specific viruses have more issues with misassignments? If so, it would argue the issue is more biological than technical.



{% hint style="info" %}
If there’s some apparent discrepancy, I usually just ask the authors to explain it rather than saying this is evidence of a big problem. They may have a good explanation or not, but give them the benefit of the doubt.
{% endhint %}

4\. In Fig. 33k, the authors show that validation by conventional sequencing yields much higher rates of gene plasticity than expected by their own NVIR-seq data. Can the authors discuss why this discrepancy exists.



{% hint style="info" %}
Minor point. Can comment on points of clarity.
{% endhint %}

5\. Acronyms like EIEIO and LMNOP detract from the clarity of the manuscript.



{% hint style="info" %}
I sign my reviews but you don’t have to.
{% endhint %}

Arjun Raj

<br>
