1. Generate a table using metadata from GTDB and NCBI XML files (Timing < 1.5 h)
2. Host information was manually curated using the information from BioProject descriptions and original publications (Timing variable)
3. Include additional genomes associated with sponges, as identified in the literature (Timing variable)
4. Assign HMA/LMA type to each sponge based on literature sources (Timing variable)
5. Counting sponge-associated bacteria capable of metabolizing sulfoacetate and taurine (Timing variable)
6. The occasionally sponge-associated group versus the control group (Timing 8 mins)
7. Identification of Genes Encoding Tripartite ATP-Independent Periplasmic Transporters (Timing Variable)



Part 1: Sequence similarity networks

Sequence similarity networks were constructed using BiG-SCAPE v. 2.0.0-beta.8 and visualized with Cytoscape v. 3.10.3. Input: pre-existing GenBank files containing clusters corresponding to sulfoacetate utilization (sauS_sauT, sauS_sucC_sucD), used without modification.

Part 2: Phylogenetic analysis

Phylogenetic trees were reconstructed using RAxML-NG v. 1.2.2 and visualized with iTOL. Prior to tree reconstruction, sequences were processed in the following order: clustering with MMseqs2 v. 13-45111, multiple sequence alignment with MUSCLE v. 5.3, manual inspection and editing of alignments in Jalview, and trimming with ClipKIT v. 2.7.0.
