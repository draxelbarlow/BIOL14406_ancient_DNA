---
title       : "Ancient DNA"
subtitle    : "BIOL14406: Living Systems"
author      : Dr Axel Barlow
job         : "email: axel.barlow@ntu.ac.uk"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # {zenburn, tomorrow, solarized-dark, ...}
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
logo        : ntu-shield.png
biglogo     : NTU_open-graph.png
assets      : {assets: ../../assets}
license     : by-nc-sa
github:
  user: draxelbarlow
  repo: BIOL14406_ancient_DNA
  branch: "gh-pages"
---



<!-- adding bold and italic options -->
<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## Ancient DNA

- Mitochondrial phylogenetics
- Ancient DNA
- Sabretooth cats
- Sequencing the North Sea *Homotherium*

<img src="./assets/img/smilodon1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="45%" style="display: block; margin: auto 0 auto auto;" />

--- .class #id

## Paijmans et al. 2017

<embed src="./assets/img/Paijmans et al. - 2017.pdf" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" width="100%" height="500" type="application/pdf" />

--- .segue .dark 

## Mitochondrial phylogenetics

--- &twocol bg:white

## You've probably seen diagrams like this...

### This is called a `phylogeny`. It represents the evolutionary process

*** =right

<img src="assets/fig/unnamed-chunk-3-1.png" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" width="80%" style="display: block; margin: auto;" />

*** =left

- The phylogeny works like an evolutionary tree
- The tips are species
- The branches show their relationships
- Nodes represents common ancestors, from which new species evolved
- Generally, phylogenies are calculated using **genetic data**

--- .class #id

## Inheritance plus mutation

- Errors in DNA replication (mutations) change the DNA sequence
- Human mutation rate is ~1.1×10−8 mutations per site per generation
- This means you carry ~40 mutations in your 3.6 Gb genome
- These differences are inherited by offspring
- Sequence divergence and time are (approximately) linearly related

### Phylogenetics works in reverse: we observe the DNA sequences and try to work out the tree that generated them

--- .class #id

## DNA sequence alignment

<img src="./assets/img/DNA_alingment.png" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" width="90%" style="display: block; margin: auto;" />

--- .class #id

## Mitochondrial DNA is great for phylogenetics!

<img src="./assets/img/Mitochondrion_mini.svg" title="plot of chunk unnamed-chunk-5" alt="plot of chunk unnamed-chunk-5" width="70%" style="display: block; margin: auto;" />

--- &twocol

## Mitochondrial DNA is great for phylogenetics!

*** =right

<img src="./assets/img/Map_of_the_human_mitochondrial_genome.svg" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" width="100%" style="display: block; margin: auto;" />

*Emmanuel Douzery, CC BY-SA 4.0*

*** =left

- Mitochondrial genome ~16 kb
- 13 protein-coding genes, 2 rRNAs and 22 tRNAs
- High mutation rate
- No recombination
- High copy number per cell
- Maternally inherited

--- .class bg:white

<img src="./assets/img/mtDNA_tree.svg" title="plot of chunk unnamed-chunk-7" alt="plot of chunk unnamed-chunk-7" width="95%" style="display: block; margin: auto;" />

--- .segue .dark 

## Ancient DNA

--- .class #id

## Ancient DNA is just old DNA

<img src="./assets/img/samples.png" title="plot of chunk unnamed-chunk-8" alt="plot of chunk unnamed-chunk-8" width="80%" style="display: block; margin: auto;" />

--- .class #id

## Some samples don't fit in the lab!

<img src="./assets/img/big_bone.jpg" title="plot of chunk unnamed-chunk-9" alt="plot of chunk unnamed-chunk-9" width="65%" style="display: block; margin: auto;" />

--- &vcenter

## Timeline of ancient DNA

<img src="./assets/img/timeline.svg" title="plot of chunk unnamed-chunk-10" alt="plot of chunk unnamed-chunk-10" width="100%" style="display: block; margin: auto;" />

--- .class #id

## Study species

<img src="./assets/img/extinct.png" title="plot of chunk unnamed-chunk-11" alt="plot of chunk unnamed-chunk-11" width="90%" style="display: block; margin: auto;" />

*Glyptodont, WolfmanSF, CC BY_SA 3.0*

