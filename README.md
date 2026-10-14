# Task-5-Python-Listictionaries-Tuples-Sets-and-Ds
## Data Science Internship — Veda Technology

### Objective
Develop practical skills for handling structured data using Python collections.

### Tools
- Python
- Jupyter Notebook

## 1. Lists
A list is an ordered, changeable collection that allows duplicate values.

```python
students = ["Sujitha", "Ravi", "Priya"]
students.append("Kiran")
students.remove("Ravi")
students.sort()
print(students)
```

## 2. Tuples
A tuple is an ordered collection that cannot be changed after creation. Duplicate values are allowed.

```python
coordinates = (10, 20, 30)
print(coordinates[0])
print(coordinates.count(20))
print(coordinates.index(30))
```

## 3. Sets
A set is an unordered collection of unique values. Duplicate values are removed automatically.

```python
numbers = {10, 20, 20, 30, 40}
numbers.add(50)
numbers.discard(20)
print(numbers)
print(30 in numbers)
```

## 4. Dictionaries
A dictionary stores data as key-value pairs. Keys must be unique.

```python
student = {
    "name": "Sujitha",
    "branch": "Data Science",
    "year": 2
}
student["year"] = 3
student["college"] = "My College"
print(student["name"])
print(student)
```

## 5. Comparison Table

| Feature | List | Tuple | Set | Dictionary |
|---|---|---|---|---|
| Syntax | `[]` | `()` | `{}` | `{key: value}` |
| Ordered | Yes | Yes | No guaranteed positional order | Yes (insertion order) |
| Changeable | Yes | No | Yes | Yes |
| Duplicates | Allowed | Allowed | Not allowed | Keys must be unique |
| Access | Index | Index | Membership / iteration | Key |

## 6. Common Methods

| Collection | Methods | Purpose |
|---|---|---|
| List | `append()`, `remove()`, `sort()` | Add, remove, and sort items |
| Tuple | `count()`, `index()` | Count an item and find its position |
| Set | `add()`, `remove()`, `discard()` | Add or remove items |
| Dictionary | `keys()`, `values()`, `items()`, `get()` | Access keys, values, and pairs safely |

## 7. Practice Tasks
1. Create a list of five student names. Add one name, remove one name, and sort the list.
2. Create a tuple of five numbers. Print its first and last elements.
3. Create a set containing repeated numbers and show that duplicates are removed.
4. Create a dictionary for an employee with name, ID, and department. Update the department.
5. Write a short program that demonstrates at least two methods for each mutable collection.

## 8. Conclusion
Python collections help store, organize, access, and update data efficiently. Choose a list for an ordered changeable sequence, a tuple for a fixed sequence, a set for unique values, and a dictionary for key-value data.
