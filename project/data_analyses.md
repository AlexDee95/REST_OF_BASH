# Data analyses

- the data we will analyse was downloaded from https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/repod.0107441
- we want to use MNE-Python for the analysis
- we want to look at the data of all subjects to identify 'bad channels' and artifacts in the signals

## Overview

- first, we want to do some preprocessing with the eeg data, means filtering, bad channel handling (interpolation or not (?)) and artifact correction
- afterwards, we want to do some statistical analyses with e. g. panda (python based)
- goal could be to find some significant differences in eeg signals between schizophrenia patients and healthy controls

## Outcomes

A general overview about the analysis steps. For a closer look, please look at our codes.

- Preprocessing
  - imported modules: 
    - numpy
    - mne
    - os
  - set directory to data folder to load the .edf files
  - check up the raw data
  - creating a template for excluding eye artifacts
  - build up ICA (seven components, save these files as .fif files)

- Frequency-Band Analysis
  - import mne and numpy module
  - load average for each frequency activation for every person and define minimum/ maximum power frame
  - load all filtered and preprocessed eeg/ .fif files for every person
  - define the files referring to one of the two groups (schizophrenic and healthy persons)
  - create epochs
  - averaging the activity to do some statistics
  - plot topomaps for all frequencies for the two groups
- statistics
  - import seaborn, pandas and matplotlib
  - detect which electrodes might be of critical interest in comparison between healthies and schizophrenics for each frequency activation
  - define critical electrodes for each frequency acitvation
  - load and show swarm and box plots for average activation for healthies and schizophrenics
  - import scipy
  - do independent t-test for the two variables to find out if there is a significant difference