--- .class #id

## What are the challenges?

<img src="./assets/img/workflow.svg" title="plot of chunk unnamed-chunk-12" alt="plot of chunk unnamed-chunk-12" width="80%" style="display: block; margin: auto;" />

--- .class #id

## Ancient DNA work is contamination sensitive

<img src="./assets/img/sina_lab.jpg" title="plot of chunk unnamed-chunk-13" alt="plot of chunk unnamed-chunk-13" width="80%" style="display: block; margin: auto;" />

--- .class #id

## Ancient DNA work is contamination sensitive

<img src="./assets/img/sinalab2.JPG" title="plot of chunk unnamed-chunk-14" alt="plot of chunk unnamed-chunk-14" width="50%" style="display: block; margin: auto;" />

--- &vcenter

## But the samples are already highly contaminated

<img src="./assets/img/endo.svg" title="plot of chunk unnamed-chunk-15" alt="plot of chunk unnamed-chunk-15" width="100%" style="display: block; margin: auto;" />

--- .segue .dark 

## Sabretooth cats

--- &twocol

## There were two genera of sabretooth cats

- **A genus us a group of closely related species. It's the first part of the scientific name**
- **e.g. Homo sapiens**

*** =left

### Smilodon

- The most commonly known group
- Massive canines
- > 400 kg and 120 cm shoulder height
- N and S America
- 3 species, *S. gracilis, S. populator, S. fatalis*
- Extinction 10 ka

*** =right

<img src="./assets/img/smilodon_skull.jpg" title="plot of chunk unnamed-chunk-16" alt="plot of chunk unnamed-chunk-16" width="100%" style="display: block; margin: auto;" />

--- &twocol

## There were two genera of sabretooth cats

- **A genus us a group of closely related species. It's the first part of the scientific name**
- **e.g. *Homo sapiens*)**

*** =left

### Homotherium

- Less known group
- Also known as scimitar-toothed cats
- Flat, serrated canines
- ~ 200 kg and 110 cm shoulder height
- Europe, Africa, N and S America
- Europe: *H. latidens*, extinction 300 ka
- N. America: *H. serum*, extinction 12 ka

*** =right

<img src="./assets/img/Homotherium_serum.jpg" title="plot of chunk unnamed-chunk-17" alt="plot of chunk unnamed-chunk-17" width="100%" style="display: block; margin: auto;" />

*Sergiodlarosa, CC BY-SA 3.0*

--- .class #id

## *Homotherium* skull

<img src="./assets/img/Homotherium_crenatidens_skull_45.jpg" title="plot of chunk unnamed-chunk-18" alt="plot of chunk unnamed-chunk-18" width="90%" style="display: block; margin: auto;" />

*Ghedoghedo, CC BY-SA 4.0*

--- &twocol

## Fishing for fossils

*** =left

- Britain connected to mainland Europe by an area called **Doggerland**
- Rising sea levels 6-7 ka flooded the area, making Britain an island

<img src="./assets/img/ship-2262650.jpg" title="plot of chunk unnamed-chunk-19" alt="plot of chunk unnamed-chunk-19" width="90%" style="display: block; margin: auto;" />

*** =right

<img src="./assets/img/Doggerland.svg" title="plot of chunk unnamed-chunk-20" alt="plot of chunk unnamed-chunk-20" width="90%" style="display: block; margin: auto;" />

*Max Naylor, CC BY-SA 3.0*

--- &vcenter

## 16th March 2000, something surprising turned up...

<img src="./assets/img/NS_Homo.png" title="plot of chunk unnamed-chunk-21" alt="plot of chunk unnamed-chunk-21" width="100%" style="display: block; margin: auto;" />

### This didn't look like a 300 ka fossil

--- .class #id

## Analysis of the Dutch North Sea *Homotherium*

### Dating

 >- The bone was radiocarbon dated at 31,300 ± 400!
 >- This was extraordinary, so the dating was repeated:
  + 31,300 ± 400
  + 26,900 ± 400
  + 26,700 ± 240
  + 28,100 ± 220
  + 27,650 ± 280

>- The first Late Pleistocene European *Homotherium*

--- .class #id

## Analysis of the Dutch North Sea *Homotherium*

### Ancient DNA

