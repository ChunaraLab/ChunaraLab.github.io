---
layout: default
title: Data Science and Machine Learning in Public Health
description: 
nav_order: 1
---

Course info
This 5-session (2 hours each session), 1 credit course, delivered over zoom, will introduce and encourage thinking around new datasets and analytic  methods in public health. The data science pipeline, across data gathering, processing, analysis and communication will be covered. Content will include summaries of current and best practices from the literature, discussion of research papers and methods in terms of their appropriateness in public health, and approaches to address methodological challenges. Content will relate to both infectious diseases such as COVID-19 and noncommunicable diseases. Students are encouraged to bring their own dataset or use publicly available ones to develop their own data science project, and time will be allotted for discussing project challenges.

<!--
This repository contains information about the tutorial [Machine Learning in Population and Public Health: challenges and opportunites](https://www.chilconference.org/tutorial_b.html) at [ACM Conference on Health, Information and Learning, 2020](https://www.chilconference.org/index.html). A full summary of the tutorial is provided in [this document](./docs/ACM_chil_tutorial_summary.pdf). Citation: <br/>
**Mhasawade, Vishwali, Yuan Zhao, and Rumi Chunara. “Machine Learning in Population and Public Health.” ArXiv:2008.07278 [Cs], July 21, 2020. [http://arxiv.org/abs/2008.07278](http://arxiv.org/abs/2008.07278).**

[Tutorial video found here.](https://slideslive.com/38931964/machine-learning-in-population-and-public-health-challenges-and-opportunities)

-->
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


## Pre-requisites
"This course will be a good introduction for anyone interested in learning how data science can be used in public health and biomedicine, and what kinds of skills and problems are involved. Previous exposure and experience in epidemiology, biostatistics research and/or practice will be assumed. Students should also have some experience working with data and a working knowledge of the principles of linear regression and statistics. Course examples will be in R so a working knowledge will also be required, or students should go through an online introduction prior to enrolling."

## Goals, Overview and Slides
The goals of this tutorial are to:<br>
1) Familiarize the audience with research in public and population health<br>
2) Identify open areas relevant to machine learning and health equity<br>
3) Activate the machine learning community on challenges in public/population health<br>

## Modules
{: .d-block }

In order to demonstrate the use of machine learning across aspects of health, comprehensively, we developed a taxonomy of Machine Learning in <i>health</i> tasks (broadly) and list example studies below.

<details>
<summary>1. What is data science?</summary>
<ul>
<li>
<details>
<summary>Disease incidence at population level</summary>
<ul> 
<li> <a href="https://www.nature.com/articles/nature12060?page=32">
Bhatt, Samir, et al. "The global distribution and burden of dengue." Nature 496.7446 (2013): 504-507. 
</a>  
</li>
</ul>
</details>
</li>

<li>
<details>
<summary>Disease detection including behaviors and markers</summary>
<ul>
<li> <a href="https://jamanetwork.com/journals/jama/article-abstract/2588763">
Gulshan, Varun, et al. "Development and validation of a deep learning algorithm for detection of diabetic retinopathy in retinal fundus photographs." Jama 316.22 (2016): 2402-2410.
</a>
</li>

<li> <a href="https://arxiv.org/abs/1807.10215">
Lu, Jen-Tang, et al. "Deepspine: Automated lumbar vertebral segmentation, disc-level designation, and spinal stenosis grading using deep learning." arXiv preprint arXiv:1807.10215 (2018). </a> </li> 




<li>
<details>
<summary>Individuals/populations to minimize healthcare costs </summary>
<ul><li> <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1448604/pdf/0942139.pdf">
Rose, Sherri, Savannah L. Bergquist, and Timothy J. Layton. "Computational health economics for identification of unprofitable health care enrollees." Biostatistics 18.4 (2017): 682-694.
</a></li>

<li> 
<a href="https://www.healthaffairs.org/doi/abs/10.1377/hlthaff.2016.0012">
McGuire, Thomas G. "Achieving mental health care parity might require changes in payments and competition." Health Affairs 35.6 (2016): 1029-1035.
</a>
</li>


