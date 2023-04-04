---
layout: page
title: SIRIG
subtitle: Systematic study of inverted repeated sequences in prokaryotic genomes
permalink: /
redirect_from:
  - /about/
  - /about.html
---


DNA sequence motifs are short sequences found many times in a genome, often
associated with a biological function. Amongst particular motifs, an inverted
repeat (IR) is a nucleotide sequence followed downstream by its reverse
complement (e.g., ATACGG followed by CCGTAT), potentially with a gap in the
center (e.g., ATACGGnnnCGTAT). They are involved in many biological processes,
including gene regulation, replication, translocation, and recombination.
Thanks to the advent of high-throughput sequencing, the number of fully
sequenced genomes has grown exponentially, paving the way for systematic
studies of motifs. Yet, despite two types of IRs found in prokaryotes
revolutionizing molecular biology (CRISPR-cas and restriction enzyme cutting
sites), IRs have never been systematically studied in prokaryotic genomes.

In SIRIG, we aim to develop efficient computational and statistical tools to
systematically detect and characterize IRs in prokaryotic genomes. 

## People

<div class="block">
{% for post in site.peoples %}
    {% include archive-people-index.html %}
{% endfor %}

<br />
  
</div>




## Publications

<div class="block">

{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
{% endfor %}
</div>

