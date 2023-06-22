# MATH578F22CSULB

MATH 578 - Numerical Linear Algebra, Fall 2022

California State University -- Long Beach

The content of this course closely follows *Computational Linear Algebra for Coders* that was taught by Rachel Thomas (fast.ai) in USF Data Science program, which is accessible through this website: [https://github.com/fastai/numerical-linear-algebra/blob/master/nbs/0.%20Course%20Logistics.ipynb](https://github.com/fastai/numerical-linear-algebra/blob/master/nbs/0.%20Course%20Logistics.ipynb). The course is taught in Python with Jupyter Notebooks, using libraries such as Scikit-Learn, Numpy, Scipy, Matplotlab, Pandas for most lessons, as well as Numba (a library that compiles Python to C for faster performance) and PyTorch (an alternative to Numpy for the GPU) in a few lessons. 

Throughout the semester, I will be using Jupyter Notebook to write most of my lecture notes and coding; while sometimes handwriting some mathematical derivations using notability. Meanwhile, I will record all my lecture videos. All the notability notes, jupyter notebook notes, and lecture videos will be linked under the Course Content below. 

## Course Syllabus

Click here for the Course Syllabus: [https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb)

## Additional CSULB Syllabus Statements

* [COVID-19 Health and Safety Requirements](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#COVID-19-Health-and-Safety-Requirements)
* [Title IX Prohibits Gender Discrimination](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#Title-IX-Prohibits-Gender-Discrimination)
* [Supporting Undocument Students](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#Supporting-Undocument-Students)
* [Syllabus Statement on Basic Needs](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#Syllabus-Statement-on-Basic-Needs)
* [Syllabus Statement on Eliminating Anti-Blackness](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#Syllabus-Statement-on-Eliminating-Anti-Blackness)

## Course Content

The following listing links to the notebooks in this repository, rendered through the [nbviewer](http://nbviewer.jupyter.org) service. The contents will be added and updated dynamically throughout the semester. 

### 1. Course Logistic, Downloads and Install, Basic Introduction (*[Lecture01 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EdlgVcVHcm1LhyK9WIRc6mQBbJ_O4y0rmtiZRCxaXAqobQ?e=E9hsxJ) covering 1.1-1.3*, *[Lecture02 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/ETy-K785D8BAqnSJw9RXpb0BfE86Nf5axYm_UfZ0YLFljQ?e=jupcra) covering 1.4 and Assignment 1*)
* 1.1 [Course Syllabus](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb)
* 1.2 [Downloads and Install](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Downloads.ipynb)
* 1.3 [Jupyter Notebook and Markdown Language](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Markdown.ipynb)
* 1.4 [Introduction to Python](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec01.ipynb)
* **[Assignment #1](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment01.ipynb)**  *Due Aug 30, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 2. Linear Algebra Basics (*This chapter is the reading part of [Assignment 2](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment02.ipynb).*)
* 2.1 [What is an array?](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#What-is-an-array?)
* 2.2 [Creating arrays](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Creating-arrays)
* 2.3 [Array maths](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Array-maths)
* 2.4 [Indexing and Slicing](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Indexing-and-Slicing)
* 2.5 [Types of operations](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Types-of-oper5tions)
* 2.6 [Linear algebra and other advanced math](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Linear-algebra-and-other-advanced-math)
* **[Assignment #2](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment02.ipynb)**  *Due Sep 6, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 3. Topic Modeling with NMF and SVD (*[Lecture03 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EXutjbDjYaJFsUNsYKOTqo0BaZWn-CzXozLuFjCq4hm0vQ?e=zYfWEU) covering 3.1*, *[Lecture04 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EUCxJYsdxrVNnxcMXm3aUukBEhs6ltP8WFkTnhpB-p6ogQ?e=l0gtVw) covering 3.1, 3.2*, *[Lecture05 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EXI36rawlXpElDWiezwZa5sBKawX4yJECeldG74l2ow5Jg?e=OiuCHL) covering 3.2, 3.3*, *[Lecture06 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EWL5dD33yvVIvLykQmOrJ0YBl_G7vOGgq29UU6xY8E8IPg?e=YxZko6) covering 3.4--3.7*)
* 3.1 [Set up data](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Set-up-data)
* 3.2 [Singular Value Decomposition (SVD)](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Singular-Value-Decomposition-(SVD))
* 3.3 [Non-negative Matrix Factorization (NMF)](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Non-negative-Matrix-Factorization-(NMF))
* 3.4 [PyTorch](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#PyTorch)
* 3.5 [Truncated SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Truncated-SVD)
* 3.6 [Randomized SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Randomized-SVD)
* 3.7 [Implementing our own Randomized SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Implementing-our-own-Randomized-SVD)
* **[Assignment #3](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment03.ipynb)**  *Due Sep 20, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 4. [Background Removal with Robust PCA](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb)(*[Lecture07 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EQchEBpN84NHjtB1jqb1N0cBadjPBF1Fizwk3qKFJV6Zrw?e=gBsBha) covering 4.1--4.2*)
* 4.1 [Getting Started](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb#Getting-Started)
* 4.2 [SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb#SVD)
* 4.3 [PCA](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb#Principal-Component-Analysis-(PCA))
* 4.4 [Robust PCA](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb#Robust-PCA-(via-Primary-Component-Pursuit))
* **[Book Chapter on SVD and PCA](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/topics/10457733) has been added to Beachboard.** (*[Lecture08 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EUC4-P-lRvJHnH8A4lYrLJcBf2XgMxuWqR-5WS2Zr6cLTg?e=7ChC0Y) covering SVD and PCA, [notes](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/topics/10458541) posted in Beachboard.*)
* **[Lecture notes on Robust PCA](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/units/10458538) has been added to Beachboard.** (*[Lecture09 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EeteMrXExyJOn7CI-vHElGkBgMctX2a-qzzke8mrhkiUXQ?e=a88gSd) covering Robust PCA*) 
* **[Yale Face denoising with Robust PCA](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/yaleB_RPCA.ipynb)(*[Lecture10 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EfnG5I020EdEh1mCp-hx6ToBaFLO4HYgpSkf5qeQwdki4A?e=EPCWtV), [Lecture11 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EVcbbmz5ULJDietA7uQWS4kB9rqZKRDYoeVfVCEWNj__Dw?e=ssgVQy)*)
* **[Assignment #4](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment04.ipynb)**  *Due Oct 4, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 5. [Compressed Sensing with Robust Regression](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec05_CS_RR.ipynb)(*[Lecture12 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/ES2ATBBm9BJBvMYFv4MmV2EBXLabkqJfNdJ3tzHGn9dLJw?e=JcJ8nm) covering 5.1--5.3, [Lecture13 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EYycydrNxW9Dk5XpB6MLyL8Bjj2vQQB0uwlPcGUiogfmUQ?e=tt1cdQ) covering 5.3--5.4 with [Lecture notes](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/units/10458538), [Lecture14 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EQt623R6ZB9AlPTbbI6w2KUB8haNRgReAIaCstS7kfd3Hw?e=YXPaKv) covering 5.5--5.6, , [Lecture15 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/ET56ISrHQa9NngJyT92PfLMBEXinOCDqnf6pMNFP9xu15w?e=rKkhby) covering 5.6--5.7 and LU factorization*)
* 5.1 [Broadcasting](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec05_CS_RR.ipynb#Broadcasting)
* 5.2 [Sparse Matrices (in Scipy)](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec05_CS_RR.ipynb#Sparse-Matrices-(in-Scipy))
* 5.3 [CT scans](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec05_CS_RR.ipynb#Today:-CT-scans)
* 5.4 [Generate Data](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec05_CS_RR.ipynb#Generate-Data)
* 5.5 [Generate Projections](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec05_CS_RR.ipynb#Generate-Projections)
* 5.6 [Intersection between x-rays and data](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec05_CS_RR.ipynb#Intersection-between-x-rays-and-data)
* 5.7 [Regresssion](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec05_CS_RR.ipynb#Regresssion)
* **[Assignment #5](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment05.ipynb)**  *Due Oct 20, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 6. [Predicting Health Outcomes with Linear Regressions](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec06_LinRegrApp.ipynb)(*[Lecture16 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/Ee1TX48j-XRAkEdr3nPQZWIBaXgqtr6mjGYz_s-JaVdJdw?e=mJpaA4)*)

### 7. [How to Implement Linear Regression](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec07_Implement_LR.ipynb)
* [Lecture17 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/ET0ljBUwbF1PoaApPryIbekBaRxlwl6LRdKs_SiS5GbPBA?e=n8tm3J)
* [Notes on different methods for solving Least Squares problem.](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/units/10458538)
* [Lecture18 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EY0GKAMcU01CuXJdHHEhz24Btjqhzeyivk-hLQ4dJG7BwA?e=MRV5wD)

### 8. [PageRank with Eigen Decompositions](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec08_PageRank.ipynb) (*[Lecture19 video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EUAs9SeIpiRAg5SJlAxQbFABJfakDSYLHK-86liuTbv5tg?e=rnHnbB) on 8.1 and 8.2, [Lecture20 video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EUiyDXXsILJArfrcUnwhlgMBiDJsr34j2Eav0-qTTG5zqA?e=J2hDiY) on 8.2*, [Lecture21 video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EY_6uV2tca9JtcOJXHI2qhoBGJqV1zkiNsjc9BR907WXvA?e=mWHqpr)[Lecture22 video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EcIey0uRT2xItr_3uI26oYcB-e-FTgxlOKe5z11261FQvQ?e=veo2fX)[Lecture23 video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/Ea5yRN4ZEIJIk1MeAB7_6q0BzkHXI47KOCtqhm0qpBadbA?e=Kw3zaz))
* 8.1 [SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec08_PageRank.ipynb#Motivation)
* 8.2 [DBpedia Dataset](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec08_PageRank.ipynb#DBpedia)
* 8.3 [Power Method](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec08_PageRank.ipynb#Power-method)
* 8.4 [QR Algorithm](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec08_PageRank.ipynb#QR-Algorithm)
* 8.5 [Two-phase approach to finding eigenvalues](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec08_PageRank.ipynb#A-Two-Phase-Approach)
* 8.6 [Arnoldi Iteration](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec08_PageRank.ipynb#Arnoldi-Iteration)
* [Lecture notes on Arnoldi, QR, Hessenberg](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/units/10458538)
* **[Assignment #6](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment06.ipynb)**  *Due Dec 1, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 9. [Implementing QR Factorization](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec09_Implement_QR.ipynb)(*[Lecture25 video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/ESg-fs0XYNpCkhjfcqcaXfEB5UzLfFczBgcJc3tglyTPaw?e=80bSp6)*)
* [Lecture notes on QR factorization](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/units/10458538)

### 10. [Final project](https://csulb-my.sharepoint.com/:w:/g/personal/paul_sun_csulb_edu/ERyZZD7OfWJOqkrPR7KagsgB6FOLMwiMk3YpKrbLu4xHJA?e=ZnaIda)
