## ImmFeSdb-Immune Features Sets/Signatures Database 

Note: Keeping it open for not just genes as features - any features types (for future modeling e.g. metabolomics etc) in context with immunology association. 

(Another brainstormed sugesstion: IGSdb-Immune Gene Signatures Database - No! because Find out that there are 02 R packages names )


ImmFeSdb  is a NoSQL document-oriented database created using Cloud Firestore [Intro to Firestore](https://firebase.google.com/docs/firestore) or [wiki of this git repo](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki) for more information on CloudThingies like --SettingupSDKandFirebaseForProjects

This is an ensemble of Features (genes initially) sets which were contextually curated from immunology data in individual efforts and are acquired from either in-house data or from public domain. ImmFeSdb means to provide immunology context rich feature sets from heterogeneous resources to be used for enrichment analysis and/or multivariate data association analysis conveneiently in one standardized format in one place to facilitate immunology commmunity.


## Types of Features set Models in DB

Based on the sources we fetch data from, we could use two out of teh given options to organize data in firestore:

1- Pathways: features, interaction, pathway, network

2- Feature Sets from experiments/ markers type data resources which do not hold interaction type of information basically: source (project/experiment etc), features, features sets (based on experimental ontology- like the panels used , gating mechanisms used etc in case of cell data) 

3- Hybrid: to discuss BTM models 

***
# Table of Contents
* [Home](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki)

* [1.Installing and Setting Up Credentials with SDK GCP](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki/1.Installing-and-Setting-Up-Credentials-with-SDK-GCP)

* [2.Setting up a Conda venv for GCP SDK firebase client libraries in Isolation](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki/2.Setting-up-a-Conda-venv-for-GCP-SDK-firebase-client-libraries-in-Isolation)

* [3.Firestore](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki/3.Firestore)

* [4.Adding, Updating, Querying data in FireStore](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki/4.Adding,-Updating,-Querying-data-in-FireStore)

* [Random Thingies](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki/Random-Thingies)

