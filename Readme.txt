In this package, there are five folders.

PSO.apache: results of the Apache subject
PSO.jdk: results of the JDK subject
PSO.matlab: results of the MATLAB subject
PSO.gsl: results of the GSL subject
PSO.gcc: results of the GCC subject

In each folder, there are four subfolders.
1MR: results of 1-MR
2MR: results of 2-MR
3MR: results of 3-MR
4MR: results of 4-MR
In particular, the folder 'before_filter' in the subfolder represents the results using our appoach but without the filtering step.

In each folder, there are many files, and I will explain the file in detail as follows. In particular, I use the 'cos.txt' in 1-MR as the representative.
Each row in this file is shown in this format: {1.000000, -1.000000, -0.999604, 6.279991, 0.000000}, and thus we can identify the MR is: cos(x)-cos(-x+2*PI)=0.
More concretely, there are five parameters in the formular of 1-MR (described in our paper): c1, c2, a, b, d, and the five values in the vector {1.000000, -1.000000, -0.999604, 6.279991, 0.000000} represent the values of corresponding parameters as the order, respectively. That is, c1=1.000000, c2=-1.000000, a=-0.999604, b=6.279991, and d=0.000000


Thanks!