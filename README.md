Clinical practice guidelines for patients using bisphosphonates and the need for dental interventions: a systematic review


Educating healthcare professionals through clinical cases based on systematic reviews of Clinical Practice Guidelines
Nature of my research interests: My research interests are primarily focused on summarizing the best available evidence for treating patients with drug addiction, with the aim of educating healthcare professionals. This interest was triggered by the direct impact drug addiction has on voice, memory and language, all of which are part of my practice as a speech pathologist and were part of my PhD dissertation. My long-term goals are to continue focusing on this field to pursue an academic career primarily focused in this research field.

Proposed work:  While Clinical Practice Guidelines were designed to communicate the best available evidence to healthcare professionals, their effectiveness in translating this evidence to practice has been limited. Although the reasons are multifactorial, two reasons have been consistent across the literature: (1) Different Clinical Practice Guidelines are often conflicting and of varying quality, ultimately confusing more than guiding clinicians, and (2) The format behind Clinical Practice Guidelines is not conducive to direct application in either professional education. My proposal aims at providing potential solutions to both problems. Specifically, my aims are:

Aim 1 - Conduct a systematic review of Clinical Practice Guidelines targeting crack and cocaine: Standard systematic searching methods as proposed by the PRISMA (Preferred Reporting Items for Systematic Reviews and Meta-Analyses) standard will be used in the search and data aggregation, the quality of each Clinical Practice Guideline being evaluated through the recommendations of a recent systematic review.

Aim 2 - Develop clinical cases and corresponding infographics in an online course for healthcare professionals: Based on the results of the systematic review resulting from Aim 1, I will compile a series of "facts" from the Clinical Practice Guidelines, graded according to the strength of their evidence. These facts will then be used to populate a series of clinical case models using a standard Automatic Item Generation framework as previously described in the psychometric literature. Finally, these facts will be transformed into infographics summarizing the information from the systematic review
Aim 3 - Conduct an online, parallel, randomized controlled educational trial. This trial will compare the combined use of (a) clinical cases and infographics (clinical case arm) resulting from Aim 2 vs (b) standard education using a set of original Clinical Practice Guideline documents and references. We will include a diverse group of healthcare professionals from the US and South America. Outcome variables will include knowledge, student satisfaction with the training and transfer of knowledge to clinical practice.

Methods: All of my methods will be conducted using a strict Reproducible Research methodology, implying that all data and scripts will be released under either an Apache Software Foundation 2.0 Apache 2 open source license or a Creative Commons Attribution 4.0 International license, and placed under open repositories such as Gihub and Figshare. Specific methods are described in the following sections.

Aim 1 - Conduct a systematic review of Clinical Practice Guidelines targeting crack and cocaine
Search strategy: I will make use of standard, reproducible searching techniques using: (1) Boolean searches across databases including PubMed, Google Scholar, PsycInfo, and the international Clinical Practice Guideline repositories, (2) citation analyse of key references, (3) manual search of key journals and Web sites, (4) communication with experts and international healthcare agencies in charge of healthcare policies.

Quality evaluation: I will make use of a 2013 systematic review that has compiled recommendation on best practices for the evaluation of Clinical Practice Guidelines. Their recommendations include factors such as the ones displayed under Table 1.
Table 1 - Siering's quality dimensions (  Siering et al., 2013) 

Construct	Elements
1. Information retrieval	Health questions and outcomes, Literature search, Literature selection
2. Evaluation of evidence	Grading of evidence, Consistency between evidence and recommendations
3. Consideration of different perspectives	Norms and values, Expert knowledge, Patient perspectives
4. Formulation of recommendations	Formulation of recommendations
5. Transferability	Comparability, Costs, Barriers and facilitators
6. Presentation of guideline content	Benefits and harms, Link to evidence
7. Alternatives	Options for management, Exceptions, Patient preferences
8. Reliability	Independent Review, pilot test
9. Scope	Rationale and objective, Guideline topic, Practice setting, Patient population,  Provider population, 
10. Independence	Guideline development group, Guideline development organization and funding, Conflicts of interest
Fact extraction, aggregation and reporting: Each one of the facts across all Clinical Practice Guidelines and their respective quality evaluation will be extracted and reported through a table containing the original citations, criteria taken into consideration when assigning the quality grade and the fact itself.

Aim 2 - Develop clinical cases and corresponding infographics in an online course for healthcare professionals
Based on the fact table from Aim 1, I will develop a series of Clinical Cases following a standard Automatic Item Generation (AIG) (@gierl2012automatic) methodology:
1.	Standard clinical cases will be generated with an initial clinical case description followed by a multiple alternative format presenting therapy options based on the facts from the Clinical Practice Guidelines systematic review
2.	Sections within the clinical case will be tagged as (a) clinical facts that are part of Clinical Practice Guidelines, (b) characteristics of addicted patients, (c) characteristics of normal people, (d) common situations encountered in association with crack and cocaine addiction
3.	A database will be generated with lists of the previously mentioned components so that they can be combined to create a large number of variations of clinical cases. Interactive infographics will be created using Google Web Designer, an intuitive and easy to use software that can generate interactive infographics for the Web in HTML5 format.

