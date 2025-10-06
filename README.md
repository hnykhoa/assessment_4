# Bioinformatics Assignment 4 – Part 1 and 

##  What the project does

This project performs data analysis on two biological datasets using R.  
It focuses on gene expression and tree growth, applying data wrangling, mathematical operations, and visualization techniques. The goal is to explore biological patterns and practice reproducible coding in RStudio.



##  What files are included

- `part1.Rmd`: RMarkdown script containing all code and explanations  
- `part1.pdf`: Final knitted report in PDF format  
- `README.md`: This documentation file



##  How to run the code

1. Open `part1.Rmd` in RStudio  
2. Ensure `gene_expression.tsv` and `growth_data.csv` are in the same folder  
3. Click **Knit → Knit to PDF** to generate the report  
4. All required packages (e.g. `tidyverse`, `ggplot2`) are loaded within the script  
5. Each code chunk is commented to explain its purpose and logic


# Part 2: Comparative Genomics

This section compares coding DNA sequences between *Escherichia coli* and *Streptacidiphilus jiangxiensis* to explore sequence diversity and codon usage bias.

###  Organisms
- *Escherichia coli* 
- *Streptacidiphilus jiangxiensis* 

###  Input Files
- `ecoli_cds.fa`: Coding sequences for *E. coli*
- `streptacidiphilus_jiangxiensis_cds.fa`: Coding sequences for *S. jiangxiensis*

###  Analyses
- Sequence counts: Compare number of coding sequences between organisms
- Total coding DNA: Calculate and compare total base pairs of coding sequences
- Length distributions: Analyze CDS length patterns with statistical summaries and boxplots
- Base composition: Calculate nucleotide and amino acid frequencies with bar plots
- Codon usage: Generate codon usage tables, calculate RSCU, and quantify codon bias
- K-mer analysis: Identify over- and under-represented protein 4-mers and compare between organisms

### Tables
- Table 1: CDS counts comparison  
- Table 2: Total coding DNA length  
- Table 3: CDS length statistics  
- Table 4: Nucleotide frequencies and GC content  
- Table 5: Top 10 codons by RSCU value  
- Table 6: Top 10 over-represented 4-mers  
- Table 7: Differentially enriched 4-mers  
- Figure 8: CDS length distribution boxplot  
- Figure 9: Nucleotide frequencies comparison  
- Figure 10: Amino acid frequencies comparison  
- Figure 11: RSCU comparison (top 30 codons)  
- Figure 12: Top 20 protein 4-mers comparison

### Required R Packages
```r
install.packages("R.utils")
install.packages("seqinr")
install.packages("knitr")
install.packages("rmarkdown")
install.packages("ggplot2")
install.packages("dplyr")
install.packages("stringr")

### Who contributed
Name: Nguyen Y Khoa Huynh
Student ID : 225595361
Course: Master of biotechnology 