<li> 
<a href="https://europepmc.org/article/med/23513755">
Williams, J. "A new model for care population management." Healthcare Financial Management: Journal of the Healthcare Financial Management Association 67.3 (2013): 68-76.</a>
</li>




<summary>Data in Public Health and Healthcare</summary>
<ul>
<li>
<details>
<summary>Individual-level interventions</summary>
<ul><li> <a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/17358">
Rahmattalabi, Aida, et al. "Influence Maximization for Social Network Based Substance Abuse Prevention." Thirty-Second AAAI Conference on Artificial Intelligence. 2018.
</a></li></ul></details>
</li>

<details>
<summary>Prediction</summary>
<ul>
<li>

<details>
<summary>Risk scores (clincal algorithms) </summary>
<ul><li> <a href="https://www.nejm.org/doi/full/10.1056/NEJMms2004740">
Vyas, Darshali A., Leo G. Eisenstein, and David S. Jones. "Hidden in Plain Sight—Reconsidering the Use of Race Correction in Clinical Algorithms." (2020).
</a></li></ul></details>
</li>




<li>
<details>
<summary>Chances of mortality </summary>
<ul><li> <a href="https://journalofethics.ama-assn.org/article/can-ai-help-reduce-disparities-general-medical-and-mental-health-care/2019-02">
Chen, Irene Y., Peter Szolovits, and Marzyeh Ghassemi. "Can AI help reduce disparities in general medical and mental health care?." AMA journal of ethics 21.2 (2019): 167-179. 
</a></li>

<li> <a href="https://journalofethics.ama-assn.org/article/can-ai-help-reduce-disparities-general-medical-and-mental-health-care/2019-02">
Einav, Liran, et al. "Predictive modeling of US health care spending in late life." Science 360.6396 (2018): 1462-1465.
</a></li>

<li> <a href="https://www.nature.com/articles/s41746-018-0029-1/">
Rajkomar, Alvin, et al. "Scalable and accurate deep learning with electronic health records." NPJ Digital Medicine 1.1 (2018): 18.
</a></li>


<li> <a href="http://proceedings.mlr.press/v68/forte17a.html">
Forte, José Castela, et al. "Predicting long-term mortality with first week post-operative data after Coronary Artery Bypass Grafting using Machine Learning models." Machine Learning for Healthcare Conference. 2017.
</a></li>
</ul></details>
</li>

<li>
<details>
<summary>Treatment adherence </summary>
<ul><li> <a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/1475-6773.12310">
Franklin, Jessica M., et al. "Observing versus predicting: initial patterns of filling predict long‐term adherence more accurately than high‐dimensional modeling techniques." Health services research 51.1 (2016): 220-239.
</a></li>

<li> <a href="https://ieeexplore.ieee.org/abstract/document/7889104/">
Karanasiou, Georgia Spiridon, et al. "Predicting adherence of patients with HF through machine learning techniques." Healthcare technology letters 3.3 (2016): 165-170.
</a></li>
</ul></details>
</li>

<li>
<details>
<summary>Readmission to hospital </summary>
<ul><li> <a href="https://dl.acm.org/doi/abs/10.1145/3287560.3287593">
Galiatsatos, Panagis, et al. "The Association Between Neighborhood Socioeconomic Disadvantage and Readmissions for Patients Hospitalized With Sepsis." Critical Care Medicine 48.6 (2020): 808-814. 
</a></li>

<li> <a href="https://journalofethics.ama-assn.org/article/can-ai-help-reduce-disparities-general-medical-and-mental-health-care/2019-02">
Chen, Irene Y., Peter Szolovits, and Marzyeh Ghassemi. "Can AI help reduce disparities in general medical and mental health care?." AMA journal of ethics 21.2 (2019): 167-179. 
</a></li>
</ul></details></li>
</ul>
</details>
 


<details>
<summary>Allocation</summary>
<ul>
<li>
<details>
<summary>Resources to individuals  </summary>
<ul><li> <a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/ajt.15115">
Snyder, Jon J., et al. "Organ distribution without geographic boundaries: a possible framework for organ allocation." American Journal of Transplantation 18.11 (2018): 2635-2640.
</a></li>

