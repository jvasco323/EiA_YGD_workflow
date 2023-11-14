# Explained R scripts for yield gap decomposition

Yield gap decomposition has been increasingly applied in agronomy to disentangle the impact of sub-optimal management on crop production and 
to identify agronomic measures to improve yields. To date, most applications refer to cereal crops (and some tuber and root crops) in a wide 
range of production systems worldwide, particularly in sub-Saharan Africa, South and Southeast Asia, and Northwest Europe. 

This notebook aims to formalize the R scripts used to decompose yield gaps across most of those applications making use of the framework introduced 
by Silva et al. (2017). Data collected by CIMMYT and EIAR for wheat in Ethiopia (Silva et al., 2021), are used here as an example. 

The development of this notebook was possible thanks to the financial support from the OneCGIAR initiative on Excellence in Agronomy. For further 
support and questions on how to implement this workflow to other data sets, or further thoughts on how to improve the theoretical framework used, 
are almost welcome and should be addressed to j.silva@cgiar.org.

**References**:
1) Silva, J.V., Reidsma, P., Laborte, A.G., van Ittersum, M.K. (2017) Explaining rice yields and yield gaps in Central Luzon, Philippines: An application 
of stochastic frontier analysis and crop modelling. European Journal of Agronomy, 82, 223-241. DOI: http://dx.doi.org/10.1016/j.eja.2016.06.017
2) Silva, J.V., Reidsma, P., Baudron, F., Jaleta, M., Tesfaye, K., van Ittersum, M.K. (2021) Wheat yield gaps across smallholder farming systems in Ethiopia.
Agronomy for Sustainable Development, 41, 12. DOI: https://doi.org/10.1007/s13593-020-00654-z
