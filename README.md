# Quantum SVM 
A comparative study of QSVMs (Quantum Support Vector Machines) and classical SVMs over various datasets (such as iris, breast cancer, digits).
### Quantum Feature Maps Used
- Pauli-X (σx)
- Pauli-Y (σy)
- Pauli-Z (σz)
- Pauli-XY (σx⊗σy)
- Pauli-XYZ (σx⊗σy⊗σz)
- Pauli ZZ
- Pauli ZZZ
- Pauli ZXZY
### Classical Kernels Used
- RBF
- Polynomial
- Linear
- Sigmoid
### Results
The Pauli-Z (σz) Feature Map resulted in the highest performance among all Quantum Feature Maps tested, and gave comparable performance on the Iris and Breast Cancer Datasets to classical kernels. On the Digits dataset, however, classical kernels significantly outperformed all quantum kernels. 
