# HARP
## NGS Data Processing and Analysis

This Python pipeline processes and analyzes NGS data, providing an overview of the analysis performed for the following paper:


[**High-Throughput Activity Reprogramming of Proteases (HARP)**](https://pubs.acs.org/doi/10.1021/acschembio.5c00230)
*Samantha G. Martinusen, Ethan W. Slaton, Seyednima Ajayebi, Marian A. Pulgar, Cassidy F. Simas, Sage E. Nelson, Amit Dutta, Julia T. Besu, Steven Bruner, and Carl A. Denard*
ACS Chemical Biology 2025 20 (10), 2381-2392
DOI: 10.1021/acschembio.5c00230 


## Usage:
1. Clone or download the repository, then open the provided Jupyter Notebook to follow the step-by-step instructions.
2. Change the path for your input FASTQ files.
3. Run each step you need for your analysis to have a clean dataset.
4. Run the enrichment section on the cleaned data.

This code is developed in [The Denard lab](https://www.thedenardlab.com/).


## Requirements:
python 3.12.3
biopython 1.83
numpy 1.26.4
pandas 2.1.1
scipy 1.11.3
seaborn 0.12.2

For ESM-2 embedding you need to install transformers in your virtual environment(suggested way):

```
conda install conda-forge::transformers
```
You also need to install UMAP: Uniform Manifold Approximation and Projection for Dimension Reduction.
```
 conda install conda-forge::umap-learn
```

This work uses ESM [^1], UMAP [^2], and BioPython [^3], please make sure to cite them. 

[^1]: https://www.pnas.org/doi/full/10.1073/pnas.2016239118
[^2]: https://arxiv.org/abs/1802.03426
[^3]: https://academic.oup.com/bioinformatics/article/25/11/1422/330687
