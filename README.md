## ImmFeSdb-Immune Features Sets/Signatures Database 

Note: Keeping it open for not just genes as features - any features types (for future modeling e.g. metabolomics etc) in context with immunology association. 

(Another brainstormed sugesstion: IGSdb-Immune Gene Signatures Database - No! because Find out that there are 02 R packages names )


ImmFeSdb  is a NoSQL document-oriented database created using Cloud Firestore [Intro to Firestore](https://firebase.google.com/docs/firestore) or [wiki of this git repo](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki) for more information on CloudThingies like --SettingupSDKandFirebaseForProjects

This is an ensemble of Features (genes initially) sets which were contextually curated from immunology data in individual efforts and are acquired from either in-house data or from public domain. ImmFeSdb means to provide immunology context rich feature sets from heterogeneous resources to be used for enrichment analysis and/or multivariate data association analysis to facilitate immunology commmunity. 


## Types of Features set Models in DB

Based on the sources we fetch data from, we could use two out of teh given options to organize data in firestore:

1- Pathways: features, interaction, pathway, network

2- Feature Sets from experiments/ markers type data resources which do not hold interaction type of information basically: source (project/experiment etc), features, features sets (based on experimental ontology- like the panels used , gating mechanisms used etc in case of cell data) 

3- Hybrid: to discuss BTM models 

### Components: 
- List of pathways/Modules:  A pathway is defined by the interactions (physical, co-expression, casual etc)  in the pathway/modules. 
- List of Feature Sets: Feature set is  defined by an annotated features list classified based on some ontology used in experiments e.g. cell type classification based on DEGs etc specifying cell markers.
- List of Interactions:  An interaction is minimally defined by source and target nodes/features.  Ontology , Synonym ids,  tissue, species could be additional infromation.
- List of genes with HUGO gene symbols.


***
# Table of Contents
* [Home](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki)

* [Adding data to FireStore](https://github.com/amnahsiddiqa/ImmFeSdb/wiki/Adding-data-to-Firestore)

* [Feature Sets]

* [Using In Enrichment Analysis: Example]




