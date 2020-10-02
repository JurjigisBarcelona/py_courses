| . | . | . |
| - | - | - |
| ![NASA](http://www.nasa.gov/sites/all/themes/custom/nasatwo/images/nasa-logo.svg) | ![NCCS](https://www.nccs.nasa.gov/sites/default/files/NCCS_Logo_0.png) | <img src="https://github.com/astg606/py_courses/blob/master/rapids/NVLogo_H_2160x1080.png" width="275" /> |

# Accelerating Data Science Workflows with RAPIDS

Data science workflow has traditionally been slow and cumbersome when it came to loading, filtering and manipulating data, as well as ML training itself. These processes were constrained to slow, CPU-based compute, and resulted in lengthy cycle times impacting data science productivity. RAPIDS delivers GPU accelerated machine learning and data analytics libraries, deployed on NVIDIA GPU platforms, for maximized data science productivity, performance and insights. Bring the power of GPU acceleration to your research and decrease your time to new discoveries with RAPIDS.

In this course, you will learn how to GPU-accelerate your data science applications by:

- Utilizing key RAPIDS libraries like cuDF (GPU-enabled Pandas-like dataframes) and cuML (GPU-accelerated machine learning algorithms)
- Learning techniques and approaches to end-to-end data science, made possible by rapid iteration cycles created by GPU acceleration.


**Prerequisites**: Python, Numpy, Pandas, Scikit-Learn

To take this course, you are expected to:

- Install the [OKTA SFT client](https://github.com/astg606/py_courses/blob/master/rapids/Hackathon_Cluster_Instructions_NASA.pptx) on your laptop before the beginning of the class (hopefully by Tuesday, November 3). The client is required to connect the NVIDIA Hackathon Cluster. If you do not have the administrative privilege on your work computer, we highly recommend that you use instead your personal computer. Note that the access to the cluster will be granted few hours before the course starts.
- Have a gmail account, needed to have access to Google Colaboratory.

You might find it useful:

- To install the Anaconda Python distribution by following the instructions at: [Anaconda installation Guide](https://docs.continuum.io/anaconda/install/)
- To learn little more about Jupyter notebook: 
 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/jupyter_notebook/jupyter_notebook_introduction.ipynb)

## AGENDA

- **10:00-10:15 [Welcome and Cluster Setup](#)**
- **10:15-11:00 [Introduction to GPU Computing and RAPIDS
     - How to build and execute end-to-end GPU-accelerated data science workflows
- **11:00-12:00 [Introduction to cuDF](#)**
     - Hands-on: Implement GPU-accelerated data preparation and feature extraction using cuDF
- **12:00-13:00 [Lunch break](#)**
- **13:00-14:00 [Introduction to cuML](#)**
     - Hands-on: Implement GPU-accelerated machine learning algorithms such as Linear Regression and UMAP using cuML
- **14:00-14:30 [Introduction to Dask](#)**
     - Overview of Dask [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/dask/overview_dask.ipynb)
- **14:30-15:00 [Dask + GPUs](#)**
     - Demo on how to distribute data and computation over multiple GPUs



<!---
| 17:15-17:30 | **Feedback Session** |  |  |
| 17:15-17:30 | **Feedback Session** |  <a href="https://www.surveymonkey.com/r/PWQVXH5"> Evaluation Survey </a> | |
--->