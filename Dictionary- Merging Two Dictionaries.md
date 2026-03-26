## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
def merge_dicts(d1, d2):
    merged = d1.copy()
    merged.update(d2)
    return merged
dict1 = eval(input())
dict2 =eval(input())

print(merge_dicts(dict1, dict2))

```
## Output

<img width="1060" height="230" alt="530463311-5ca301f7-d15d-4f7f-8822-bae011d04a90" src="https://github
<img width="636" height="198" alt="530463338-d49cbfc3-8daf-4abe-8826-1082a74c89f7" src="https://github.com/user-attachments/assets/cb813496-dba8-4e95-9723-4593b01e5707" />
.com/user-attachments/assets/0eeed040-cbf4-4002-a6df-78b87a198520" />

## Result
Thus the program executed successfully.
