[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Data for the Empirical Analysis of the Paper [" TGVx: Dynamic Personalized POI Deep Recommendation Model"](https://doi.org/) 

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The software and data in this repository are a snapshot of the software and data
that were used in the research reported on in the paper 
[TGVx: Dynamic Personalized POI Deep Recommendation Model](https://pubsonline.informs.org/journal/ijoc) by X.-J. Wang, T. Liu, and W. Fan. 

## Cite

To cite this software, please cite the [Xiao-Jun Wang, Tao Liu, Weiguo Fan. TGVx: Dynamic Personalized POI Deep Recommendation Model, INFORMS Journal on Computing.](https://pubsonline.informs.org/journal/ijoc) using its DOI and the software itself, using the following DOI.

[![DOI](https://zenodo.org/badge/574702645.svg)](https://zenodo.org/badge/latestdoi/574702645)

Below is the BibTex for citing this version of the code.

```
@article{TGVx,
  author =        {X.J. Wang, T. Liu, and W. Fan},
  publisher =     {INFORMS Journal on Computing},
  title =         {TGVx: Dynamic Personalized POI Deep Recommendation Model, v2021.0010},
  year =          {2022},
  doi =           {10.5281/zenodo.7407123},
  note =          {https://github.com/INFORMSJoC/2021.0010},
}  
```
## Contact Details

If you have questions about the paper, please contact Xiao-Jun Wang <wxjjessicaxj0903@126.com> . 

If you have questions about the code, please contact Liu Tao <lt110510@163.com>.

## Description

The goal of this software is to facilitate readers to reproduce the experimental results in this paper. 

Our experiments verify the effectiveness of the TGVx model in both local and out-of-town recommendation scenarios.

## Environment Requirements

To run the code, you will need to make sure that you have the following dependencies installed: 

- Python 3, `numpy`, `pandas`, `tensorflow`, `scikit-learn`, `scipy`, `networkx`

- Matlab, the `MEX` compilation environment needs to be configured

## Results

Please view Supplemental Material-2021.0010-23.1.27.pdf 

## Replicating

The `src` folder contains all the code which implements TGVx. its structure is used when the provided software reads and writes files and references modules. It is therefore important the folder structure is not modified.


To start the test, run the`Main.py` file in the `src` folder.  We recommend to run this code in GPUs.

We provide sample data files that can run the code, and the complete dataset can be found [here](https://sites.google.com/site/yangdingqi/home/foursquare-dataset).


## Acknowledgement
We want to thank the editor and anonymous reviewers for their detailed and constructive feedbacks in helping improve the paper. We also want to thank Professor Jiafu Tang's helpful comments. 

## Funds

This work is supported by the National Natural Science Foundation of China (Nos.71831003, 72293563, 72172025), the High-level Talent Innovation Team Project of Dalian Science and Technology Talent Innovation Support Policy Project (No.2022RG17), Scientific Research Funding Project of the Education Department of Liaoning Province (No.LN2019Q44), and the Basic Scientific Research Project of Liaoning Provincial Department of Education (No.LJKMZ20221582).
