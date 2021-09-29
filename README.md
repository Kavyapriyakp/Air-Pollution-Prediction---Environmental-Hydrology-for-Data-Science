<h1 align="center"><a name="section_name">Air Pollution Prediction</a></h1>

<div align="justify">
A GUI model of a software prototype with latest features developed to aid surveillance systems' monitoring.
</div>

<br>


## Build Status

<img src="https://img.shields.io/badge/langugage-python-blue"/>


## Requirements

<div align="justify">
The following frameworks were utilized in the building of this code.
</div>


<img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white"/>


<div align="justify">
The following tools were utilized in the building of this code.
</div>


<img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white"/>


## User Guide

<div align="justify">


<br>

>  Pro Tip

</div>


<details>
<summary>Installation of Dependencies / Development Setup</summary>

---


<div align="justify">

The code is developed with Python ver.3.8 and `pip` ver.21.0.1 in Windows OS and the same is tested on Ubuntu OS too. The necessary packages and frameworks can be installed from the *Requirements* directory.  However, one can follow the below mentioned steps in case of any errors.


```Python
pip install -r requirements.txt
``` 


Firstly, check the version of Python on your system using:


```Python
python --version
``` 

If you wish to change / upgrade the version or install Python afresh, visit https://www.python.org/downloads/. 

`pip` is a package-management system written in Python used to install and manage software packages. It connects to an online repository of public packages, called the Python Package Index. pip can also be configured to connect to other package repositories.  One can check `pip` version using:

```Python
pip --version
```

If you wish to install `pip` afresh, do:

```Python
python3 -m pip install --upgrade pip
```

or

```Python
sudo apt install python3-pip
```

Installing the necessary packages and depencies is a pre-requisite.  The setup itself varies according to the OS, though the code is really the same.  Yet, the GUI is builded with different libraries in runtime, hence it results in differrent appearances of the same GUI accroding to OSs.


The `tkinter` package (“Tk interface”) is the standard Python interface to the Tk GUI toolkit. The `Tk interface` is located in a binary module named `_tkinter`. It is usually a shared library (or DLL), but might in some cases be statically linked with the Python interpreter.  The `cffi` module is used to invoke `callback` methods inside the program.

```Python
pip install tk
python3 -m pip install cffi
```

`Pillow` is a Python Imaging Library (`PIL`), which adds support for opening, manipulating, and saving images. The current version identifies and reads a large number of formats.  It supports wide variety of images such as “jpeg”, “png”, “bmp”, “gif”, “ppm”, “tiff”.

```Python
python3 -m pip install --upgrade Pillow
```

`OpenCV` is a huge open-source library for computer vision, machine learning, and image processing. `OpenCV` supports a wide variety of programming languages like Python, C++, Java, etc. It can process images and videos to identify objects, faces, and so on. The library has more than 2500 optimized algorithms, which includes a comprehensive set of both classic and state-of-the-art computer vision and machine learning algorithms.


```Python
pip install opencv-python
```

The GUI code supports `tensorflow`'s version (2.0 - 2.4.1). Install `tensorflow` and the latest version of `Pixellib` with:

```Python
pip3 install tensorflow
pip3 install pixellib --upgrade
```

If you have have a PC enabled GPU, install *tensorflow--gpu*'s version that is compatible with the cuda installed on your pc:


```Python
pip3 install tensorflow--gpu
```

`NumPy` is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.  By reading the image as a `NumPy` array ndarray, various image processing can be performed using NumPy functions.


```Python
pip3 install numpy
```


`Imutils` are a series of convenience functions to make basic image processing functions such as translation, rotation, resizing, skeletonization, and displaying Matplotlib images easier with `OpenCV` in Python.


```Python
pip3 install imutils
```


</details>


## Work under Progress



## References



[Go to Top](#section_name)
