# Genomic surveillance of SARS-CoV-2 in Ontario, Canada reveals biases in mutational patterns between successive epochs

## Description
Datasets, analysis code, and analysis output used to generate the results for the manuscript. 

## File Structure
<pre>
├── Analysis_Notebook                                         
│   └── SARS-CoV-2_Analysis.ipynb.zip                         // Jupyter notebook of custom Python code used to generate the results in Figure 2-6 and Supplementary Figure 1-3.
├── Auspice
│   └── ncov_global.json.zip                                  // Output of the Augur informatics pipeline used as input into the Auspice visualization tool to generate the results in Figure 7.
├── Mutation Dataset                                                 
│   └── All Mutations
│   └── └── All Mutations.zip                                 // All SBS mutations observed in sequences sampled from Epoch 1, 2, 3, and 4.
│   └── Epoch-specific Mutations
│   └── └── Epoch-specific Mutations.zip                      // Epoch-specific SBS mutations first observed in sequences sampled from Epoch 1, 2, 3, and 4.
├── Sequence FASTA
│   └── MN996528_1.fasta                                      // WIV04 SARS-CoV-2 reference genome.
│   └── ontario_sequences.fasta.zip                           // SARS-CoV-2 genomes sampled from January 1, 2020 to December 31, 2021 inclusive retrieved from the GISAID database on January 1, 2022.
├── Sequence Metadata
│   └── ontario_metadata.tsv.zip                              // Metadata associated with SARS-CoV-2 genomes in ontario_sequences.fasta.zip.
</pre>

## Placeholder Citation
[Chen, D., Randhawa, G.S., Soltysiak, M.P.M., de Souza, C.P.E., Kari, L., Singh, S.M., Hill, K.A. (2022). Genomic surveillance of SARS-CoV-2 in Ontario, Canada reveals biases in mutational patterns between successive epochs.]

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
