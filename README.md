Hi!

I am **Joowon Lee**, a Ph.D. student in the Department of Statistics at University of Wisconsin-Madison.

I am interested in the fields of causal inference and machine learning. My general research interest is in learning important latent features from a large dataset that for classficiation or prediction tasks. I seek for methods that can give interpretible results so that it can be used and communicated with broad range of people. 

I love helping individual patients to improve their health condition, however, my ultimate goal is to develop novel statistical methods for medical and public health studies, aiming for the oveerall improvement of public health status. As long as I can pursue these goals, I am not yet confined to any particular kind of jobs (academia or industry). 


## Research 

Here are some of my previous projects: 

 [1] Joowon Lee, Hanbaek Lyu, and Weixin Yao,\
*"Supervised Dictionary Learning with Auxiliary Covariates*" ([arXiv](https://arxiv.org/abs/2206.06774) 2022, 61 pp, [GitHub](https://github.com/ljw9510/SDL))

 [2] Joowon Lee, Seungyeoun Lee, Jin-Young Jang, and Taesung Park, \
*"Exact association test for small size sequencing data*"([Journal](https://bmcmedgenomics.biomedcentral.com/articles/10.1186/s12920-018-0344-z) 2018, 12 pp)

The recent work [1] on *supervised dictionary learning* provides a novel statistical method for finding class-discriminative dictionaries to perform supervised learning in the framework of dictionary learning. 

 [3] Joowon Lee and Gwanhwa Chen, \
 *"Weighting strategies for multiple time-point causal effect identification"* (In preparation)
 
My current ongoing work with Prof. Chen is on developing three-way balancing methods for causal effect identification, where one needs to decide the optimal multi-stage treatments (e.g., Covid19 vaccine) given the initial baseline covariate. 

## Education 

I earned my B.S. in Statistics and Nursing, and master in Statistics at Seoul National Unversity in South Korea. Before joining UW-Madison, I worked as an emergency room nurse at Hyundai Asan medical center in South Korea and joined various projects including patient safety, finding susceptible genes related to pancreatic cancer by dealing with clinical data, microarray, and sequencing data.


<p align="center">
<img width="600" src="https://github.com/HanbaekLyu/NDL_paper/blob/main/Figures/NDL_logo1.png?raw=true" alt="logo">
</p>


## Network Dictionary Learning (repository for paper)

<br/> This repository contains the scripts that generate the main figures reported in the paper: <br/>


&nbsp;

For a more user-friendly repository, please see [NDL package repository](https://github.com/jvendrow/Network-Dictionary-Learning).\
Our code is also available as the python package [**ndlearn**](https://pypi.org/project/ndlearn/) on pypi.


&nbsp;

![](Figures/Figure1.png)
&nbsp;
![](Figures/Figure2.png)
&nbsp;
![](Figures/Figure3.png)
&nbsp;
![](Figures/Figure4.png)
&nbsp;
![](Figures/Figure5.png)
&nbsp;
![](Figures/Figure6.png)
&nbsp;
![](Figures/Figure7.png)
&nbsp;
![](Figures/Figure8.png)
&nbsp;
![](Figures/Figure9.png)
&nbsp;
![](Figures/Figure10.png)
&nbsp;
![](Figures/Figure11.png)
&nbsp;


## Usage

First add network files for UCLA, Caltech, MIT, Harvard to Data/Networks_all_NDL\
Ref: Amanda L. Traud, Eric D. Kelsic, Peter J. Mucha, and Mason A. Porter,\
*Comparing community structure tocharacteristics in online collegiate social networks.* SIAM Review, 53:526–543, 2011.
&nbsp;

Then copy & paste the ipynb notebook files into the main folder. Run each Jupyter notebook and see the instructions therein. 

## File description 

 1. **utils.ndl.py** : main Network Dictionary Learning (NDL) and Network Reconstruction and Denoising (NDR) functions. 
 2. **utils.onmf.py**: Online Nonnegative Matrix Factorization algorithms (see https://github.com/HanbaekLyu/ONMF_ONTF_NDL)
 3. **helper_functions.final_plots_display.py**: helper functions for making plots 
 4. **helper_functions.helper_functions.py**: helper functions for plotting and auxiliary computation 
 5. **helper_functions.link_prediction.py: Script for network denoising benchmark experiments 
 6. **helper_functions.NDL_generate_dictionary.py: Script for generating all network dictionaries for all networks used in the paper
 7. **helper_functions.link_prediction.py: Script for network denoising benchmark experiments 
 8. **helper_functions.node2vec_helper.py: Script for using node2vec for network denoising experiments
 9. **helper_functions.node2vec.py: original node2vec wrapper reformatted 

## Authors

* **Hanbaek Lyu** - *Initial work* - [Website](https://hanbaeklyu.com)
* **Yakoub Kureh** - *Initial work* - [Website](https://www.math.ucla.edu/~ykureh/)
* **Joshua Vendrow** - *Initial work* - [Website](https://www.joshvendrow.com)
* **Mason A. Porter** - *Initial work* - [Website](https://www.math.ucla.edu/~mason/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
