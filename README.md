
## 4.2 Lab - Introduction to Functions in Python (GitHub Codespaces Version)

### **Introduction**

Functions are essential building blocks in Python programming, allowing you to encapsulate code into reusable pieces. This lab will guide you through editing and running a Python file in GitHub Codespaces. You’ll explore how to define functions, pass parameters, and return values — key skills for writing reusable and organized Python code.

### **Objectives**

* Learn how to define and call functions in Python.
* Understand how to pass information using parameters.
* Practice using return values to get results from functions.
* Gain experience editing and running code in GitHub Codespaces.

---

### **Lab Steps**

#### **Step 1: Launch GitHub Codespaces**

1. Go to the repository for this lab on GitHub.
2. Click the green **"Code"** button, then select **"Codespaces"** > **"Create codespace on main"**.
3. The Codespace will launch in a browser-based Visual Studio Code environment.

---

#### **Step 2: Open the Starter Code**

1. In the left file explorer, locate and open `function_lab.py`.
2. You’ll see some base code or an empty script file ready to be edited.

---

#### **Step 3: Add a Simple Greeting Function**

Verify the contents of the file:

```python
# Simple Greeting Function
def greet():
    print("Hello from Python functions!")

greet()
```

---

#### **Step 4: Add a Function with Parameters**

Below the previous code, add:

```python
# Function with Parameters
def greet_user(name):
    print(f"Hello, {name}! Welcome to the function lab.")

greet_user("Alice")
```

---

#### **Step 5: Add a Function with Return Value**

Add this code to the bottom of the file:

```python
# Function with Return Value
def add_numbers(num1, num2):
    return num1 + num2

result = add_numbers(10, 15)
print("The sum of the numbers is:", result)
```

---

#### **Step 6: Run the Script**

1. Open the terminal inside Codespaces by selecting `Terminal > New Terminal` from the top menu or pressing **Ctrl + \`**.
2. Run the script with:

```bash
python3 function_lab.py
```

---

#### **Step 7: View the Expected Output**

If everything is working correctly, the terminal should display:

```
Hello from Python functions!
Hello, Alice! Welcome to the function lab.
The sum of the numbers is: 25
```

---

### **Summary**

In this lab, you practiced editing and running Python functions using GitHub Codespaces. You wrote a basic greeting, added parameters, and returned results. These examples demonstrated how functions help you write cleaner and more modular code — and how Codespaces makes cloud-based coding easy and accessible from anywhere.
