# Dataset Description
#### Author: nikhil153 (tdveale modified)
#### Date: 30 May 2021 (15 Aug 2022 modified)

This directory consists subset of data from AOMIC: the Amsterdam Open MRI Collection. 

Modified by tdveale to only have sub-001 and group data for IDEAS software development carpentry workshop.

See this [website](https://nilab-uva.github.io/AOMIC.github.io/) and [OpenNeuro](https://openneuro.org/datasets/ds002790/versions/2.0.0) for complete details. 

## Data types
- Participant info  (./participants.tsv)
- Structural MR scans for sub-0001 (./sub-0001/anat/*)
- FreeSurfer "mri" output for sub-0001 (./derivatives/freesurfer/sub-*/mri/*)
- FreeSurfer average thickness surface for entire cohort (N=226) (./derivatives/freesurfer/fsaverage5/surf)
- FreeSurfer thickness stats for DKT and Destrieux parcellations for entire cohort (N=226) (./:wqderivatives/fs_stats)  

