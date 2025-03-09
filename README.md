# EDL-BRKGA-Peptide-Design
- This repository presents a novel computational framework that integrates the biophysics-based Peptide Binder Design (PepBD) algorithm with evidential deep learning (EDL) and metaheuristic search to accelerate the design of plastic-binding peptides.

- The framework leverages the predictive power of EDL to efficiently explore the vast peptide sequence space, while incorporating uncertainty quantification to prioritize promising candidates.

- Molecular dynamics simulations validate the efficacy of the designed peptides, demonstrating their superior binding affinity compared to existing solutions, thus opening a new avenue for bio-inspired microplastic remediation strategies.

## Citation
```
@Article{D4DD00219A,
author ="Alshehri, Abdulelah S. and Bergman, Michael T. and You, Fengqi and Hall, Carol K.",
title  ="Biophysics-guided uncertainty-aware deep learning uncovers high-affinity plastic-binding peptides",
journal  ="Digital Discovery",
year  ="2025",
volume  ="4",
issue  ="2",
pages  ="561-571",
publisher  ="RSC",
doi  ="10.1039/D4DD00219A",
url  ="http://dx.doi.org/10.1039/D4DD00219A",
abstract  ="Plastic pollution{,} particularly microplastics (MPs){,} poses a significant global threat to ecosystems and human health{,} necessitating innovative remediation strategies. Biocompatible and biodegradable plastic-binding peptides (PBPs) offer a potential solution through targeted adsorption and subsequent MP detection or removal from the environment. A challenge in discovering plastic-binding peptides is the vast combinatorial space of possible peptides (i.e.{,} over 1015 for 12-mer peptides){,} which far exceeds the sample sizes typically reachable by experiments or biophysics-based computational methods. One step towards addressing this issue is to train deep learning models on experimental or biophysical datasets{,} permitting faster and cheaper evaluations of peptides. However{,} deep learning predictions are not always accurate{,} which could waste time and money due to synthesizing and evaluating false positives. Here{,} we resolve this issue by combining biophysical modeling data from Peptide Binder Design (PepBD) algorithm{,} the predictive power and uncertainty quantification of evidential deep learning{,} and metaheuristic search methods to identify high-affinity PBPs for several common plastics. Molecular dynamics simulations show that the discovered PBPs have greater median adsorption free energies for polyethylene (5%){,} polypropylene (18%){,} and polystyrene (34%) relative to PBPs previously designed by PepBD. The impact of including uncertainty quantification in peptide design is demonstrated by the increasing improvement in the median adsorption free energy with decreasing uncertainty. This robust framework accelerates peptide discovery{,} paving the way for effective{,} bio-inspired solutions to MP remediation."}


```
# About

## Overview
* `1 Data/` contains PepBD data results
* `2 Models/` contains EDL moddels
* `3 Codes/` contains peptide representation and genetic algorithm generation methods
* `4 Results/` contains the results of EDL and molecular dynamic simulations along with molecular dynamics comparisons between PepBD and EDL

## Requirements
* python (>=3.7)
* tensorflow (>=2.0)
* evidential-deep-learning
* Pickle
* functools
* pymoo

To install `evidential-deep-learning`: 
```
pip install evidential-deep-learning
```

To install `pymoo`: 
```
git clone https://github.com/anyoptimization/pymoo
cd pymoo
pip install .
```

## LICENSE: Attribution-NonCommercial 4.0 International 

