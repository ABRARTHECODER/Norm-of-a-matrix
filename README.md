# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 25009852
# Developed By: MOHAMED ABRAR M
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
nom=np.linalg.norm(a,1)
print(f"{nom:.2f}")



# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,2)
print(f"{norm1:.2f}")



# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
nor=np.linalg.norm(a,np.inf)
print(f"{nor:.2f}")

```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

<img width="1312" height="761" alt="image" src="https://github.com/user-attachments/assets/a4320887-e504-4655-84e9-423a32016b32" />

### 2-Norm of a Matrix
<br>
<br>
<br>

<img width="1237" height="656" alt="image" src="https://github.com/user-attachments/assets/5c903f15-c1df-4adb-8f0b-4e7d4452e00c" />

### Infinity Norm of a Matrix
<br>
<br>
<br>


<img width="1297" height="661" alt="Screenshot 2025-11-27 103410" src="https://github.com/user-attachments/assets/ccd61de9-6090-409e-a925-9ad5513fbb0e" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
