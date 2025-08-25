# Project Setup Guide

Follow these steps to set up and run the project:

---

## 1. Extract the ZIP Files
Unzip the provided `.zip` files into the project directory.  
Make sure that `pics.z01` and `pics.zip` are being combined.
Make sure the extracted folders are in the correct location before proceeding.

---

## 2. Install Dependencies
The project dependencies are listed in `requirements.txt`.  
To install them, run:

```bash
pip install -r requirements.txt
```

## 3. CUDA Support
# What is CUDA?

CUDA(Compute Unified Device Architecture) is NVIDIA’s parallel computing platform.
It allows deep learning frameworks like PyTorch or TensorFlow to run computations on your GPU, making training and inference much faster compared to using only the CPU

# How the Code Handles CUDA
* If CUDA is installed:
the project will use your GPU automatically.



* If CUDA is not installed: 
You need to delete  `device= 0` where it is.