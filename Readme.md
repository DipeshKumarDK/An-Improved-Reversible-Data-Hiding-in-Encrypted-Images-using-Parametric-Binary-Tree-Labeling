## Introduction

This repository contains the code for the implementation of a Reversible Data Hiding Technique to hide data in encrypted images using the parametric binary tree labeling technique. Initially, we are given a matrix that represents the values of different pixels of an image. The image is encrypted using a new encryption matrix and the pixels are labelled into embeddale and non-embeddable pixels using parametric binary tree labeling. The embeddable pixels are then used to hide the secret data and the matrix is sent to the reciever. Now, at the reciever's end, hidden data is retrieved and the matrix is decrypted into original form.

## How To Use

Research paper used for implementation-> https://ieeexplore.ieee.org/abstract/document/8896058

1. Encrypt.cpp ->
   Enter the pixel values you want to enter in the normal matrix that represents the image. A new encrypted matrix with pixels labelled as embeddable and non-embeddable will be generated.

2. data_hiding.cpp->
   Add this code at the end of encrypt.cpp. After running, you will get the encrypted image matrix, the intermediate matrices, and an option to enter 3-4 length string that is the data to hide. Now, you will get the embedded matrix.

3. Decrypt.cpp ->
   Enter the pixel values that you got after 2nd step.
   Run the code and you will see the extracted data and decrypted image.
   
