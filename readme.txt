Instructions:

1. To run without Surf

Run the No_SURF file.

Output: 
output_knn.csv
output_nb.csv
output_lr.csv
output_svm.csv

2. To run with Surf

Run the SURF file.

Output: 
output_surf_knn.csv
output_surf_nb.csv
output_surf_lr.csv
output_surf_svm.csv

3. To run CNN

Run the CNN file.

Output:
submission_cnn.csv

NOTE:

You can directly run the classifiers by commenting these function:

preprocessing_without_surf("dataset") in No_SURF.py file

preprocessing_surf("dataset") in SURF.py file

I am providing the processed dataset:
data.csv file is used in No_SURF.py and SURF.py
train40.csv and train60.csv is used in CNN.py
