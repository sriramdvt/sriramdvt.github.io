---
layout: post
title: Defended my MS thesis at IIIT Hyderabad.
date: 2024-07-11 12:00:00+0530
inline: false
related_posts: false
---

[Blog on IIIT's website.](https://blogs.iiit.ac.in/monthly_news/devata-sriram/)

Title: Rethinking Structure Prediction in Computational Chemistry: The Role of Machine Learning in Replacing Database Searches
Abstract:

Well designed search algorithms can be used to search databases in computational chemistry to identify unknown compounds and their structures based on their observable attributes that are stored in the databases. Apart from an inherent problem of the lack of diversity within individual databases, algorithms that depend on database searches are inaccessible to researchers who are unable to access or have their own copy of these enormous databases. This thesis focuses on removing the database dependency for algorithms that depend on database searches for structure prediction in two areas within computational chemistry- molecular structure elucidation from molecular spectra, and tertiary structure prediction of RNA (Ribonucleic acid) molecules from their sequence.

Molecular spectroscopy studies the interaction of molecules with electromagnetic radiation, and interpreting the resultant spectra is invaluable for deducing the molecular structures. However, predicting the molecular structure from spectroscopic data is a strenuous task that requires highly specific domain knowledge. DeepSPInN is a deep reinforcement learning method that predicts the molecular structure when given Infrared and 13C Nuclear magnetic resonance spectra by formulating the molecular structure prediction problem as a Markov decision process (MDP) and employs Monte-Carlo tree search to explore and choose the actions in the formulated MDP. On the QM9 dataset, DeepSPInN is able to predict the correct molecular structure for 91.5% of the input spectra in an average time of 77 seconds for molecules with less than 10 heavy atoms. This study is the first of its kind that uses only infrared and 13C nuclear magnetic resonance spectra for molecular structure prediction without referring to any pre-existing spectral databases or molecular fragment knowledge bases, and is a leap forward in automated molecular spectral analysis.

RNA molecules play a significant role in many biological pathways and have diverse functional roles, which is a result of their structural flexibility to fold into diverse conformations. This structural flexibility makes it challenging to obtain the structures of RNAs experimentally. Deep learning can be used to predict the secondary structures of RNA and other properties such as the backbone torsion angles, to be used as restraints for the computational optimization of the tertiary structures of RNA. TorRNA is a transformer encoder-decoder model that takes an input RNA sequence and predicts the (pseudo)torsion angles of each nucleotide with a pre-trained RNA-FM model as the encoder. TorRNA is able to achieve a performance boost of 2%−16% over the previous (pseudo)torsion angle prediction method for RNAs. We also demonstrate that TorRNA can be used as a tool for model quality assessment of candidate RNA structures.
