This repository supports data associated with our studies of a developmental lineage-based gene co-expression network for mouse pancreatic beta-cells. 

Please cite:
> Anna B Osipovich, Karrie D Dudek, Emily Greenfest-Allen, Jean-Philippe Cartailler, Elisabetta Manduchi, Leah Potter Case, Eunyoung Choi, Austin G Chapman, Hannah Worchel Clayton, Guogiang Gu, Christian J Stoeckert, and Mark A Magnuson. A developmental lineage-based gene co-expression network for mouse pancreatic β-cells reveals a role for Zfp800 in pancreas development. Development 2021 .doi: 10.1242/dev.196964
> 
> https://dev.biologists.org/content/early/2021/02/26/dev.196964
> 
> To gain a deeper understanding of pancreatic β-cell development, we used iterativeWGCNA to calculate a gene co-expression network (GCN) from eleven temporally- and genetically-defined murine cell populations. The GCN, which contained 91 distinct modules, was then used to gain three new biological insights. First, we found that the clustered protocadherin genes are differentially-expressed during pancreas development. Pcdhγ is preferentially expressed in pancreatic endoderm, Pcdhβ in nascent islets, and Pcdhα in mature β-cells. Second, after extracting sub-networks of transcriptional regulators for each developmental stage we identified 81 zinc finger protein (ZFP) genes that are preferentially expressed during endocrine specification and β-cell maturation. Third, we used the GCN to select three ZFPs for further analysis by CRISPR mutagenesis of mice. Zfp800 null mice exhibited early post-natal lethality, and at E18.5 their pancreata exhibited a reduced number of pancreatic endocrine cells, alterations in exocrine cell morphology, and marked changes in expression of genes involved in protein translation, hormone secretion, and developmental pathways in the pancreas. Together, our results suggest that developmentally-oriented GCNs have utility for gaining new insights into gene regulation during organogenesis.

## Explore

Please [explore the data here](https://markmagnuson.github.io/BetaCell-GCN/).

## Summary

Expression profiles were determined at the following timepoints and genenotypes:

![Timepoints of developmental study](genebrowser/data/pancreas-developmental-network-Osipovich.png)

## Meta-module network
Each node in the meta-network represents a module of highly co-expressed genes.  The meta-network is defined by correlations between module eigengenes and partitions modules into three distinct strongly connected module groups.

![Meta-modules](images/metanetwork.png)




