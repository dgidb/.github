## Welcome to the Drug-Gene Interaction Database project

### Introduction

In the era of clinical sequencing and personalized medicine, investigators are frequently presented with lists of mutated or otherwise altered genes implicated in 
disease for a specific patient or cohort. Numerous resources exist to help form hypotheses about how such genomic events might be targeted therapeutically. However, 
utilizing these resources typically involves tedious manual review of literature, clinical trial records, and knowledgebases. Few currently exist which collect and 
curate these resources and provide a simple interface for searching lists of genes against the existing compendia of known or potential drug-gene interactions. The 
drug-gene interaction database (DGIdb) attempts to address this challenge. Using a combination of expert curation and text-mining, drug-gene interactions have been 
mined from DrugBank, PharmGKB, ChEMBL, Drug Target Commons, and others. Genes have also been categorized as potentially druggable according to membership in selected 
pathways, molecular functions and gene families from the Gene Ontology, the Human Protein Atlas, IDG, "druggable genome" lists from Hopkins and Groom (2002) and Russ 
and Lampel (2005), and others. Drug and gene grouping is provided by the VICC Gene and Therapy Normalizer services. DGIdb contains over 10,000 genes and 20,000 drugs 
involved in nearly 70,000 drug-gene interactions or belonging to one of 43 potentially druggable gene categories. Users can enter a list of genes to retrieve all known 
or potentially druggable genes in that list. Results can be filtered by source, interaction type, or gene category. DGIdb is built on Ruby on Rails and PostgreSQL with 
a flexible relational database schema to accommodate metadata from various sources.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
