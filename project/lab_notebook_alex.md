# Alex' lab notebook

# week 1 (10.5. - 17.5.)

## GitHub and GitKraken:

### - created github repository "LASERPIN"
### - updated README.md file
### - updated project.md
### - updated data*.md
### - updated labnotebook
### - created a timeline on GitKraken

## Search for raw EEG data:

### - it has turned out to be quite difficult to find suitable raw EEG data of schizophrenia patients for our purposes
### - at the moment, three possible sources are:
#### - https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/repod.0107441
#### - http://brain.bio.msu.ru/eeg_schizophrenia.htm
#### - https://melbourne.figshare.com/articles/dataset/Data_Monash_Study/12752399?file=24131678
### - probably we found the paper to the last of these three data sets:
#### - https://research.monash.edu/en/publications/aberrant-connectivity-in-auditory-precision-encoding-in-schizophr

# week 2 (17.5. - 24.5.)

## Docker:

### - try to fix Docker and to get familiar with on my system

## Literature and data:

### - try to find well suiting articles about our topic and to contact the responsible researchers to get raw data from them

# week 3 (24.5. - 31.5.)

## Jupyter Notebook:

### - got familiar with Jupyter Notebook
### - checked how to open standard .ipynb files in my JN
### - checked how to create a new file with Python Code

# week 4 (31.5. - 7.6.)

## New messages regarding data:

### - the first of June I received a message from Elzbieta Olejarczyk from Poland
### - she said that their data is in .edf format which might be useful for us
### - this data set includes eeg signals from 14 patients with paranoid schizophrenia and 14 healthy controls
### - this is the article which probably belongs to this eeg measurement:
#### - https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0188629

## Practice with Jupyter Notebook and Python:

### - programmed a calculator with Python code in my jupyter notebook in collaboration with Anna
### - uploaded it here in our repo under the file name Calc.ipynb

# week 5 (7.6. - 14.6.)

## MNE and reading EEG data:

### - got familiar with the program MNE as integrated tool for EEG data (.edf files) in Jupyter Notebook
### - did first programing steps with MNE to have a first closer sight on our 28 .edf files (14 with Schizophrenia, 14 healthy ones/ s01-s14; h01-h14)
### - data includes a resting measurement for every person with closed eyes (about 15 mins) with 19 eeg channels/ data points

# week 6 (14.6. - 21.6.)

## Filtering data/ single Preprocessing (with José):

### - created a bandpass filter with lowest frequency at 0.5 hz and highest frequency at 45.0 hz
### - created eog and ecg epochs to define interfering components in the eeg signal
### - tried to create first steps for the independent component analysis (ICA)

# week 7 (21.6. - 28.6.)

## ICA/ complete Preprocessing (with José):

### - loaded data into our jupyter notebook and created a for-loop to preprocess all data
### - decided to take Fp1 and Fp2 of s01 as examples for eye artifacts and to use it for filtering these out for every other person
### - applied ICA (fastica) for all persons but it didn't work out well for each of them:
#### - was faulty for s02, s06, s07, s11, s12, s14, h06, h07, h10, h11 and h14

# week 8 (28.6. - 5.7.)

## refining ICA (with José):

### - decided to refine the first ICA of the data and to create an own template for filtering out eye artifacts
### - worked out better with this refined version of the ica, data looked even better; some rare single channels with conspicuously bad signal had to be taken out manually
### - persons with still a problematic components which couldn't filtered out:
#### - s06, s09, h04, h11, h12

# week 9 (5.7. - 12.7.)

## creating epochs and bands (with José):

### - setting up fixed epochs length (2 seconds)
### - averageing the activation for each person and each frequency
### - averageing the activation for each group and each frequency

# week 10 (12.7. - 19.7.)

## frequency-band analysis (with José):

### - detecting and defining critical electrodes for the comparison between healthy ones and schizophrenics
### - observing strongest differences in delta and gamma frequency bands
### - independent t-test for some critical electrodes in these bands
#### - they seem to have a tendence to significance 

# week 11 (19.7. - 26.7.)

## analysing results of frequency-band analysis

### - compare our results with those we found in the literature:
#### - Bates et al. (2009)
#### - Mulert et al. (2010)
#### - Light et al. (2006)
#### - Moran et al. (2011)
#### - Lisman (2012)
#### - Basar-Eroglu et al. (2007)
#### - Kirihara et al. (2012)
#### - Hanslamyr et al. (2013)
#### - Uhlhaas & Singer (2010)

### - which of our prior hypotheses can be confirmed and which ones can be rejected (?)
### - which results do we want to present and how (?)

# week 12 (26.7. - 2.8.)

## first poster draft

### - structuring our results
### - what exactly is our theoretical background and where could our results be placed in there (?)
### - what should we put on our poster (?)

# week 13 (2.8. - 9.8.)

## finalysing poster, osf preregistration and Github page/ public website of REST_OF_BASH via Github

# week 14 (9.8. - 11.8.)

## the finishing touches and preparing poster presentation

# 12.08.: POSTER SESSION! / SYMPOSIUM AND SCIENTIFIC TALK
