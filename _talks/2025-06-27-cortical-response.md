---
title: "Cortical response to local perturbations validates spatial, but not temporal, neural field theory predictions"
collection: talks
type: "Poster"
# permalink: /talks/2025-06-27-cortical-response
venue: "OHBM 2025"
date: 27/06/2025
location: "Brisbane, Queensland, Australia"
excerpt: "<img src='/images/OHBM_2025_Brisbane.jpg'><br/><br/>"

---


[Download poster here](http://LachlanHamilton.github.io/images/OHBM_2025_Brisbane.jpg)
<img src='/images/OHBM_2025_Brisbane.jpg'><br/><br/>

Introduction:

The mechanisms that govern the propagation of neural signals through the cortex are poorly understood. Recent findings [2] suggest that cortical geometry and wave equations derived from neural field theory (NFT) can describe task and resting state brain networks more accurately and with fewer parameters than network-based approaches. The role of cortical geometry is summarized by eigenmodes, the set of spatial patterns predicted to underlie activity. However, it is unclear if eigenmodes have predictive power beyond being a parsimonious basis for decomposing neuroimaging data. Moreover, it remains debated if the temporal principles of NFT can explain macroscopic signal propagation. To test these hypotheses, we assessed whole-brain spatiotemporal responses following distinct local perturbations of neural activity.
Methods:
The current work used NFT to describe the impact of focal non-invasive brain stimulation on functional neuroimaging (EEG) data; exploring the cortical propagation for signals initialised directly on the cortex. Single-pulse Transcranial Magnetic Stimulation (TMS) was delivered to frontal, parietal, and occipital brain regions during the acquisition of 64 channel surface EEG [3] (Fig.1B).
From the cortical response of hundreds of pulses (n=2314 occipital, 2396 parietal,1578 frontal) delivered across 6 subjects, we constructed an average space-and-time resolved source-reconstructed response on the cortical surface (64k vertices).  Next, we performed a space-time decomposition using orthogonal matching pursuit (OMP), which iteratively fit the best matching space-time predictions (eigenmodes [2] and damped waves [1]) from NFT with the empirical data and quantifies the amount of signal explained (Fig.1A). Further analysis used eigenmode decomposition and focused on each eigenmode’s temporal response. These empirical responses were compared to NFT simulations of a 4-parameter model based on geometric propagation [1] and simplified thalamic contributions.
Results:
Eigenmode decomposition of the TMS signal yielded a high accuracy for all sites (time-averaged spatial correlation r>0.9 with 500 modes, p<0.05 for the spatial maps at each time). OMP provided a constrained decomposition, allowing only damped waves to describe each eigenmode's temporal response. The OMP decomposition was less accurate than unconstrained eigenmode decomposition (time-averaged spatial correlation r = 0.29,0.27,0.15, for occipital, parietal, frontal signals, respectively with 1000 atoms, p<0.05 each spatial fit), suggesting that simplified cortical NFT principles may only partially explain spatiotemporal propagation. 
Results showed that the closer the TMS pulse aligns to an eigenmode's zero-amplitude regions (the nodal line), the less this mode will respond (Fig.2A). Furthermore, the most responsive modes following TMS carried the most energy across time (Fig.2B, Spearman rank-correlation for the first 50 modes r = 0.67 occipital, 0.52 parietal, 0.49 frontal, p<0.05). However, we observed that the temporal response of each eigenmode deviated from the damped-wave behaviour predicted by NFT models (Fig.2C and D).
Conclusion:
Our findings highlight a key role of eigenmode shape in determining the whole-cortex fate of local changes in neural activity. However, in this simplified form, wave-like mechanisms appear insufficient to explain the response of each mode and whole-cortex signal propagation. Future work is needed to assess if new models and mechanisms can explain the observed temporal dynamics (e.g. alternative spatial propagation mechanisms, and cortico-thalamic temporal contributions) and support the current conclusions. By revealing the role of eigenmodes in mediating the whole-brain response of neurostimulation, our work provides new avenues to improve the specificity and efficacy of existing neuromodulation therapies.
References: 

[1]	J. C. Pang et al., “Geometric constraints on human brain function,” Nature, pp. 1–9, May 2023, doi: 10.1038/s41586-023-06098-1.
[2]	M. Rosanova, A. Casali, V. Bellina, F. Resta, M. Mariotti, and M. Massimini, “Natural Frequencies of Human Corticothalamic Circuits,” J. Neurosci., vol. 29, no. 24, pp. 7679–7685, Jun. 2009, doi: 10.1523/JNEUROSCI.0445-09.2009.
[3]	N. C. Gabay, T. Babaie-Janvier, and P. A. Robinson, “Dynamics of cortical activity eigenmodes including standing, traveling, and rotating waves,” Phys. Rev. E, vol. 98, no. 4, p. 042413, Oct. 2018, doi: 10.1103/PhysRevE.98.042413.