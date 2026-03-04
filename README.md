# Ensembl GraphQL Workshop

This repository contains a small proof-of-concept notebook demonstrating how to query the **Ensembl GraphQL API** using Python.

The goal of the `ensembl-graphql-notebook-poc.ipynb` notebook is to show how a workshop could progressively teach participants to retrieve genomic data using GraphQL and export the results for downstream analysis.

---

## Workshop Modules
1. **Basic Biological Concepts**
   - Genes and what they represent in the genome
   - Transcripts and alternative splicing
   - Species and genome assemblies
Goal: This section provides a short conceptual overview so participants without a genomics background can interpret the biological entities they will query.

2. **Introduction to Ensembl**
   - What is Ensembl
   - How Ensembl organises biological data
   - Key entities in Ensembl (gene, transcripts, variants)
   - Why GraphQL was built

3. **GraphQL Basics**
   - Types and fields
   - Query structure
   - Nested queries

4. **Schema Exploration**
   - Navigating the GraphQL schema
   - Using the GraphQL interface

5. **Query Building**
   - Retrieving genes from symbols and IDs
   - Gene → transcript relationships
   - Retrieving genomic coordinates
   - Structured queries

6. **Exporting Data**
   - Parsing JSON responses
   - Converting nested data into tables
   - Exporting results to CSV / TSV.

7. **Debugging Queries**
   - Interpreting GraphQL error messages
   - Fixing broken queries

8. **AI-Assisted Querying**
   - Prompt templates for AI assistants

## Running the Notebook

1.Clone the repository:

```bash
git clone https://github.com/omabekee/ensembl-graphql-workshop.git
```

2.Open the notebook:
`ensembl-graphql-notebook-poc.ipynb`

Run using:
- Jupyter Notebook
- Google Colab

### Note:
This proof-of-concept focuses on basic querying and exporting genomic data.
Additional modules will be added in the full workshop.