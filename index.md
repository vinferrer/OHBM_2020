---
layout: landing
title: Characteristic Traits of Mild cognitive impairment in Parkinson's disease
description: Vicente Ferrer-Gallardo, Manuel Delgado, Irene Navalpotro, Stefano Moia, Manuel Carreiras, Pedro M. Paz Alonso, María Cruz Rodriguez-Oroz, César Caballero-Gaudes
publication: OHBM 2020
year: 2020
button:
  link: https://github.com/vinferrer/OHBM_2020/raw/master/OHBM_2020_poster.pdf
  name: Poster
owner:
  name: Vicente Ferrer
social:
  twitter: https://twitter.com/VFerrerGallardo
  github: https://github.com/vinferrer
  email: vferrer@bcbl.eu
---


# [Introduction](#Introduction)

Mild cognitive impairment (MCI), frequent in Parkinson Disease (PD), is a well-known risk factor for dementia. Nevertheless, MCI key network changes are still mostly unknown. Functional connectivity resting state networks (RSNs), such as the default mode, dorsal attention, executive control and sensorimotor networks, have been reported to correlated with cognitive deficits in PD. This study investigates how whole-brain functional networks are affected by MCI in PD using a Connectome ICA (connICA) analysis with resting state functional MRI (RS-fMRI).

# [Dataset](#Dataset)
87 participants (26 PDCN and 33 PD-MCI and 28 HC) were recruited and scanned in Siemens Trio 3T MR scanner with 32 channel head coils. A battery of neuropsychological tests was taken by each individual to diagnose PD-MCI according to MDS task force guidelines (level II) [^1]. PD patients were under anti-parkinsonian medication during the study
![](./images/dataset.jpg){:width="100%"}
**Figure 1: Dataset structure. Motion based censoring was done after Functional preprocessing eliminating the subjects with more than 20% of censored volumes. After motion based censoring, 21 HC, 21 PDCN and, 23 PD-MCI subjects remained**

# [Acqusition and Preprocesing](#Preprocesing)
For each subject, we collected: T1-weighted and T2-weighted anatomical scans (1 mm isotropic voxels), and 10 minutes eyes-open resting state BOLD fMRI images with standard (monoband, TR=2s, 33 slices) and multiband (TR=800ms, 45 slices) GE-EPI images (3 mm isotropic voxels, matrix size= 64x64, TE= 28ms). 
![](./images/Anatomical_preprocessing.jpg){:width="100%"}
**Figure 2: Anatomical Preprocessing**
Brain parcellation was performed using FreeSurfer based on the Destrieux atlas (72 cortical and 8 subcortical regions for hemisphere)[^2]. Structural images were registered to the functional images.
fMRI preprocessing included despiking, slice timing, EPI distortion correction, head realignment and nuisance regression. After motion based censoring, 21 HC, 21 PDCN and, 23 PD-MCI subjects remained. FC matrices were computed using Schaefer atlas plus subcortical areas of Destrieux atlas
![](./images/Functional_preprocessing.jpg){:width="100%"}
**Figure 2: Functional preprocessing Preprocessing**
# [Results](#Results)

---
[^1]: Litvan I, Goldman JG, Tröster AI, Schmand BA, Weintraub D, Petersen RC, et al. Diagnostic criteria for mild cognitive impairment in Parkinson’s disease: Movement Disorder Society Task Force guidelines. Mov Disord 2012; 27: 349–56.


