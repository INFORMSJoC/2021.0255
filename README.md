[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# A Nonconvex Regularization Scheme for the Stochastic Dual Dynamic Programming Algorithm
This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The software and data in this repository are a snapshot of the software and data that were used in the research reported on in the paper [A Nonconvex Regularization Scheme for the Stochastic Dual Dynamic Programming Algorithm](https://pubsonline.informs.org/doi/10.1287/ijoc.2021.0255) by A. Bhattacharya, J.P. Kharoufeh, and B. Zeng.

## Cite

Please cite the paper using its DOI and the software itself, using the following DOI:

[https://doi.org/10.1287/ijoc.2021.0255](https://doi.org/10.1287/ijoc.2021.0255)

[https://doi.org/10.1287/ijoc.2021.0255.cd](https://doi.org/10.1287/ijoc.2021.0255.cd)

Below is the BibTex for citing this version of the code.

```
@article{Bhattacharya2023,
  author =        {Bhattacharya, Arnab and Kharoufeh, Jeffrey P. and Zeng, Bo},
  publisher =     {INFORMS Journal on Computing},
  title =         {A Nonconvex Regularization Scheme for the Stochastic Dual Dynamic Programming Algorithm},
  year =          {2023},
  doi =           {10.1287/ijoc.2021.0255.cd},
  note =          {Available for download at https://github.com/INFORMSJoC/2021.0255},
}  
```


## Content

Currently, this repository contains data ancd results used for the multistage portfolio optimization (MPO) and the multistage microgrid energy storage management (MESO) problems used in the paper. The source code, along with any future software development, will be publicly made available at this [link](https://github.com/cfcarnabiitkgp/2021-0255), pending information release approval from the Pacific Northwest National Laboratory (PNNL). 

### Data 

The [data folder]() contains all of the raw data used to generate probabilistic multi-stage scenarios of the MPO and MESO problem instances used in the paper. The portfolio-optimization folder contains historical daily stock prices and returns of all stocks in the S&P 500 index (we used the top 100 out of the leading 500 stocks in our MPO experiments). The microgrid-optimization folder contains data of generator mix (conventional and renewable), power network configuration, historical load and renewable generation, and weather data used to solve instances of the MESO problem. 

### Results

The [results folder]() contain plots of the  average solution times observed when solving instances of the MPO and MESO problems using our customized SDDP algorithm, along with the standard SDDP and SDDP with quadratic regularization. 





