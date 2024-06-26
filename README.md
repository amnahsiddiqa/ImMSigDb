## ImMSigDb - Immune Models and Signatures Database

**ImMSigDb** is a NoSQL document-oriented database created using Google Cloud Firestore. For more information, see the [Intro to Firestore](https://firebase.google.com/docs/firestore) or the [wiki of this GitHub repository](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki).

**Objective:** ImMSigDb aims to provide immunology context-rich molecular feature sets from diverse resources. These sets can be used for enrichment analysis and multivariate data association analysis, facilitating the immunology research community.

**Note:** The database is designed to be flexible and open to various feature types beyond genes, such as metabolomics, microbiome, for future modeling in the context of immunology.

**Under Development**

**ImMSigDbR:** An R package for feature set enrichment analysis is under active development, with an estimated release date of September 2024. The goal is to offer a single resource for easy and insightful visualizations and analyses using these (and/or others) features sets with minimal effort.

**Age related PBMC Immune Signatures** [Under dev](https://github.com/amnahsiddiqa/ImMSigDb/wiki/Age-related-PBMC-Immune-Signatures)


## Data organization

Based on the heterogeneous collections and sources from which the data is fetched, two primary methods are used to organize the data in Firestore:

1. **Pathways/Networks:**

   **Components:** Features, interactions (Since, initially these include interaction data, so we will model the interactions comprehensively as well e.g. pathways models)
2. **Features Sets:**
   
   **Components:** Features (Derived from experiments or marker-type data resources that do not contain interaction information)

   **Organization:** Organization of components include a standardized data structure from both types of data sources which shall use a minimum annotation and would be updated using nextflow pipeline biannually.  

### Current Data in ImMSigDb

* The full Firestore database can be downloaded in JSON format from ImMSigDb_v0.0.0.
* For datasets served, see full list at [Datasets served](https://github.com/amnahsiddiqa/ImMSigDb/wiki)

## Data Updates

The database follows a biannual update model. The last update was made in June 3rd 2024 and json dumps can be downloaded from [here](https://github.com/amnahsiddiqa/ImMSigDb/tree/master/V0.0.0) untill the dashboard is made avaialible in Sep 2024.

---

# Table of Contents

* [Home](https://github.com/amnahsiddiqa/GCPFirebase_ImmuneData/wiki)
* [Adding data to ImMSigDb](https://github.com/amnahsiddiqa/ImMSigDb/wiki/Workflow-for-automated-updates)
* [Current release, ImMSigDb_v0.0.0](https://github.com/amnahsiddiqa/ImMSigDb/tree/master/V0.0.0)
* [Applications: Example] (This is a work in progress)
  

Suggestions and contributions are welcome!!
