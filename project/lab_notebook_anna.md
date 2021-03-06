
# Annas lab notebook

# week 1 (03.05.-09.05.)
literature search:
 - openknowledgemaps.org
 - terms: EEG AND schizophrenia; EEG AND schizophrenia AND language; EEG AND schizophrenia AND N400
 - naming the project 

# week 2 (10.05. -16.05.)
* created github repository "LASERPIN"
  * updated README.md file
  * updated project.md
  * updated labnotebook
  * updated data*.md
  * created a timeline on GitKraken
* search for raw EEG data
  * https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/repod.0107441
  * http://brain.bio.msu.ru/eeg_schizophrenia.htm
  * https://melbourne.figshare.com/articles/dataset/Data_Monash_Study/12752399?file=24131678
* writing mails to different people to ask for their EEG data
  * Melissa Larsen and Ilvana Dzafic for the raw data of the Monash Study 
  * Shupin Tan (https://www.frontiersin.org/articles/10.3389/fninf.2019.00004/full)

# week 3 (17.05. -23.05.)
* writing again an email to Ilvana -> Ilvana told me, that she is in contact with the IT to solve the downloading problem
* writing an e-mail to Daniel Hermens -> „BMRI Electroencephalography (EEG) clinical research data“ from the University of Sydney -> still waiting for an answer
* trying out commands on docker and conda

# week 4 (24.05. -30.05.)
* trying out commands on jupyter but actually it only works on binder 

# week 5 (31.05. -06.06.)
* talk with Alex about the answer from Elzbieta Olejarczyk
* have a look on the paper and the eeg data from the study: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0188629

* now my jupyter notebook works with my PC and my command system

* programmed a calculator with Python code in Alex' jupyter notebook in cooperation with Alex
* after that I programmed my own calculator

# week 6 (07.06. -13.06.)
* downloaded the EEG data files from https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/repod.0107441
* updated data*.md
* read the related publication to the EEG data files: Olejarczyk E, Jernajczyk W (2017) Graph-based analysis of brain connectivity in schizophrenia. PLoS ONE 12(11): e0188629. https://doi.org/10.1371/journal.pone.0188629
* meeting with José to talk about the first steps of preprocessing
* creating a jupyter notebook for preprocessing -> first steps on preprocessing to get a first look on the data (28 .edf files)
* get to know MNE as a tool for EEG data

# week 7 (14.06. -20.06.)
* updating github repository
* creating eog and ecg epochs to evaluate interfering components in the eeg signal 
* first steps for the ICA (independent component analysis)

# week 8 (21.06. -27.06.)
* meeting with José to solve problems with the preprocessing
* completion of the preprocessing for one subject
* creation of a loop on the jupyter notebook to preprocess all subjects
  * take Fp1 and Fp2 as reference for eye artifacts
  * ICA did not work for every subject: s02, s06, s07, s11, s12, h06, h07, h10, h11, h14 

# week 9 (28.06. -04.07.)
* update "_toc.yml" on github 
* meeting with José 
* completion of preprocessing by creating an own template for filtering eye artifacts in the eeg signal
* control the ICA for all subjects
  * it worked better than our first ICA
  * some artifacts could not be filtered: s06, s09, h04, h11
  * in one subject it could not be detected a component: s12

# week 10 (05.07. -11.07.)
* we decide to make a frequency band analysis for our eeg data because of the missing of stimulus events
* doing the epochs analysis for all subject and plotting the results 
  * adaptation of the scales for the different frequencies
* averaging the data separately for the frequencies (delta, theta, alpha, beta and gamma)
  * averaging the activation for each person 
  * averaging the activation for the two groups

# week 11 (12.07. -18.07.)
* plotting the averages for all frequencies and the two groups and making a short presentation about the results
* discuss the results with Alex 
* looking for prospective statistic analysis 
* literature research because of the new aim of our project:
  * frequency-band analysis
    * detecting and defining critical electrodes to compare schizophrenic patients with healthy persons
    * observing greater differences in delta and gamma oscillations
    * independent t-test for critical electrodes
* creation of "code"-folder on github


# week 12 (19.07. -25.07.)
* read some paper about the activity of the different frequencies in schizophrenia compared to healthy controls
  * Bates et al. (2009)
  * Mulert et al. (2010)
  * Light et al. (2006)
  * Moran et al. (2011)
  * Lisman (2012)
  * Basar-Eroglu et al. (2007)
  * Kirihara et al. (2012)
  * Hanslamyr et al. (2013)
  * Uhlhaas & Singer (2010)
* comparing our results to these in the literature
* which hypotheses we can confirm and which ones we must reject

# week 13 (26.07. -01.08.)
* on holiday

# week 14 (01.08. -08.08.)
* creation and designing the poster for the symposium
* osf preregistration

# week 15 (09.08. -12.08.)
* updating GitHub documents
* creating website of our GitHub reposatory
* building up a presentation and our poster presentation
* symposium

