---
title: "Chapter 3 Preclinical Studies to Enable First in Human Trials"
date: 2021-03-08T14:58:42+08:00
draft: false 
tags: [ "读书","专业" ]
categories: [ "技术" ]
---

Preclinical genomic data

\- https://depmap.org/portal/

\- https://www.sanger.ac.uk/ 

\- https://cansarblack.icr.ac.uk/



### Key steps in pre-clinical drug discovery before FiH

- Target selection

- Target validation based on

​     - Biological assessment

​     - Technical assessment

- Strategy for obtaining hit matter

- Establishment of a screening cascade

- Defining appropriate pharmaceutical properties

​      - Drug candidate selection

- Establishing a Target Product Profile



#### Target selection

- derived from published data that implicate

​    - particular mutation

​    - RNA species 

​    - protein as a driver of cancer

- always from clinical observations(bedside to bench)

- derived from high throughput functional genome screens using

​    - Si/ShRNA or 

​    - CRISPR/cas9 screens

- define targets whose loss of function causes cancer cell death 



#### Target validation



Biological assessment

- 50−80% publications fail replication

​    - lack of robustness in experimental design

​    - based on univariate statistical analysis to justify target selection from clinical data

​    \- correlation not equal to causality

​    - identified genetic mutations may not represent a gain or loss of function

- prospective studies should be utilised



Target validation

- often assessed by overexpression studies or knockdown of the target by Si/ShRNA or CRISPR/Cas 9 technologies

- Over expression studies are often confounded by the supraphysiological levels of gene expression from an exogenous viral promoter, require careful titration

- knockdown studies, off-target effects and inability to detect acute consequence of target knockdown 

​    \- use at least three siRNA or guide RNA sequences at low nM concentrations

​    \- make sure off-target effects are controlled for

​    \- achieve a knockdown of 80%

​    \- rescue any phenotype with SiRNA/gDNA resistant mutants

- use of antibiotic selection processes to select for cell clones where the target has been knocked out for genomic target validation

​    \-  up to 2 weeks

​    \-  protein degradation-based technologies (dTAG system) can evaluate acute loss

