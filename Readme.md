## Introduction

This repository contains the code for the implementation of a Reversible Data Hiding Technique to hide data in encrypted images using the parametric binary tree labeling technique. Initially, we are given a matrix which represents the values of different pixels of an image.

Research paper used for implementation-> https://ieeexplore.ieee.org/abstract/document/8896058

1. Encrypt.cpp ->
   Enter the pixel values you want to enter in the normal matrix that represents the image.

2. data_hiding.cpp->
   Add this code in the end of encrypt.cpp. After running, you will get encrypted image matrix, the intermediate matrices and a option to enter 3-4 length string that is the data to hide. Now, you will get the embedded matrix.

3. Decrypt.cpp ->
   Enter the pixel values that you got after 2nd step.
   Run the code and you will see the extracted data and decrypted image.
   
