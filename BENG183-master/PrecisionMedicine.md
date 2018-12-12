# Precision Medicine 
1. [Introduction](#1)<br>
2. [Pharmacogenomics](#2)<br>
3. [Precision Medicine in Cancer](#3)<br>
    3.1 [History via Breast Cancer Treatment](#31)<br>
    3.2 [Modern Usage](#32)<br>
4. [RNA Detection and Quantification Technologies](#4)<br>
    4.1. [Northern Blot](#41)<br>
    4.2. [RT-qPCR](#42)<br>
    4.3. [Hybridization based microarrays](#43)<br>
    4.4. [RNA-seq](#44)<br>
5. [Gene Expression Assays in Medicine](#5)<br>



## Introduction<a name="1"></a>

Precision medicine is defined as the act of tailoring medical treatment such that it takes into consideration the individual characteristics of each patient's case [1]. Traditionally, medicine has been practiced with a "one fits all" approach, where the same standard tests and common drugs are used to treat the same phenotypically-appearing symptoms. This new approach of precision medicine looks beyond phenotype by gathering a genetic understanding of the individual's disease and applying it to how health care is delivered to the patient.

To gather a genetic understanding of a patient's disease, various types of data are taken into consideration. This includes the patient's genetic/health history, their response to the disease, and their lifestyle. Each of these factors are significant in understanding how the patient's disease may have developed as well as how it can currently be characterized.

> FAQ: What is the difference between "precison" medicine and "personalized" medicine? "Personalized" was used initially, but this term gave rise to the concern that it would be misinterpreted as using an approach that is unique to _each_ person. However, the idea is not that an individual receives their very own unique treatment; the idea is that targeted therapies are developed based on molecular diagnostics. "Personalized" medicine refers to the practice of handling a patient's care hollistically, while "precision" medicine refers to the science of creating evidence-based medicine [2].

## Pharmacogenomics<a name="2"></a>

The process of delivering precision medicine does not end when a targeted therapeutic drug is developed. It must continue with ensuring if the patient will respond well and effectively to it. This gives way to an integral field of precision medicine - pharmacogenomics. Pharmacogenomics is the study of how genes and genetic variations affect a patient's response to therapeutic drug treatment [3]. This involves taking a hollistic approach in drug design to minimize chances of adverse health effects because knowing a patient's genetic makeup can help with predicting the outcome of certain therapies. Pharmacogenomics allows scientists and doctors to address questions such as: will the drug optimally target the abnormality that needs fixing? Will it induce any negative side effects known to occur in the patient? Will it potentially cause further complications due to other genetic factors that must be considered for this patient?

Research has been and is currently being done to further scientists' knowledge on how genetic variations can affect the human body's response to medications. For instance, the Human Genome Project is working towards combining sequencing information gathered from many genomes with current knowledge on gene functions to enhance drug discovery by understanding why particular genotypes found in these genomes respond a certain way - and therefore identifying subpopulations that may benefit most from a certain drug [4]. Although the current use of pharmacogenomics is still quite limited due to a continued need for growing knowledge, it will further the development of tailoring drugs to treat a wide range of health problems in the future.


## Precision Medicine in Cancer<a name="3"></a>

##### History via Breast Cancer Treatment<a name="31"></a> 

The first forms of breast cancer treatment included removal of the ovaries - which would completely interrupt the hormonal feedback loop, as ovaries produce and release estrogen. However, in the 1970s, it was discovered that this kind of treatment was not necessary for patients with estrogen-receptor positive tumors. Rather these patients could benefit from anti-estrogen agents that block their tumors from receiving the growth-stimulating estrogen. By 1984, with the help of microarrays and gene expression profiling techniques, it was further discovered that some breast cancer patients (approximately 20%) could be characterized by abnormal HER-2 gene expression. Once more, efforts were made to develop targeted drug therapy, leading to the creation of Herceptin for inhibiting the function of the protein produced from this gene. In the 1990's, scientists found that 5% of breast cancer patients inherited genetic defects in genes BRCA1 and BRCA2, causing doctors to begin screening and watching for this mutation in patients. As this timeline shows, precision medicine has allowed for the creation and implementation of treatments that are more effective/beneficial to specific patients based on the characterization of their disease.  

##### Modern Usage <a name="32"></a>

###### Types of Treatment<br>
Current treatments for cancer include a combination of surgery, chemotherapy, radiation therapy, immunotherapy - each meant to be applied under specific conditions of the patient [5]. A common form of precision medicine is providing hormonal therapy based on a patient's gene abnormalities (is there a protein that can be targeted?) or tumor characteristics (does the tumor have hormone receptors that can be blocked?) As the figure below shows, there is a correlation between longer survival and the use of precision medicine.

![bargraph](https://github.com/kmercade/BENG183/blob/master/BENG183-master/unnamed.png "The Impact of Personalized Medicine on Cancer Survival in Years")<br>
**Figure 1: The Impact of Personalized Medicine in Cancer Survival in Years [6].** The bar graph is a visual representation of the impact of targeted cancer therapy on survival.<br>

###### Current Usage<br>
Since precision medicine is still a growing field, it is not used for most patients today. However, research and clinical trials continue to contribute to current knowledge such that its usage can grow as well. To find out a patient's eligibility for precision medicine, often a biopsy will be ordered to take a sample from the tumor mass which will get sent to testing to determine the tumor's chemical and genetic characteristics.

###### Economics<br>
One of the constraints hindering the growth of precision medicine usage is cost. Since it requires many years to develop specific treatments to target certain types of cancer, the treatments often end up being expensive by the time they’re available. However, if patients agree to participate in clinical trials, the cost of testing can be sponsored by the researchers.

## RNA Detection and Quantification Technologies<a name="4"></a> 

So how exactly are we able to "measure" and "classify" a person's disease type? This can be done with the help of various RNA detection and quantification methods. RNA can be used to measure levels of gene expression, and if abnormalities are found in these levels, this can be used to determine specific genes or proteins that may need to be targeted. The key point in precision medicine is that not every person of a certain disease phenotype may have the exact same genetic abnormalities. 

##### Northern Blot<a name="41"></a>
![Northern Blot](https://github.com/kmercade/BENG183/blob/master/BENG183-master/latest.jpg "Northern Blot")<br>
**Figure 2: Northern Blot [7].** Here the process of Northern Blot is displayed, from sample input to just before signal detection.<br>

One method that is used for RNA detection and quantification is the Northern Blot. First, total RNA is extracted from the tissue of interest. mRNA is isolated from total RNA, which is then run through gel electrophoresis to separate the strands by size. These strands are then transferred to a nylon membrane and immobilized. Probes that are designed to be complementary to specific RNA sequences are fluorescently labeled and added so that they may hybridize to their corresponding sequences (if present in the sample). The probe's signal can be detected and used for quantification of that sequence. 

##### RT-qPCR<a name="42"></a>
![RT-qPCR](https://github.com/kmercade/BENG183/blob/master/BENG183-master/unnamed.jpg "RT-qPCR")<br>
**Figure 3: RT-qPCR [8].** Here the process of RT-qPCR is displayed, from sample input to just before signal detection. <br>

Another method is reverse transcription quantitative polymerase chain reactioin (RT-qPCR). First, reverse transcription is conducted to synthesize cDNA from the RNA sample, which is then used as template for PCR to amplify the sequence of interest. In this case, quantitative PCR is used so that the amount of product is quantified with each step by way of fluorescent signaling detection. Several fluorescent methods may be used, but a common one is the use of Sybr Green, which binds double stranded DNA by intercalating between the bases and emits green light. The process of RT-qPCR can be repeated for various samples to compare the amounts of desired product detected. 

##### Hybridization based microarrays<a name="43"></a>
![Hybridization based microarrays](https://github.com/kmercade/BENG183/blob/master/BENG183-master/chi_003_01.gif "Hybridization based microarrays")<br>
**Figure 4: Hybridization based microarrays [9].** Here the process of hybridization based microarrays is displayed, from sample input to signal detection.<br>

There's also hybridization based microarrays. It also utilizes reverse transcription to create cDNA from RNA. The cDNA strands are then fluorescently labeled and added to a microarray containing spots with sequences of known genes. If expression of these genes are present in the sample, there will be cDNA strands that hybridize in those spots. Detection of fluorescent signaling levels in each spot is used to create a gene expression profile. 

##### RNA-seq<a name="44"></a>
![RNA-seq](https://github.com/kmercade/BENG183/blob/master/BENG183-master/te-203-4.png "RNA-seq")<br>
**Figure 5: RNA-seq [10].** Here the process of RNA-seq is displayed, from sequence preparation to just before sequencing.<br>

Finally, the more recent technology being used for RNA quantification is RNA-seq. Sample preparation involves isolation, fragmentation, and size selection of mRNA. cDNA is once again synthesized and prepared for sequencing by ligating adapters to the ends of the strands, which will hybridize to sequences on a flow cell for further amplification and sequencing of the template. Expression is quantified by counting the number of reads that map to each gene, which can then be compared between samples to identify differences in gene expression. In contrast to the previous technologies mentioned, RNA-seq is not limited to detecting only a certain set of known genes because it can account for all transcripts in the cell for each condition. In other words, this process is not dependent on sequence-specific primers or probes. 

## Gene Expression Assays in Medicine<a name="5"></a> 
![Gene expression patterns of breast carcinoma](https://github.com/kmercade/BENG183/blob/master/BENG183-master/Screen%20Shot%202018-11-26%20at%206.36.46%20PM.png "Gene expression patterns of breast carcinoma")<br>
**Figure 6: Gene expression patterns of breast carcinoma [11].** Displayed is a heatmap showcasing gene expression patterns among various breast cancer patients.<br>

With the quantifications obtained from technologies such as the ones previously discussed, gene expression assays can be done to analyze and capture gene expression patterns. Depictions can be created, such as the one shown in the figure above, to help identify patterns for classifying different subtypes of a disease. Different patterns may constitute distinct forms of the disease in terms of growth rate, potential to metastasize, and responsiveness to certain treatments. Understanding the genomic and transcriptomic diversity of diseases can ultimately help with better matching therapies for patients, which in the end is the fundamental idea of delivering precision medicine.



# References
[1] https://ghr.nlm.nih.gov/primer/precisionmedicine/definition<br>
[2] https://ghr.nlm.nih.gov/primer/precisionmedicine/precisionvspersonalized<br>
[3] https://www.mdpi.com/1999-4923/8/1/8/htm#B1-pharmaceutics-08-00008<br>
[4] http://nopr.niscair.res.in/handle/123456789/24037<br>
[5] https://www.cancer.gov/about-cancer/treatment/types/precision-medicine<br>
[6] https://www.nature.com/articles/nrclinonc.2012.160<br>
[7] http://mmg-233-2014-genetics-genomics.wikia.com/wiki/Northern_Blot<br>
[8] https://www.thermofisher.com/us/en/home/brands/thermo-scientific/molecular-biology/molecular-biology-learning-center/molecular-biology-resource-library/spotlight-articles/basic-principles-rt-qpcr.html<br>
[9] http://www.3d-gene.com/en/about/chip/chi_003.html<br>
[10] https://www.labome.com/method/RNA-seq-Using-Next-Generation-Sequencing.html<br>
[11] https://www.pnas.org/content/pnas/98/19/10869.full.pdf