- Chemical probes can used for target validation

  \- molecule modulators of target function should ideally be potent and selective for a protein target

  \- use of chemical probes in different cell contexts can reveal new biology

  \- resources: [Chemical Probes Portal](https://www.chemicalprobes.org/) and  [Probe Miner](https://probeminer.icr.ac.uk/)

- understand the target distribution in normal tissue, its homology to other proteins, enable an understanding of the potential therapeutic window and potential side effects



Technical assessment

- establish the ability to drug a specific target protein

  \- directly via its active catalytic site or

  \- at a druggable cavity at a more distant site

- Druggability: presence of protein structures within a target that enable interaction with chemical compounds

- pharmaceutical drug-like properties:  Lipinski’s Rule of 5 

  \- molecular weight of ≤500 Da

  \- Log P ≤5

  \- H-bond acceptors ≤10

  \- H donors ≤5

- additional approaches 

  \- precedence-based assessment

  \- knowledge of endogenous ligands for the target

  \- algorithms that predict druggable pockets based on structures found in the protein databases 

  \- druggability based on machine learning approaches



#### Establishing a Screening Cascade

##### Hit generation strategy

- phenotypic screens

  \- focus on disease models and biological readouts

  \- not require knowledge of the target or pathways 

  \- dependent on a predefined biological (in cell models) or physiological (in in vivo models) response

  \- suit for degrading target proteins rather than modulating their function 

- Combinatorial approach

  \- large chemical libraries WITH

  \- high throughput target based screening

- For kinases and receptors, bio-chemical approaches have been used 

- For nuclear receptors, ion channels and membrane transcription factor cell-based assays are preferable



##### Screening methodologies and assays for the cascade

stablish a robust test cascade

\- high throughput screening reactions in sessile 2D droplet micro-arrays 

\- Cell-based assays can also be used as phenotypic screens, based on function 

\- cells grown in 3D respond differently to treatment compared with cells in 2D cultures

  \- spheroids generates models  

  \- mass spectrometry and nuclear magnetic resonance (NMR)



#### Choice of chemistry approach 



#### Generation of Lead compounds

\- establish IC50 or GI50 from cellular/biophysical assay

\- understand relationship between compound potency, target engagement, measured target modulation and the resulting phenotypic effect



#### Finding the target engagement-biomarker-the earlier the better

- enzymes with a known endogenous substrate, evaluation of target modulation

- Mitotic targets are especially challenging 

  \-  proliferation biomarker (P-HH3) and engineered cell lines can be used for in vivo but target is overexpressed

- novel biology may not identified the biomarker of target engagement

  \- Tool compounds together with SiRNA or CRISPR may discover novel biomarkers

  \- obtained from gene expression profiling, proteomics, protein arrays, or metabolomics or a combination of these methods



#### Secondary pharmacology profiling

\- refer to ICH S7A, evaluate highlight potential off-target effects

\- in vitro: hERG channel, CEREP screen 





#### Further in vitro testing for patient selection

required when

\- original therapeutic hypothesis fails validation in preclinical models

\- additional sensitive patient population are sought ahead of clinical studies

\- provide information on potential mechanism of resistance or inform potential drug combinations

Organoids derived from patient material are more representative of patient tumors than spheroids



#### Optimising the PK and predicting the active dose in man

Understanding the target requirement from in vitro tests is a guide to optimising PK to demonstrate target engagement and efficacy



![Figure3.1](https://i.loli.net/2021/03/08/HiM91TKd7EyulGg.png)



- compounds metabolised by aldehyde oxidase or carboxyles-terases are more challenging

- Transport-mediated clearance is less accurate and always suffer drug resistance and efflux from many tumors and cancer stem cells

- humanised mice models help to quantify metabolism

- Identification of metabolites

   \- check of the potential activity of metabolites

   \- confirmation that no metabolites formed are toxic

   \- qualitative and quantitative evaluation of the metabolites formed across species favours selection of the toxicology species where metabolites are closest to those in man

- more than 10% of parent compound in blood need to be measured in FiH

- DDI: [EMA](https://www.ema.europa.eu/en/documents/scientific-guide-line/guideline-investigation-drug-interactions/) and [FDA](https://www.fda.gov/drugs/drug-interactions-labeling/drug-development-and-drug-interactions)

- PBPK and allometric scaling or variants  can be used to predict various PK parameters 



#### Selecting the optimal in-vivo model

- Xenograft models in immunocompromised mice (SCID, NCR nude, NOD) 

  \- frequently utilised for PKPD and efficacy studies of non-immune- oncology targets

  \- lack of translation to clinical responses

- patient derived xenografts (PDX)

  \- lower throughput

  \- better predict than simple xenografts derived from cell lines

- genetically engineered mouse models

  \- validate the effect on the target and the resulting in vivo effect

  \- useful models in immuno-oncology

- syngeneic mice provided the immune pathway targeted is similar in mice and humans

  \- suit for immuno-oncology target

  \- mimic the human immune response in mice

  \- still devoid of cytokines and growth factors

  \- successed in CAR-T therapy, NK therapy and PD-1 antibodies

- PD assay developed originally in human cells may not be directly applicable in human tumor xenografts, PDX or GEMM models

  \- interactions of secondary antibody

  \- number of variants of a protein and their structure and regulation can vary across specie



### Drug Candidate Selection

Selection criteria for a drug development candidate to enable IND studies

![Table 3.2](https://i.loli.net/2021/03/08/gX2i8WGStrluzjZ.png)



### Translating the candidate for IND and FiH

Once the candidate has been selected, a number of parallel yet interdependent activities need to be carried out.



**Toxicology evaluation**

\- Help to define the starting dose in man and formulation

\- In one rodent and one non-rodent species

  \- species selected relates to the target biology in the species

  \- knowledge from previous preclinical studies (ICH guidelines S7A and B, FDA Guidance for industry M3R2)

​    \- antiproliferative activity often cause gut toxicity and induce myelosuppression

​    \- Dogs are extremely prone to emesis, so mini-pigs can be a good alternative to dogs

\- For immune-oncology and biologic agents, humanised mice models are often used alongside cynomolgus monkeys or minipigs

\- For small molecules, it is important to consider the mechanism of clearance and the metabolites produced in the species tested, as well as impurities

\- Duration of the study should cover all potential clinical applications

  \- ICH guidelines S7A and B, [FDA Guidance for industry M3R2](https://www.fda.gov/animal-veterinary/guidance-regulations/guidance-industry)

  \- In oncology, a 28-day evaluation is usually sufficient for IND application

 

**Definition of dose and scheduling for FIH**

starting dose

For cytotoxic agents: 

\- NOAEL dose multiplied by safety margin

\- combined with in vivo PK/PD and efficacy models to 

  \- define systemic exposure 

  \- correlate with the degree of target engagement and desired efficacy 

  \- use allometric scaling to extrapolate doses from animal to human based on BSA(ICH guidelines S7A, S7B, FDA Guidelines for industry M3R2)



**Formulation**

\- For IV, solution stability needed

\- For PO, rate of dissolution, crystalline form, excipients are important

  \- low solubility of the salt form has resulted in variable bioavailability 



**Clinically validated biomarker assays**

assays to measure biomarkers of target engagement is essential

\- In solid tumors, the biomarker selected to support preclinical studies is ideally validated for human tumors

  \- limited by the availability of tumor biopsies

  \- paired biopsies: before treatment and at peak effect

  \- liquid biopsies: circulating free DNA

  \- surrogate tissues(blood cells, hair follicles, skin biopsies, plasma) inform to generate concentration-time-target engagement relationship

\- In haematological malignancies

  \- circulating tumors are available

  \- often limited by the myelosuppressive effect of therapeutics

\- biomarker modulations techniques

  \- immunoassays in a variety of formats and platforms

  \- gene expression profiling

  \- flow cytometry

  \- proteomics and metabolomics 

\- target established drivers of cancer in patient subpopulations, excluding patients with certain molecular features



#### Modelling and Simulations



**Cases**

- ALK: growth inhibition is observed when EC50 to EC60 of ALK is reached

- PI3K: a minimum of 30% inhibition of AKT phosphorylation is required for antitumor activity in breast cancer

- gefitinib and sorafenib: assuming that free steady state concentrations in human and mouse were identical, predicted correct clinical doses 

- resistance model: predict the active doses for sensitive and resistant patients

- immune oncology: tumor uptake for cytokine-based immunotherapy model available

- Toxicities can be modelled and to optimise scheduling



#### Development of a Target Product Profile (TPP)

highly useful for IND & as an important dynamic document, at the pre-IND stage it should include

\- potential indications and usage in defined patient populations

\- dosage and administration

\- formulation (with dosage forms and strengths)

\- contraindications

\- clinical pharmacology

\- non-clinical toxicology

\- planned clinical studies

\- storage, handling and drug stability

\- patient information and the consent form for the first in human study 