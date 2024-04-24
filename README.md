# Case Studies

For deciding the best face detection algorithm for the thesis, see the case studies created (created in JupyterHub files). The two main factors for a real-time face detection system is efficacy and accuracy. These factors were also discussed and agreed upon with the bachelor thesis client. There are two case studies

1. Case Study - Comparing Accuracy for Real-Time Face Detection Models
This case study measures the FPS over a dataset with ~2800 images. It presents the result in plotted in multiple graphs. See the [case study for more information](https://github.com/RIT-NTNU-Bachelor/OpenCV_Server/blob/main/analysis/compare_face_detection_accuracy.ipynb)

2. Case Study - Comparing Efficacy for a Real-Time Face Detection System
This case study measures the memory usage of each algorithm. It plots the result as peak mega byte usage during a stress test of the algorithms. For this case, the python package `memory_profiler` is used. The result is plotted in multiple graphs. See the [case study for more information](https://github.com/RIT-NTNU-Bachelor/OpenCV_Server/blob/main/analysis/compare_face_detection_efficacy.ipynb)


**Note:** The case studies do not represent an absolute truth. There are most likely something that makes it not objectively true. Use them with caution.

Code Owners are allowed to use the Github Workflow that triggers the compiling of the case studies. The workflow also downloads the dataset needed. The code for the workflow can be found [here](https://github.com/RIT-NTNU-Bachelor/OpenCV_Server/blob/main/.github/workflows/jupiterhub_workflow.yml). 

Estimated time of compiling both case studies (Note: the repository includes compiled notebooks): 

```txt
~ 2h, 46 min
```