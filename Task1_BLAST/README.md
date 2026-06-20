# Task 1: BLAST Analysis

This folder contains screenshots and files related to BLAST sequence analysis.

Tool Used: NCBI BLAST

Objective:
To identify homologous sequences and analyze sequence similarity.

BLASTP results table with:

Query Coverage = 100%
Percent Identity = 100% (top hits)
E-value = 1e-73 (very significant)
Max Score = 226
Homologous sequences from Homo sapiens, Gorilla gorilla gorilla, Pan troglodytes, Pongo abelii, etc.
| Homologous Sequence   | Organism                | Query Coverage | Percent Identity | E-value | Max Score |
| --------------------- | ----------------------- | -------------- | ---------------- | ------- | --------- |
| Insulin isoform UB    | Homo sapiens            | 100%           | 100.00%          | 1e-73   | 226       |
| Insulin isoform X1    | Gorilla gorilla gorilla | 100%           | 100.00%          | 1e-73   | 226       |
| Insulin preproprotein | Homo sapiens            | 100%           | 100.00%          | 4e-73   | 223       |
| Insulin isoform X2    | Pongo abelii            | 100%           | 99.09%           | 2e-72   | 222       |
| Insulin preproprotein | Pan troglodytes         | 100%           | 98.18%           | 3e-72   | 221       |
Interpretation

The BLAST search identified several insulin homologs from primates and other mammals. The top matches showed 100% query coverage and 100% sequence identity, indicating that the insulin protein sequence is highly conserved among closely related species. The extremely low E-values (1e-73) suggest that these matches are statistically highly significant and not due to chance.

The results demonstrate the evolutionary conservation of insulin, highlighting its essential biological role in glucose metabolism. Closely related primates such as gorillas, chimpanzees, and orangutans possess insulin sequences that are nearly identical to those of humans.

Conclusion

BLAST analysis successfully identified homologous insulin protein sequences across multiple species. The high percentage identity, complete query coverage, and very low E-values confirm that insulin is a highly conserved protein. These findings support the evolutionary and functional importance of insulin in mammals.
