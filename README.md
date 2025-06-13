# CHL-python
Inversion of chlorophyll content based on mechanism-guided active learning hybrid models
# Started guide
To ensure the program can be completed, please set the absolute path names of the input data and output data and run them. Follow the following simple steps.
# Prerequisites
This project is based on Pycharm and built with the python language. Therefore, users need to install the python library files they are using, refer to Prerequisites.txt.
# Spectra pretreatment
In this project, frist, we performed the spectra pre-process. Users can used the code 'pre-process.py', where it contains many methods for changing origianl spectra, such as SG, MSC, First-order Derivative, resample_spectra. 
And, if you want to display the spectral curves, you also can do it in this code.

# Spectral analysis
Then, we performed the spectral analysis, which denoted the 'SAM' method. And you can obtain it from the code in 'spectral-analysis.py'.  To integrate the spectra after first-order derivate and caculate euclidean_distance, we improved the 'SAM' to 'WSAM'.

# Active learning
Due to the large data dimension of the physical model, there are serious problems of data collinearity and redundancy, resulting in higher computational costs for the inversion model.
Therefore, in order to improve the computational efficiency of the model and enhance its robustness, we have applied active learning techniques.This method can effectively reduce the data dimension and retain informative and representative samples.
If you want to accomplish this process, you can refer to the code 'AL-EDB.py'. This denoted we combined the 'EDB' method with active learning.

# Predict
In this project, final, we constructed an active learning hybrid inversion model based on mechanism guidance. In the code 'predict.py', you can set different ratio combined simulated data with satellite data if you want.

# Description
Although the ultimate goal of this code is to invert the chlorophyll content of vegetation, it can still be used to invert other functional traits of vegetation, and is not limited to this.Users can definitely Improve this project based on their actual application requirements.
Furthermore, due to the platform's restriction that the file size cannot exceed 25 MB, therefore, the sample data in this project is only part of the content, but it is sufficient to represent the entire process.

# Statement 
These code in this project cannot be used for any commercial purposes without the author's consent. 

# Note: Ensure all files are accessible by setting the proper directories on your computer.

# Contact
Bolin Fu: fubolin@glut.edu.cn; Yiji Song: 1020232077@glut.edu.cn
