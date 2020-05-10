# basic_proteomics_workflows

A walk through of basic proteomics workflows in use at the OHSU PSR core.

---

## Basic Proteomics Workflows

### author: Jennifer Cunliffe
### date: April 29, 2020
### OHSU Proteomics Shared Resource

***

![slide 1](images/Slide1.PNG)

_Slide 1_

This slide deck gives an overview of some of the work that we do in the PSR for non-affinity immunopurification experiments. Whether a targeted or shotgun assay, the sample prep portion follows a similar workflow. This slide shows a brief overview of each step and subsequent slides will go into more detail.
The first step is to plan the experiment and design the study, preferably in collaboration with the PSR. Step 1 also involves picking samples for analysis. Step 2 involves physically disrupting the sample, to lyse cells or increase the surface area of tissues, so that Step 3, denaturation and solubilization, and occur more efficiently. The denaturation step disrupts secondary structures of proteins allowing them to unfold, which makes them more accessible to the digestion enzymes used in Step 4. The digestion enzymes, typically trypsin but others as well, cut the proteins into smaller pieces called peptides. In some experiments, enrichments are performed to look at certain post-translational modifications (PTM, Step 5). If quantitative results are desired, the peptides can be [mass tagged in a multi-plex experiment](https://github.com/pwilmart/TMT_overview_2020) (Step 6). Regardless of PTM enrichments or mass tagging, the final step in the sample prep is to inject and detect the peptides by LC-MS/MS (Step 7) then analyze the data (Step 8).

***

![slide 2](images/Slide2.PNG)

_Slide 2_

The first step is to establish the study objectives and design the experiment, preferably in collaboration with the PSR. We will be able to help design the experiment knowing the strengths and limitations of our tools and techniques. Sample preparation methods vary with the type of samples analyzed.


***

![slide 3](images/Slide3.PNG)

_Slide 3_

The next step is to disrupt the sample, the method used depending on the sample type. This will release the contents of cells and increase the surface area of tissues, but the proteins will remain intact.

***

![slide 4](images/Slide4.PNG)

_Slide 4_

The third step is solubilizing and denaturing the proteins. If we are working with >10 mg of proteins, this is typically done with lysis buffers such as urea, deoxycholate or SDS, each with its down advantages and disadvantages.

***

![slide 5](images/Slide5.PNG)

_Slide 5_

If we are working with smaller amounts of protein, for example < 1 mg, then we might use [ProteaseMAX](https://www.promega.com/products/mass-spectrometry/proteases-and-surfactants/proteasemax-surfactant_-trypsin-enhancer/?catNum=V2071) or do an eFASP digestion, again, each with its advantages and disadvantages.

***

![slide 6](images/Slide6.PNG)

_Slide 6_

More recently we have started using [S-traps](https://www.protifi.com/s-trap/) to do some of our digestions. They come in 3 sizes so different amounts of protein can be accommodated. All of the steps occur in one vial/tube to minimize sample loss, and the procedure is much faster than eFASP.  

***

![slide 7](images/Slide7.PNG)

_Slide 7_

The next step is digestion, where an enzyme (typically [trypsin](https://en.wikipedia.org/wiki/Trypsin), but we use others when the situation warrants) cuts the protein into smaller pieces.
In the example at the bottom of the slide, using trypsin it would be difficult to localize on which serine the phosphorylation occurs. But if [Glu-C](https://www.promega.com/products/mass-spectrometry/proteases-and-surfactants/glu_c_-sequencing-grade/?catNum=V1651) was used, the serines would be in different peptides and it would be easy to differentiate them.

***

![slide 8](images/Slide8.PNG)

_Slide 8_


***

![slide 9](images/Slide9.PNG)

_Slide 9_

We often perform phosphopeptide enrichments using TiO2 beads. The beads target phospho-modified serines, threonines and tyrosines.  Adding a phospho group causes a mass shift of 80 Da. A more detailed description of the [TiO2 enrichment method used can be found here](https://www.ncbi.nlm.nih.gov/pubmed/25195567).

***

![slide 10](images/Slide10.PNG)

_Slide 10_

While discussing phosphopeptide enrichment techniques, it is worth taking a moment to discuss phospho site localization.

***

![slide 11](images/Slide11.PNG)

_Slide 11_

In the peptide shown in the slide, there are two possible phosphorylation sites (serines, shown in red). If the peptide has a mass shift of 80 Da, one of the serines is phosphorylated. In this case, there is MS2 fragmentation between the serines, and evidence of both serines being phosphorylated with the detection of the b14 and y8 ions. The underlined serines indicates it is phosphorylated.

***

![slide 12](images/Slide12.PNG)

_Slide 12_

In this case, the two phospho sites are only separated by one amino acid, and there are no fragments that lead to any conclusive site localization. Therefore it is impossible to assign the phosphorylation event to either the serine or threonine.

***

![slide 13](images/Slide13.PNG)

_Slide 13_

Some PTMs are enriched with immunoaffinity purification. [Cell Signaling Technologies](https://www.cellsignal.com/) offers a suite of antibodies against many common PTMs.

***

![slide 14](images/Slide14.PNG)

_Slide 14_

Please refer to the more detailed slide set on [TMT labeling for quantitative experiments](https://github.com/pwilmart/TMT_overview_2020).

Please refer to the more detailed slide set on LC-MS/MS analysis.

Please refer to the more detailed slide set on Data Analysis.

***

Thank you!
