# Solutions_Explain

### Exercise1

The bug occurs because python set does not preserve order.
The issue is fixed by using list type 


### Exercise2

The original code is incorrect because NumPy slicing returns views, causing values to be overwritten during assignment.
The issue is fixed by copying the coordinate columns before swapping them.


### Exercise3

The plot is incorrect because the values read from the CSV file are strings instead of numeric values
This is fixed by converting the CSV values to floats


### Exercise4

The structural bug was caused by assuming a fixed batch size for all batches
This was fixed by using the actual batch size of the data.
The cosmetic bug was caused by incorrectly comparing the batch index with the batch size when displaying results.