<img src="./assets/img/hofreiter_02c.png" title="plot of chunk unnamed-chunk-22" alt="plot of chunk unnamed-chunk-22" width="50%" style="display: block; margin: auto auto auto 0;" />

- A sample was taken in 2006 by Prof. Michi Hofreiter
- Some tiny sequences were recovered, but they were too short to provide conclusive results...

--- .segue .dark 

## Sequencing the North Sea *Homotherium*

--- &twocol

## By 2014 the technology had improved substantially

*** =left

- Widespread adoption of Next Generation Sequencing by the aDNA community
- Improved DNA extraction methods
- Improved library preparation methods
- A targeted sequencing technique called **DNA hybridisation capture**

*** =right

<img src="./assets/img/me_cropped.jpg" title="plot of chunk unnamed-chunk-23" alt="plot of chunk unnamed-chunk-23" width="70%" style="display: block; margin: auto;" />

- Michi gave the sample to his PhD student, Johanna Paijmans, to try again

--- &vcenter

## Initial sequencing showed extremely high contamination

<img src="./assets/img/endo.svg" title="plot of chunk unnamed-chunk-24" alt="plot of chunk unnamed-chunk-24" width="100%" style="display: block; margin: auto;" />

--- &twocol

## DNA hybridisation capture

### "Fishes" mitochondrial fragments from the contaminated ancient DNA

*** =left

- DNA has 2 strands, arrange in a double helix
- It can be heat denatured
- When cooled, the single strands will stick (hybridise) to strands with a similar sequence
- Manufacture "bait" sequences that match your target region
- Use to capture these sequences from the contaminants

*** =right

<img src="./assets/img/Dna-base-flipping.svg" title="plot of chunk unnamed-chunk-25" alt="plot of chunk unnamed-chunk-25" width="100%" />

*Magladem96, CC BY-SA 3.0*

--- &vcenter

## DNA hybridisation capture

<img src="./assets/img/hybr.svg" title="plot of chunk unnamed-chunk-26" alt="plot of chunk unnamed-chunk-26" width="90%" />

### This only works if you know the sequence in advance

--- &twocol

## Meanwhile a Danish group were sequencing North American cave lion mtDNA

*** =right

<img src="./assets/img/NA_Homo.png" title="plot of chunk unnamed-chunk-27" alt="plot of chunk unnamed-chunk-27" width="100%" style="display: block; margin: auto;" />

*** =left

- Sequence analysis showed it was actually a *Homotherium*
- They provided the sequence and Johanna ordered the hybridisation cature baits

--- &vcenter

## The hybridisation capture worked!

<img src="./assets/img/endo2.svg" title="plot of chunk unnamed-chunk-28" alt="plot of chunk unnamed-chunk-28" width="100%" style="display: block; margin: auto;" />

--- .class #id

## Phylogenetic analysis of sabretooth cats

<img src="./assets/img/sabre_tree_NODATE.svg" title="plot of chunk unnamed-chunk-29" alt="plot of chunk unnamed-chunk-29" width="80%" style="display: block; margin: auto;" />

--- .class #id

## The final step: molecular dating

- Molecular phylogenies are scaled to genetic divergence
- We know genetic divergence and time are linearly related

### If we know some of the divergence times, we can scale the tree to time

--- .class #id

## Phylogenetic analysis of sabretooth cats

<img src="./assets/img/sabre_tree.svg" title="plot of chunk unnamed-chunk-30" alt="plot of chunk unnamed-chunk-30" width="80%" style="display: block; margin: auto;" />

--- .class #id

## Molecular dating of sabretooth cats

- Sabretooths divergence from living cats 20 Ma
- *Homotherium* and *Smilodon* were more diverged from one another than any living cats
- A huge diversity was lost with the extinction of the sabretooths
- North American and European *Homotherium* were genetically similar
- We recommended they be treated as a single species, *H. latidens*

--- .class #id

## Paijmans et al. 2017

<embed src="./assets/img/Paijmans et al. - 2017.pdf" title="plot of chunk unnamed-chunk-31" alt="plot of chunk unnamed-chunk-31" width="100%" height="500" type="application/pdf" />

--- &thankyou

## Ancient DNA

**An exciting and dynamic field driven by technological advances**

