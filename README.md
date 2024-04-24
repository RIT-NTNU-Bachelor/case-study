# Case Studies

For deciding the best face detection algorithm for the thesis, see the case studies created (created in JupyterHub files). The two main factors for a real-time face detection system is efficacy and accuracy. These factors were also discussed and agreed upon with the bachelor thesis client. There are two case studies

1. Case Study - Comparing Accuracy for Real-Time Face Detection Models
This case study measures the FPS over a dataset with ~2800 images. It presents the result in plotted in multiple graphs. See the [case study for more information](https://github.com/RIT-NTNU-Bachelor/case-study/blob/main/compare_face_detection_accuracy.ipynb)

2. Case Study - Comparing Efficacy for a Real-Time Face Detection System
This case study measures the memory usage of each algorithm. It plots the result as peak mega byte usage during a stress test of the algorithms. For this case, the python package `memory_profiler` is used. The result is plotted in multiple graphs. See the [case study for more information](https://github.com/RIT-NTNU-Bachelor/case-study/blob/main/compare_face_detection_efficacy.ipynb)


**Note:** The case studies do not represent an absolute truth. There are most likely something that makes it not objectively true. Use them with caution.

Code Owners are allowed to use the Github Workflow that triggers the compiling of the case studies. The workflow also downloads the dataset needed. The code for the workflow can be found [here](https://github.com/RIT-NTNU-Bachelor/case-study/blob/main/.github/workflows/jupiterhub_workflow.yml). 

Estimated time of compiling both case studies (Note: the repository includes compiled notebooks): 

```txt
~ 2h, 46 min
```

## About the Git History 

As of PR [#54](https://github.com/RIT-NTNU-Bachelor/OpenCV_Server/issues/54) in the OpenCV Server, this was originally part of the [OpenCV Server](https://github.com/RIT-NTNU-Bachelor/OpenCV_Server) code. The decision for moving it out of the repository was based on the following arguments: 

- **Reduced Repository Size:** Separating case studies into their own repository keeps the main server lightweight, enhancing performance and ease of cloning and setup for new users.
- **Improved Code Cohesion:** By isolating the case studies, we can maintain a high level of cohesion within each repository, ensuring that each component focuses on a specific set of responsibilities.
- **Simplified Version Control:** With separate repositories, tracking and reverting changes becomes more straightforward, as the history of commits in each repo is more relevant to its specific content.
- **Consistent Codebase Across Repositories:** Maintaining the same `models` module in both repositories ensures consistency and interoperability of features, critical for functionality and integration testing.
- **Focused Issue Tracking and Documentation:** Issues, pull requests, and documentation can be more precisely tailored to the repository's content, improving clarity and effectiveness in project management.
- **Client Convenience:** Separating the case studies into their own repository simplifies the user experience. The user can utilize each repo without the added complexity of the other repository.  


Because of this transition between repositories the commit history is quite short. See PR, Issues and commit related to the case studies before PR [#54](https://github.com/RIT-NTNU-Bachelor/OpenCV_Server/issues/54) (before 24th April 2024)