Aim 3 - Conduct an online, parallel, randomized controlled educational trial
We will follow the CONSORT Statement while both designing and later reporting this trial. The trial will be registered with the clinicaltrials.gov Web site.

Inclusion criteria: 
We will include a diverse group of healthcare professionals from both South America (Brazil) and the United States. Trial material will be available in both Portuguese and English, validated qualitatively and through translation-backtranslation by bilingual researchers. 

Intervention: 
Both intervention and control groups will undergo training through the [Open edX] platform, an Open Source Learning Management System developed through Stanford University in collaboration with a group of more than 30 different organizations in the US and around the world. The control group will receive a series of Clinical Practice Guidelines, being asked to read them on a weekly basis for four weeks.The intervention group will receive a series clinical cases over a 4-week period where they have to answer multiple alternative questions about their conduct, followed by the presentation of a summary of recommendations from the systematic review in an interactive infographic format, also integrated into the Open edX platform. 

Sample size calculation: 
Given the absence of preliminary efficacy data, we calculated our sample size based on an assumption of a two-sample t-test for an index representing the worst case scenario for each of the three outcomes, with an effect size of 55%, a significance level and statistical power set at the traditional levels of 0.05 and 80%, respectively. Under these assumptions the estimated required sample size is of 52.9 per group, which we have rounded to 53, ultimately leading to a total sample size of 106 participants in total.

Randomization and blinding: 
Randomization schedule will be generated through the Open edX platform, making use of a recent plugin that integrates the Facebook Planout framework for the design of randomized controlled trials. The randomization schedule is generated using the Python language, following a blocked design (n=10), stratified by the specialty of the healthcare professional. All allocation is concealed, blinding being present at the participant, researcher and analyst levels, the only professional being aware of the randomization being the programmer from my institution in charge of implementing the algorithm.

Outcome variables - 
Three main variables will be measured: 
1-Knowledge: Knowledge will be measured through a group of questions (items) under two main domains, namely, cocaine and crack. Given that there are no standardized scales to measure knowledge within each of these domain areas, we will conduct a parallel validation using a combination of Classical Psychometric Theory and Item Response Theory, both methods having been extensively used in previous publications by one of my collaborators specialized in psychometric methods and latent variable modeling (RP). 

2-Satisfaction: In this study we will primarily measure User eXperience (UX) as participant satisfaction while participating in each of the two interventions. While the literature on the measurement of satisfaction within online education is vast, (see @banks2007reduction, @dibiase2005scaling and @ summers2005comparison for a few examples) we have elected to use the scale developed by Kuo et cols since it is not only comprehensive but has also been shown to be psychometrically valid. The Sampson scale covers seven satisfaction sub-constructs, namely satisfaction with learner-learner interaction, learner-instructor interaction, learner-content interaction and overall satisfaction. Cronbach's alpha reliability was found to be above 0.88 for all subscales, the Kuo scale also having been validated against student self-efficacy. 

3-Impact on clinical practice: The last evaluated construct will be the impact on clinical practice. Given that, to our knowledge, no previously validated scale has been devised to measure the impact of online learning on clinical practice, we have also devised a concomitant validation strategy. Impact on clinical practice will be measured through a group of questions (items) under one single domain (unidimensional scale). The item (question) will focus on "How much has the knowledge you gained in this course has positively or negatively influenced your clinical practice in {{setting}}, where 0 means no influence at all and 10 means an extremely influence," where {{setting}} represents different settings such as ambulatory, emergency, floor and discussions with colleagues. A five-point Likert alternative pattern will then cover the spectrum of positive or negative influence. This group of items will be exposed to the participants in our trial.

Expected results
At the end of this study I will have completed a systematic review of Clinical Practice Guidelines focusing on crack and cocaine, hopefully reducing the confusion among healthcare professional working in this field. I will also have developed and documented a reproducible method to create scalable clinical cases and corresponding infographics to be included in educational material. And last, I will have evaluated the efficacy of the combination of clinical cases and infographics in educating healthcare professionals regarding these Clinical Practice Guidelines. Three peer-reviewed manuscripts will be generated.
At a personal level, I expect that this project will help me launch my career as an academic researcher, hopefully contributing to the field and helping improving the care level to addicted patients.

Relevant publications (minhas)
Mark J Gierl, Thomas M. Haladyna. Automatic Item Generation: Theory and Practice. Routledge, New York, 2012. 
Siering U, Eikermann M, Hausner E, Hoffmann-Eßer W, Neugebauer EA. Appraisal tools for clinical practice guidelines: a systematic review. PLoS One. 2013, 8(12):e82915. doi: 10.1371/journal.pone.0082915. eCollection 2013.
Kuo YC, Walker AE, Belland BR , Schroder KEE. A Predictive Study of Student Satisfaction in Online Education Programs. The international review of research in open and distance learning. 2013, 14(1). 

