# Analyzing quantum states

## Single qubit state tomgraphy

From PMT data to quantum states

1. We have performed a single qubit tomography and saved it in the file qc2157.dat . The dataset contains all data that is required for a gate set tomography.

2. Load the dataset

2. We will convert the PMT counts into bright and dark outomes and calculate the excitation probability

3. The first three entries of the dataset are the measurements that are required for a single-qubit tomography. Measurement operators are (Sz,Sy,Sx)

4. Reconstruct the single qubit density matrix

## Single qubit randomized benchmarking

1. The files contained in the folder rb_data contain experimental data from reandomized benchmarking

2. Load all files. .raw files contain the PMT counts .dat files contain the excitation probability in the second column

3. The files contain sequence lengths of [10,30,50, 70,90, 110,130, 150,170, 190] Clifford operations

4. Fit an exponential decay A + B*p**N to the exponential decay

5. Calculate the fidelity of a Clifford operation as F = (p+1)/2