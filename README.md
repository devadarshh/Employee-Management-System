# 🧑‍💼 Employee Management System (C++ STL)

This is a simple **Employee Management System** built using **C++ Standard Template Library (STL)**. It demonstrates the usage of `vector`, `algorithm`, `accumulate`, `copy_if`, `for_each`, and lambda functions in C++.

---

## ✨ Features

- ✅ Create a list of employees with ID, name, and salary  
- 🔽 Sort employees by salary (highest to lowest)  
- 💰 Filter and display high earners (salary > 50,000)  
- 📊 Calculate total and average salary  
- 🥇 Find the highest-paid employee  

---

## 📁 Code Overview

### ✅ Data Structure

```cpp
struct Employee {
    int id;
    string name;
    double salary;
};
