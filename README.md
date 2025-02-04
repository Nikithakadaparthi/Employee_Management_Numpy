# 👩‍💼 Employee Management & NumPy Operations

## 📝 **Project Overview**

This project is divided into two main sections:

1. **Employee Management System (Object-Oriented Programming)**
   - A class-based approach to manage employee details, inheritance, and calculation of average salary.
   
2. **NumPy Array Manipulation**
   - Random vector generation, reshaping arrays, and conditional data manipulation using NumPy.

---

## 🎯 **Objectives**

- **Implement Object-Oriented Programming (OOP)** concepts like classes, inheritance, and methods.
- **Manage Employee Data** including attributes like name, family, salary, and department.
- **Calculate Average Salary** dynamically with employee count.
- **Utilize NumPy** for efficient array operations:
  - Generate random vectors.
  - Reshape arrays.
  - Replace maximum values in each row.

---

## ⚙️ **Technologies Used**

- **Python 3:** Core language for scripting.
- **NumPy:** For high-performance array operations.
- **Matplotlib (Optional):** For data visualization, if needed.

---

## 💼 **Employee Management System**

### **Key Features:**

1. **Class `Employee`:**
   - Attributes: `name`, `family`, `salary`, `department`.
   - Method: `avg_salary()` to compute average salary dynamically.
   - Tracks the total count of employees using a class variable `empCount`.

2. **Class `Fulltime_Employee`:**
   - Inherits from `Employee` class.
   - Adds an extra attribute `emp_type` to differentiate full-time employees.

### **Sample Output:**

```
Count of the Employees: 3
Average salary of the Employee: 700000.0
Employee Name: Nikitha
Family Members: 4
Employee Annual Salary: 2100000
Department: Cloud Architect
```

---

## 🔢 **NumPy Array Operations**

### **Key Operations:**

1. **Random Vector Generation:**
   - Created using `np.random.uniform()` with values between 1 and 20.

2. **Reshaping the Array:**
   - Reshaped the vector to a 4x5 matrix using `.reshape()`.

3. **Replacing Maximum in Each Row:**
   - Utilized NumPy's advanced indexing to replace the maximum value in each row with `0`.

### **Sample Output:**

```
Random Vector:
 [8.37, 7.38, 5.75, 8.17, 15.58, ...]

After Reshaping (4x5):
 [[8.37, 7.38, 5.75, 8.17, 15.58],
  [18.83, 19.98, 11.79, 16.77, 16.80],
  [2.86, 17.08, 8.47, 11.93, 10.73],
  [19.74, 16.31, 17.97, 6.25, 1.62]]

Replacing Maximum in Each Row:
 [[8.37, 7.38, 5.75, 8.17, 0],
  [18.83, 0, 11.79, 16.77, 16.80],
  [2.86, 0, 8.47, 11.93, 10.73],
  [0, 16.31, 17.97, 6.25, 1.62]]
```

---

## 🚀 **How to Run the Project**

1. **Clone the Repository:**
   ```bash
   git clone [GitHub Repository Link]
   ```

2. **Run the Python Script:**
   ```bash
   python employee_numpy_project.py
   ```

3. **Optional (for Notebooks):**
   ```bash
   jupyter notebook
   ```

---

## 💡 **Future Improvements**

- Add more employee types like `PartTime_Employee` or `Contract_Employee`.
- Implement advanced NumPy operations like matrix multiplication.
- Integrate data visualization using Matplotlib.

---

## 🙌 **Contributions**

Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

---

**Author:** Nikitha Kadaparthi  
**GitHub:** [GitHub Profile](https://github.com/Nikithakadaparthi)  
**LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/nikitha-kadaparthi-4a42321a8/)

> *"Bridging data and development with efficient Python solutions."*


