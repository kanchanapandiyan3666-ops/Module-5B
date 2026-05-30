# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd
df1 = pd.DataFrame({
    'Name': ['Alice', 'Bob'],
    'Age': [20, 21]
})
df2 = pd.DataFrame({
    'Name': ['Charlie', 'David'],
    'Age': [22, 23]
})

result = pd.concat([df1, df2])
print(result)
```
## Output
```
      Name  Age
0    Alice   20
1      Bob   21
0  Charlie   22
1    David   23
```

## Result
Thus, the program has been executed successfully.

