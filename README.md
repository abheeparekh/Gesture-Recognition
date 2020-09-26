# Gesture-Recognition
Gesture Recognition

The task 1, task2, task3 and task4 can be run in Anaconda environment with Jupyter Notebook.

Running a Jupyter Notebook

In the toolbar at the top, Select Cell option and then select Run All option. This will run all the cells in a Jupyter Notebook

Task 1 Execution Instructions

1. Run the notebook by selecting Run All option as explained above. 
2. Enter the absolute directory path where all data  files are stored
3. Enter window length (Eg: 3)
4. Enter shift length (Eg: 2)
5. Enter resolution (Eg: 3)
6. Wait for some time. After the notebook execution is completed, a message saying task1 completed will be displayed.

WRD files corresponding to all CSV files would be generated after the end of task1

Task 2 Execution Instructions

1. Run the notebook by selecting Run All option as explained above. 
2. Enter the absolute directory path where all data  files are stored
3. Wait for some time. After the notebook execution is completed, a message saying task2 completed will be displayed.

Vectors.txt will be generated. This file will contain TF, TFIDF and TFIDF2 vectors corresponding to all files in the directory

Task 3 Execution Instructions

1. Run the notebook by selecting Run All option as explained above. 
2. Enter the absolute directory path where all data  files are stored
3. Enter the gesture file number for which the has to be viewed on heatmap. Test file 1 to test file 6 are numbered between 61 to 66. It expects a number from 1 to 66 corresponding to the file.
4. Then enter the vector type which has to be used for generating the heatmap. This can be either tf, tfidf or tfidf2. Make sure to enter the input in lower case characters.

Heatmap would be plotted based on the selection made by the user would be plotted

Task 4 Execution Instructions

1. Run the notebook by selecting Run All option as explained above. 
2. Enter the absolute directory path where all data  files are stored
3. Enter the gesture file number for which the 10 most similar gestures are to be computed. Test file 1 to test file 6 are numbered between 61 to 66. It expects a number from 1 to 66 corresponding to the file.
4. Then enter the vector type which has to be used for finding 10 most similar gestures. This can be either tf, tfidf or tfidf2. Make sure to enter the input in lower case characters.

Most similar 10 gesture file numbers would be printed in decreasing order of similarity. The most similar gesture would be displayed first followed by the rest.
