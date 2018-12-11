# Precision Medicine 
1. [Introduction](#1)
2. [Pharmacogenomics](#2)<br>
3. [Precision Medicine in Cancer](#3)
4. [RNA Detection and Quantification Technologies](#4)
    4.1. [Northern Blot](#41)<br>
    4.2. [RT-qPCR](#42)<br>
    4.3. [Hybridization based microarrays](#43)<br>
    4.4. [RNA-seq](#44)<br>
5. [Gene Expression Assays in Medicine](#5)



## Introduction<a name="1"></a>

Precision medicine is defined as the act of tailoring medical treatment such that it takes into consideration the individual characteristics of each patient's case [1]. Traditionally, medicine has been practiced with a "one fits all" approach, where the same standard tests and common drugs are used to treat the same phenotypically-appearing symptoms. This new approach of precision medicine looks beyond phenotype by gathering a genetic understanding of the individual's disease and applying it to how health care is delivered to the patient.

To gather a genetic understanding of a patient's disease, various types of data are taken into consideration. This includes the patient's genetic/health history, their response to the disease, and their lifestyle. Each of these factors are significant in understanding how the patient's disease may have developed as well as how it can currently be characterized.

> FAQ: What is the difference between "precison" medicine and "personalized" medicine? "Personalized" was used initially, but this term gave rise to the concern that it would be misinterpreted as using an approach that is unique to _each_ person. However, the idea is not that an individual receives their very own unique treatment; the idea is that targeted therapies are developed based on molecular diagnostics. "Personalized" medicine refers to the practice of handling a patient's care hollistically, while "precision" medicine refers to the science of creating evidence-based medicine [2].

## Pharmacogenomics<a name="2"></a>

The process of delivering precision medicine does not end when a targeted therapeutic drug is developed. It must continue with ensuring if the patient will respond well and effectively to it. This gives way to an integral field of precision medicine - pharmacogenomics. Pharmacogenomics is the study of how genes and genetic variations affect a patient's response to therapeutic drug treatment [3]. This involves taking a hollistic approach in drug design to minimize chances of adverse health effects because knowing a patient's genetic makeup can help with predicting the outcome of certain therapies. Pharmacogenomics allows scientists and doctors to address questions such as: will the drug optimally target the abnormality that needs fixing? Will it induce any negative side effects known to occur in the patient? Will it potentially cause further complications due to other genetic factors that must be considered for this patient?

Research has been and is currently being done to further scientists' knowledge on how genetic variations can affect the human body's response to medications. For instance, the Human Genome Project is working towards combining sequencing information gathered from many genomes with current knowledge on gene functions to enhance drug discovery by understanding why particular genotypes found in these genomes respond a certain way - and therefore identifying subpopulations that may benefit most from a certain drug [4]. Although the current use of pharmacogenomics is still quite limited due to a continued need for growing knowledge, it will further the development of tailoring drugs to treat a wide range of health problems in the future.

![](/assets/1-s2.0-S1360138518300827-gr1b2_lrg.jpg)
[Figure1](https://doi.org/10.1016/j.tplants.2018.03.014). Schematic Representation of Chromosome Conformation Capture (3C) and 3C-Derived Methods. These methods help to elucidate nuclear organization by detecting physical interactions between genetic elements located throughout the genome. Abbreviations: IP, immunoprecipitation; RE, restriction enzyme. **Figure by Sotelo-Silveira, Mariana, et al. Trends in Plant Science (2018).**

To better understand the difference between these methods, I'd like to distingush them between the following couple of aspects:

#### 1) Specificity - What does _one, all, many_ mean<a name="2321"></a>
‘1’, ‘Many’ and ‘All’ indicate how many loci are interrogated in a given experiment. For example, ‘1 versus All’ indicates that the experiment probes the interaction profile between 1 locus and all other potential loci in the genome. ‘All versus All’ means that one can detect the interaction profiles of all loci, genome-wide, and their interactions with all other genomic loci [1].

These kind of specificity is determined by the primer when people use **specific primers** before PCR. 

#### 2) Through-put and resolution<a name="2322"></a>
Hi-C techniques has the highest through-put (billion reads per sample) but suffering of a relative low resolution of 0.1-1Mb. However, the other methods usually have a higher resolution  around 1kb. For more details one can refer to table2 in [2].

## 2.3.3 Hi-C<a name="233"></a>
Hi-C is the highest through-put version of 3C-derived technologies. Due to the decreasing cost of 2nd generation sequencing, hi-c is widely used.

The principle of Hi-C can be illustrated as:
![](/assets/hic.gif)


##### Hi-C critical steps [8] 
- Fixation: keep DNA conformed
- Digestion: enzyme frequency and penetratin
- Fill-in: biotin for junction enrichment
- Ligation: freeze interactions in sequence
- Biotin removal: junctions only
- Fragment size: small fragments sequence better
- Adapter ligation: paired-end and indexing
- PCR: create enough material for flow cell

##### Hi-C derived techniques 
- Hi-C original: [Lieberman-Aiden et al., Science 2010](doi: 10.1126/science.1181369)
- Hi-C 1.0: [Belton-JM et al., Methods 2012](doi: 10.1016/j.ymeth.2012.05.001)
- In situ Hi-C: [Rao et al., Cell 2014](doi: 10.1016/j.cell.2014.11.021)
- Single cell Hi-C: [Nagano et al., Genome Biology 2015](https://doi.org/10.1186/s13059-015-0753-7)
- DNase Hi-C [Ma, Wenxiu, Methods et al](https://www.ncbi.nlm.nih.gov/pubmed/25437436)
- Hi-C 2.0: [Belaghzal et al., Methods 2017](https://www.ncbi.nlm.nih.gov/pubmed/28435001)
- DLO-Hi-C: [Lin et al., Nature Genetics 2018](https://doi.org/10.1038/s41588-018-0111-2)
- Hi-C improving: [Golloshi et al., Methods 2018](https://www.biorxiv.org/content/biorxiv/early/2018/02/13/264515.full.pdf)
- Arima 1-day Hi-C: [Ghurye et al., BioRxiv 2018](https://www.biorxiv.org/content/early/2018/02/07/261149)

## 2.3.4 ChIA-PET<a name="234"></a> 
ChIA-PET is another method that combines ChIP and pair-end sequencing to analysis the chromtin interaction. It allows for targeted binding factors such as: estrogen receptor alpha, CTCF-mediated loops, RNA polymerase II, and a combination of key architectural factors. on the one hand, it has the benefit of achieving a higher resolution compared to Hi-C, as only ligation products involving the immunoprecipitated molecule are sequenced, on the other hand, ChIA-PET has systematic biases due to ChIP process:
- Only one type of binding factor selected
- Different antibodies
- ChIP conditions


## 2.3.5 Selected methods comparison<a name="235"></a> 
<table>
 <tbody>
    <tr>
        <th>Method</td>
        <th>Targets</td>
        <th>Resolution</td>
        <th>Notes</td>
    </tr>
    <tr>
        <td>3C <a href="http://refhub.elsevier.com/S2001-0370(17)30093-4/rf0535">[3]</a></td>
        <td>one-vs-one</td>
        <td>~1–10 kb<br></td>
        <td><ul><li>Sequence of bait locus must be known</li><li>Easy data analysis</li><li>Low throughput</li></ul></td>
    </tr>
    <tr>
    <td>4C <a href="http://refhub.elsevier.com/S2001-0370(17)30093-4/rf0545">[4]</a></td>
    <td>one-vs-all</td>
    <td>~2 kb</td>
    <td><ul><li>Sequence of bait locus must be known</li><li>Detects novel contacts</li><li>Long-range contacts</li></ul></td>
    </tr>
    <tr>
    <td>5C <a href="http://refhub.elsevier.com/S2001-0370(17)30093-4/rf0550">[5]</a></td>
    <td>many-vs-many</td>
    <td>~1 kb</td>
    <td><ul><li>High dynamic range</li><li>Complete contact map of a locus</li><li>3C with ligation-mediated amplification (LMA) of a ‘carbon copy’ library of oligos designed across restriction fragment junctions of interest
3C</li></ul></td>
    </tr>
    <tr>
    <td>Hi-C <a href="http://refhub.elsevier.com/S2001-0370(17)30093-4/rf0300">[6]</a></td>
    <td>all-vs-all</td>
    <td>0.1–1 Mb</td>
    <td><ul><li>Genome-wide nucleosome core positioning</li><li>Relative low resolution</li><li>High cost</li></ul></td>
    </tr>
    <tr>
    <td>ChIA-PET <a href="http://refhub.elsevier.com/S0168-9525(15)00063-3/sbref1405">[7]</a></td>
    <td>Interaction of whole genome mediated by protein</td>
    <td>Depends on read depth and the size of the genome region bound by the protein of interest</td>
    <td><ul><li>Lower noise with ChIP</li><li>Biased method since selected protein</li></ul></td>
    </tr>
 </tbody>
</table>

















# References
[1] https://ghr.nlm.nih.gov/primer/precisionmedicine/definition
[2] https://ghr.nlm.nih.gov/primer/precisionmedicine/precisionvspersonalized
[3] https://www.mdpi.com/1999-4923/8/1/8/htm#B1-pharmaceutics-08-00008
[4] http://nopr.niscair.res.in/handle/123456789/24037