<li> <a href="https://www.sciencedirect.com/science/article/pii/S001236921551283X">
Davis, Steven Q., and Edward R. Garrity Jr. "Organ allocation in lung transplant." Chest 132.5 (2007): 1646-1651.
</a></li>

<li> <a href="https://cjasn.asnjournals.org/content/12/5/848.short">
Asch, William S., and Margaret J. Bia. "New organ allocation system for combined liver-kidney transplants and the availability of kidneys for transplant to patients with stage 4–5 CKD." Clinical Journal of the American Society of Nephrology 12.5 (2017): 848-852.
</a></li>

<li> <a href="https://www.aaai.org/ojs/index.php/AAAI/article/view/3838">
Kube, Amanda, Sanmay Das, and Patrick J. Fowler. "Allocating interventions based on predicted outcomes: A case study on homelessness services." Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 33. 2019.
</a></li>
</ul></details>
 </li>

<li>
<details>
<summary>Resources to populations  </summary>
<ul><li> <a href="https://journals.sagepub.com/doi/abs/10.1111/ijs.12571">
Lord, Aaron S., et al. "Discharge educational strategies for reduction of vascular events (DESERVE): design and methods." International journal of stroke 10.SA100 (2015): 151-154.
</a></li>

<li> <a href="https://teamcore.seas.harvard.edu/files/teamcore/files/2018_14_teamcore_bridging_gap_theory.pdf">
Yadav, Amulya, et al. "Bridging the Gap Between Theory and Practice in Influence Maximization: Raising Awareness about HIV among Homeless Youth." IJCAI. 2018.
</a></li>

<li> <a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/17358">
Rahmattalabi, Aida, et al. "Influence Maximization for Social Network Based Substance Abuse Prevention." Thirty-Second AAAI Conference on Artificial Intelligence. 2018.
</a></li>
</ul></details>
</li>


<li>
<details>
<summary>Resources within hospital  </summary>
<ul><li> <a href="https://journals.lww.com/cinjournal/Fulltext/2018/05000/A_Hospital_Bed_Allocation_Hybrid_Model_Based_on.7.aspx">
da Silveira Grübler, Murillo, et al. "A hospital bed allocation hybrid model based on situation awareness." CIN: Computers, Informatics, Nursing 36.5 (2018): 249-255.
</a></li>

<li> <a href="https://journals.sagepub.com/doi/abs/10.1177/0969733018759831">
Scott, P. Anne, et al. "Resource allocation and rationing in nursing care: A discussion paper." Nursing Ethics 26.5 (2019): 1528-1539.
</a></li>

<li> <a href="https://link.springer.com/content/pdf/10.1007/s10729-015-9335-1.pdf">
Feng, Yen-Yi, I-Chin Wu, and Tzu-Li Chen. "Stochastic resource allocation in emergency departments with a multi-objective simulation optimization algorithm." Health Care Management Science 20.1 (2017): 55-75.
</a></li>
</ul></details>
</li>

<li>
<details>
<summary>Care management at individual and population level </summary>
<ul><li> <a href="https://www.sciencedirect.com/science/article/pii/S073567571730468">
Chacko, Jerel, et al. "Effect of an emergency department opioid prescription policy on prescribing patterns." The American Journal of Emergency Medicine 35.9 (2017): 1327-1329.
</a></li>

<li> <a href="https://www.sciencedirect.com/science/article/pii/S073646791630988X1">
Osborn, Scott R., et al. "Changes in provider prescribing patterns after implementation of an emergency department prescription opioid policy." The Journal of emergency medicine 52.4 (2017): 538-546.
</a></li>

<li> <a href="https://www.ncbi.nlm.nih.gov/pubmed/8221823">
[Kucukarslan, S., et al. "Points to consider about prescription drug prices: an overview of federal policy and pricing studies." Clinical therapeutics 15.4 (1993): 726.]
</a></li>
</ul></details></li>
</ul>
 </details>

## About Us
</tbody>
</table> 

