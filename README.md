# SVD-and-its-applications

This repository presents a small research about Singular Value Decomposition (SVD) and its applications. Specifically, it summarizes 3 different forms of SVD. This will help prevent researchers from getting confused when sorting through literatures with different definitions of SVD. This project also demostrates 3 interesting applications of SVD. See `SVD Report.pdf` for details. Below is a brief summary of it.

### SVD Forms
Given an 𝑚×𝑛 matrix 𝐴 and the factorization 𝐴 = 𝑈𝐷𝑉<sup>𝑇</sup> is the Singular Value Decomposition of 𝐴, we have the following forms of SVD (consider the case 𝑚 > 𝑛, the case of 𝑚 < 𝑛 is very similar):
|       SVD Forms       |    Matrix   A    |    Matrix   U    |    Matrix   D    |    Matrix V<sup>T</sup>  |
|:---------------------:|:----------------:|:----------------:|:----------------:|:------------------------:|
|    Full               |        m*n       |        m*m       |        m*n       |            n*n           |
|    Thin               |        m*n       |        m*n       |        n*n       |            n*n           |
|    Compact (r<n)      |        m*n       |        m*r       |        r*r       |            r*n           |
|    Truncated (t≪r)    |        m*n       |        m*t       |        t*t       |            t*n           |

### Image compression application
As an application of truncated version, SVD can be used to extract the most important features from images. As a result, the resulting image’s size will be much lesser that the original size. The idea is to apply rank-t truncated SVD on the matrix of pixels of an image. Below are the original image and images of different ranks:

<p align="center">
    <img src="./Image_Compression/style/Horses.jpg" height="190"/>
    <img src="./Image_Compression/style/compression1.png" height="190"/>
    <img src="./Image_Compression/style/compression2.png" height="190"/>
</p>

## Disclaimer
**This software is published for academic and non-commercial use only.**

## Acknowledgement

* This work was done by Vien Bui, and Sumanth Bail at *the University of Alabama at Birmingam*.

* All the references are mentioned in the SVD Report file.

## Contact
Feel free to contact me if there is any question (Vien Bui bnvien@gmail.com).
