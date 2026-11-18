[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.on004973-blue)](https://doi.org/10.82901/nemar.on004973)

The  fNIRS dataset focus on the prefrontal cortex activity in fourteen types of highly automated driving scenarios, which considers age, sex and driving experience factors, and contains the data of an 8-channel fNIRS device and driving scenarios. A total of 20 participants completed this driving simulator experiment，and each participant need to finish 12 tasks. Their ages range from 21 to 46 years old, with 5 females and 15 males. 

 Our objective is to provides the data support for finding the difference of prefrontal cortex activity between low-risk and high-risk episodes by quantifying the risk of driving scenarios. This research may provide a solution to prevent potential hazard and improve SOTIF based on brain-computer interface technology and fNIRS, in the future. 

## Notes

- Here a total of 240 tasks which are need to be completed by  20 participants，and the data about 20 tasks is removed because the data are not recorded correctly.
- We update the results of subjective evaluations about dangerous degree of VTD segment, and they are shown in the file "participants.tsv".

## How to cite?
doi:10.18112/openneuro.ds004973.v1.0.0

## Contributed notes (version 1.0.2)

- The fNIRS dataset focuses on prefrontal cortex activity in fourteen types of highly automated driving scenarios (8-channel fNIRS device), 20 participants, 12 tasks each.
- 25 of the 222 published SNIRF files are truncated: on opening, HDF5 reports a truncated file, because the end-of-file address in the file header is larger than the published file size. File names as published: sub-1_task-11, sub-1_task-8, sub-10_task-1, sub-10_task-2, sub-11_task-3, sub-11_task-6, sub-12_task-1, sub-13_task-6, sub-16_task-10, sub-18_task-1, sub-19_task-1, sub-19_task-2, sub-19_task-8, sub-2_task-2, sub-2_task-7, sub-3_task-2, sub-5_task-1, sub-5_task-4, sub-6_task-11, sub-6_task-4, sub-6_task-6, sub-7_task-10, sub-7_task-3, sub-9_task-2, sub-9_task-9.
- The source README notes that the authors removed the data of 20 of 240 tasks because they were not recorded correctly.
- The meaning of the trial_type codes (1.0 to 14.0) and of the task numbers is not documented in this release; the events.json files hold generic descriptions only.
