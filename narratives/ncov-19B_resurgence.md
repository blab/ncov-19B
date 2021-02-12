---
title: Resurgence of SARS-CoV-2 19B lineage
authors:
  - Cassia Wagner
  - Emma Hodcroft
  - Richard Neher
  - Trevor Bedford

authorLinks:
  - https://bedford.io/team/cassia-wagner/
  - https://www.ispm.unibe.ch/about_us/staff/hodcroft_emma/index_eng.html#pane1013282
  - https://neherlab.org/richard-neher.html
  - https://bedford.io/team/trevor-bedford/
affiliations: "Fred Hutch, Seattle, USA; ISPM, Bern, Switzerland, Biozentrum, Basel, Switzerland"

license: "CC-BY"  
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/groups/blab/ncov/19B?d=tree,map,entropy&legend=open"
date: "2021 February 11"

abstract: "Clade 19B viruses which had largely disappeared from circulation have slightly increased in frequency over the past two months.
Here we explore the genetic composition of viruses currently circulating in 19B. We find numerous examples of convergent evolution in the spike protein, which may contribute to its increasing frequency."
---

<!-- Comment tags like these are not rendered, they're just helpful for you -->
<!-- Known 'gotcha' bug: ensure that links always end in a 'letter' (a period counts). If some kind of text doesn't follow them, it breaks the slide. -->

<!-- SLIDE 1 -->
<!--  Each slide MUST start with a link to a specific view of the dataset (must match the `dataset` specified above) -->
# [Resurgence of clade 19B](https://nextstrain.org/ncov/global?d=tree&p=full)

<!-- This is left-side text -->
Here we see the SARS-CoV-2 global phylogeny colored by viral clade.
Clades 19A & 19B, in purple and dark blue at the bottom of the tree, predominated early in the pandemic.
However, these clades were soon eclipsed by viruses in clade 20.

