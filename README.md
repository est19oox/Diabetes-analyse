# Diabetes-analyse

# Objective and Requirements
Use Pandas in Python to analyse the following aspects of this dataset: 

(1) Load the data set into Pandas, and define a data frame just including columns ‘time_in_hospital’, 
‘insulin’ and ‘num_lab_procedures’. 

(2) Use a method to remove the missing data in ‘time_in_hospital’ column, and perform z-score 
normalization of the values in this column and generate a new column that contains the normalised 
values.

(3) Perform a one-hot-encoding of the attribute values in column ‘insulin’. To do so, first identify the list 
of unique values in this column (considering missing values as a special category), and then replace 
each of those values by a unique one-hot encoding vector (e.g.., replace all occurrences of ‘No’ by 
[1, 0, 0, 0, 0, 0]). Generate new column that contains the one-hot encoding vectors.

(4) Create 5 bins for the column ‘num_lab_procedures’, and generate a new column to contain the bin 
values. Also explain how you determine the size of bins.
