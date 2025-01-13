scATAC-seq processing according to standard flow, complete flow
Modified to run on Google colab
AD matrices created with Galaxy, then imported 

A lot of issues with 
 (1) different package manager dependencies (condacolab vs pip, some packages work with one package manager, some with other, some with both) 
 (2) installation of packages from different repositories
 (3) use of different cores (Python 3)

Files containing (1) in the name contain samples from two experiments
Files containing (2) in the name contain samples from four experiments

Files with no ending - preprocessing 
Files ending in DA - Differential accessibility analysis

