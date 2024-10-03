# Pocket-Based Drug Design

## Introduction
This repository focuses on drug design using pocket-based methods that utilize the detailed structural information of protein binding sites to generate appropriate ligands. Our approach leverages advanced AI algorithms to model the interactions between ligands and proteins, which facilitates the creation of molecules optimally configured for their target sites.

## Pocket-Based Algorithms
We employ several state-of-the-art algorithms including:
- **DiffSBDD**: A diffusion model that generates novel ligands with high predicted binding affinities. [View on GitHub](https://github.com/arneschneuing/DiffSBDD.git)
- **DrugGPT**: An autoregressive model using GPT for ligand design that explores vast chemical spaces. [View on GitHub](https://github.com/LIYUESEN/druggpt.git)
- **Lingo3DMol**: Utilizes a transformer-based approach for 3D molecular structure generation. [View on GitHub](https://github.com/stonewiseAIDrugDesign/Lingo3DMol.git)
- **Pocket2Mol**: An E(3)-equivariant generative network that efficiently samples molecular structures. [View on GitHub](https://github.com/pengxingang/Pocket2Mol.git)
- **RGA**: A reinforced genetic algorithm optimizing molecular designs for enhanced binding affinity. [View on GitHub](https://github.com/futianfan/reinforced-genetic-algorithm.git)

In addition, this GitHub will be constantly updated with novel Pocket-Based methods:

- **DrugAI**: A transformer-based architecture that generates molecules conditioned on protein binding sites. [View on GitHub](https://github.com/dangjaya/drugAI.git)
- **TamGent**: A transformer-based generative model designed for structure-based drug design. [View on GitHub](https://github.com/HankerWu/TamGent.git)
- **DecompDiff**: A diffusion model that decomposes ligands into arms and scaffolds to generate optimized molecules. [View on GitHub](https://github.com/bytedance/DecompDiff.git)
- **TargetDiff**: A 3D equivariant diffusion model that generates target-aware molecules and predicts binding affinity. [View on GitHub](https://github.com/guanjq/targetdiff.git)
- **AutoGrow4**: A genetic algorithm-based tool for growing molecules in the binding pocket of a protein. [View on GitHub](https://github.com/durrantlab/autogrow4.git)
- **LiGAN**: A conditional variational autoencoder that generates ligands using 3D protein structures. [View on GitHub](https://github.com/mattragoza/LiGAN.git)
- **RELATION**: A VAE-based model that generates molecules by capturing protein-ligand interactions in 3D. [View on GitHub](https://github.com/micahwang/RELATION.git)
- **Pocket2Drug**: An encoder-decoder model that generates molecules directly from binding pockets using graph-based encodings. [View on GitHub](https://github.com/shiwentao00/Pocket2Drug.git)
- **GraphBP**: A graph-based autoregressive model that builds molecules atom-by-atom within a binding pocket. [View on GitHub](https://github.com/divelab/GraphBP.git)
- **AR**: An autoregressive 3D molecular generative model for structure-based drug design. [View on GitHub](https://github.com/luost26/3D-Generative-SBDD.git)
- **ResGen**: A pocket-aware 3D molecular generation model based on parallel multi-scale modeling. [View on GitHub](https://github.com/HaotianZhangAI4Science/ResGen.git)



## Evaluation Metrics
Our frameworks are evaluated based on several metrics, including:
- **Virtual Docking**: Simulation of molecule and protein/enzyme interactions. [View on GitHub] (https://github.com/coleygroup/pyscreener.git)
- **Pharmacological Activity**: Measures the biological effects of drug molecules. [View on GitHub](https://github.com/diegolfor9/pCHEMBL-prediction.git)
- **Toxicity**: Determine the safety and viability of molecules. [View on GitHub](https://github.com/chemprop/chemprop.git)
- **Quantitative Estimation of Drug Likeness (QED)**: Indicates the likelihood of a molecule being a successful drug.
- **Lipophilicity (LogP)**: Indicates the molecule's ability to penetrate cell membranes.
- **Molecular Weight and Diversity**: Critical for assessing pharmacokinetics and structural variety.

## Results
We analyze the performance of different molecular generation models using the above metrics, with special attention to their ability to generate diverse, innovative molecules that could serve as potential therapeutic agents.

## Code Availability
The code used in our research, along with instructions for running the models, is available in this repository. This includes scripts for molecular docking simulations and evaluations using various computational tools.

## Acknowledgments
We thank all contributors and researchers whose tools and insights have facilitated this project.

## References
- Detailed references to all studies and data sources cited are included at the end of this document.

