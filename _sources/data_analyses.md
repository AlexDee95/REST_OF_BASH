# Data analyses

- the data we will analyse was downloaded from https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/repod.0107441
- we want to use MNE-Python for the analysis
- we want to look at the data of all subjects to identify 'bad channels' and artifacts in the signals

## Overview

- first, we want to do some preprocessing with the eeg data, means filtering, bad channel handling (interpolation or not (?)) and artifact correction
- afterwards, we want to do some statistical analyses with e. g. panda (python based)
- goal could be to find some significant differences in eeg signals between schizophrenia patients and healthy controls

## Outcomes

- Preprocessing
- ICA
- Frequency-Band Analysis
