## ImMSigDb - Immune Models and Signatures Database 

- ImMSigDb  is a NoSQL document-oriented database created using Cloud Firestore ( see [Intro to Firestore](https://firebase.google.com/docs/firestore) or [wiki of this git repo](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki) for more information such as --SettingupSDKandFirebaseForProjects).

- ImMSigDb means to provide immunology context rich feature sets from heterogeneous resources to be used for enrichment analysis and/or multivariate data association analysis to facilitate immunology commmunity. 

Note: Keeping it open for not just genes as features - any features types (for future modeling e.g. metabolomics etc) in context with immunology association. 

**Under devlopment:**
ImMSigDbR - for R package providing the Feature Sets enrichment analysis (under active development; **ETA: Sep 2024**)


## What data?

Based on the heterogeneous collections and sources the data is fetched from, two out of the following ways are used to organize this data in firestore:

1- Pathways: features, interaction, pathway, network (These can be used as feature Sets as well but since ther were intially having interactions we would model the interactions too)

2- Feature Sets from experiments/ markers type data resources which do not hold interaction type of information basically: source (project/experiment etc), features, features sets (based on experimental ontology- like the panels used , gating mechanisms used etc in case of cell data) 

### Current data in ImMSigDb
- Full firestore database can be downloaded in json format from ImMSigDb_v0.0.0. 

## How the data is updated?
- Currently, the data is using a biannual update model. Last update was made on June ? 2024.  


***
# Table of Contents
* [Home](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki)

* [Adding data to FireStore](https://github.com/amnahsiddiqa/ImmFeSdb/wiki/Adding-data-to-Firestore)

* [Current release] ImMSigDb_v0.0.0

* [Using In Enrichment Analysis: Example]



* This is a work in progress