Clade 20 probably dominated for multiple reasons:
This clade was exported globally, especially to Europe, as early as January 2020 where it spread rapidly undetected for over a month prior to lockdowns.
Additionally, spike D614G is one of the clade-defining mutations, and this substitution likely confers [increased transmissibility](https://pubmed.ncbi.nlm.nih.gov/32697968/).

Regardless, by June 2020, less than 10% of circulating virus were from clades 19A & 19B. By mid-September, frequency was no more than 1%.

However, transmission did continue at low levels. Recently, we have observed a slight increase in the frequency of 19B.
In December and January, we estimated 3% of all viruses to be 19B.

This resurgence of a viral clade that had largely died out, especially during the worst phase of the pandemic, is surprising.

To explore this phenomenon, we built a phylogeny enriched for recent 19A & 19B viruses.
In this report, we use that phylogeny to explore the genetic composition of currently circulating 19B virus.

<!-- There is NO right-side text on this slide -->


<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 2 -->
# [Recent 19B are present across the globe](https://nextstrain.org/groups/blab/ncov/19B?c=country&d=tree,map&dmin=2020-11-01&label=clade:19B&p=grid&legend=open)

<!-- This is the left-side text -->
Here we show all available sequences in clade 19B sampled from November 2020 onward.
These sequences were collected from across the globe in North America, South America, Europe, Africa, and the Middle East.
This suggests that transmission of this clade is ongoing in multiple locations.

Note: Our analysis is biased by the available data.
For example, almost half of all recent 19B sequences come from the UK, which is sequencing far more SARS-CoV-2 than any other country.

<!-- There is NO right-side text on this slide -->

<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 3 -->
# [Independent emergences of Spike 614G & 614N](https://nextstrain.org/groups/blab/ncov/19B?c=gt-S_614&d=tree&p=full&legend=open)

<!-- This is the left-side text -->
Coloring the tree by amino acid at spike 614, we observe, multiple independent emergences of 614G and 614N in 19B & 19A.
_In vitro_ ([Zhang et al](https://www.nature.com/articles/s41467-020-19808-4), [Yurkovetskiy et al](https://www.sciencedirect.com/science/article/pii/S0092867420312290), [Korber et al](https://pubmed.ncbi.nlm.nih.gov/32697968/)) and _in vivo_ work in mice and hamsters ([Hou et al](https://science.sciencemag.org/content/370/6523/1464), [Plante et al](https://www.nature.com/articles/s41586-020-2895-3)) demonstrate increased infectivity with the 614G substitution.

These examples of convergent evolution in the 19 clades add further support to a fitness advantage.
They also suggest that SARS-CoV-2 populations are actively being shaped by natural selection.

<!-- There is NO right-side text on this slide -->

<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 4 -->
# [Emergence of 501Y & 501T lineages in 19B](https://nextstrain.org/groups/blab/ncov/19B?c=gt-S_501&d=tree&p=full&legend=open)

<!-- This is the left-side text -->
We also observe emergence of spike 501Y (blue) and 501T (yellow) lineages in 19B.
501Y mutations are present in all three variants of concern: 2OI/501Y.V1 (B.1.1.7), 20H/501Y.V2 (B.1.351), and 20J/501Y.V3 (P.1).
_In vitro_ work demonstrates [enhanced ACE2 binding](https://jbloomlab.github.io/SARS-CoV-2-RBD_DMS/) with these mutations.

We will refer to these lineages as 19B:501Y & 19B:501T.

<!-- There is NO right-side text on this slide -->

<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 5 -->
# [19B:501Y & 19B:501T share spike mutations with variants of concern](https://nextstrain.org/groups/blab/ncov/19B?branchLabel=aa&c=gt-S_501&d=tree,map&f_clade_membership=19B&gt=S.501Y,501T&p=grid&label=clade:19B&legend=open)

<!-- This is the left-side text -->
Both spike 501 substitutions emerged on a 614D background.
They also both contain independent spike H655Y mutations, a mutation also present in 501Y.V3 which emerged in Brazil.

19B:501T contains the spike 69-70 deletion present in 501Y.V1.
This lineage has been sampled in France, Switzerland, Jordan, Turkey, Egypt, the United Arab Emirates, and the United States.

19B:501Y has several additional spike mutations.
L18F is present in 501Y.V2 and 501Y.V3.
A [preprint by McCallum et al](https://www.biorxiv.org/content/10.1101/2021.01.14.426475v1), found that this mutation reduced binding by one of six tested neutralizing N-terminal domain antibodies derived from COVID-19 convalescent serum.

The lineage also contains spike A653V, D796Y, G1219V, and L452R.
We will discuss L452R emergences later in this report.

19B:501Y has been sampled in Mayotte, Turkey, England, France, the Netherlands, Switzerland, and Denmark.

<!-- There is NO right-side text on this slide -->

<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 6 -->
# [E484K present in 19B](https://nextstrain.org/groups/blab/ncov/19B?branchLabel=aa&c=gt-S_484&d=tree&f_clade_membership=19B&gt=S.613H&label=clade:19B&legend=open)

<!-- This is the left-side text -->
Here we are highlighting another subclade in 19B with multiple spike mutations.
While this clade does not have a D614G substitution, it instead has a substitution in the adjacent residue, Q613H.

The subclade also contains F157L, V367F, and P681R.
P681H, a different but still positively charged amino acid at the same location, is present in 501Y.V1.
In a deep mutational scanning experiment of the receptor binding domain by [Starr et al](https://jbloomlab.github.io/SARS-CoV-2-RBD_DMS/), V367F was associated with increased expression.

E484K (yellow) emerged within this subclade.
This mutation is present in 501Y.V2 and 501Y.V3.
Multiple preprints have demonstrated reduced neutralization to convalescent sera, monoclonal antibodies and sera from individuals with Moderna or Pfizer-BioNTech vaccines with this mutation ([Greaney et al](https://www.biorxiv.org/content/10.1101/2020.12.31.425021v1), [Liu et al](https://www.biorxiv.org/content/10.1101/2020.11.06.372037v1), and [Wang et al](https://www.biorxiv.org/content/10.1101/2020.12.31.425021v1)).

R190S, a mutation present in 501Y.V3, occurs on the branch leading up to E484K.

<!-- There is NO right-side text on this slide -->

<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 7 -->
# [Multiple emergences of L452R](https://nextstrain.org/groups/blab/ncov/19B?c=gt-S_452&d=tree&f_clade_membership=19B&p=full&label=clade:19B&legend=open)
<!-- This is the left-side text -->
Coloring by amino acid at spike 452, we observe three independent emergences of 452R mutations (blue) and one emergence of a 452M mutation (yellow). L452R has been observed in a [lineage growing in frequency in California]((https://www.cdph.ca.gov/Programs/OPA/Pages/NR21-020.aspx) but the biological impact of this mutation, if any, is unknown.

One emergence of 452R was in 19B:501Y on a 614D backbone.
The second emergence was on a 614N backbone along with spike R190S, a mutation also present in 501Y.V3
The third emergence occurred on 614G backbone.
This lineage also contains a spike 140-143 deletions. A 143-144 deletion is observed in 501Y.V1.

These independent appearances of 452R could be examples of convergent evolution, which would suggest this mutation boosts viral fitness.

<!-- There is NO right-side text on this slide -->

<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 8 -->
# [Closing summary](https://nextstrain.org/groups/blab/ncov/19B?d=tree,map,entropy&legend=open)

<!-- This is the left-side text -->
In this report, we explored the genetic composition of viruses currently circulating in clade 19B.
We observed many 'familiar' mutations, including multiple emergences of spike D614G.

We found the following spike mutations also present in a variant of concern (501Y.V1, 501Y.V2, and 501Y.V3):
- 18F
- 69-70 del
- 143 del (along with 140-142 del)
- 190S
- 484K
- 501Y (and 501T)
- 614G (and 614N)
- 655Y
- 681R (681P is present in 501Y.V1)

There are 5 different SARS-CoV-2 lineages in 19B with at least two spike mutations present in a VOC.
These include 19B:501Y lineage and 19B:501T lineages.

We also see three independent emergences of L452R.
This mutation was identified in a lineage circulating in California and has an unknown biological impact.
Its recurrent emergence suggests it could boost viral fitness.

We find evidence of convergent evolution in the spike protein within 19B, which may have enabled these lineages to resurge.
While the proportion of 19B viruses remains quite low, it highlights that SARS-CoV-2 continues to adapt.


<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 9 -->
# [Scientific credit](https://nextstrain.org/groups/blab/ncov/19B?legend=open&d=map)
<!-- This is the left-side text -->
We would like to acknowledge the amazing and timely work done by all scientists involved in this outbreak.
Only through the rapid sharing of genomic data and metadata are analyses such as these possible.

**We encourage you to click on 'Explore the Data Yourself' and scroll down for a full list of authors; the author of each individual sequence is available by selecting it on the tree.**

We also gratefully acknowledge GISAID for providing the platform through which these data can be uploaded and shared.

<!-- There is NO right-side text on this slide -->
