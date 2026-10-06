# 🇮🇳 IndLan

> **Program in Hindi. Build without limits.**

**IndLan** is a programming language designed to make programming easier and more accessible using **Hindi + English keywords**.

IndLan uses a simple syntax so students and beginners can understand programming concepts without having to learn complex English-based syntax first.

---

## ✨ Features

* 🇮🇳 Hindi + English programming keywords
* 🧑‍💻 Beginner-friendly syntax
* 🧠 Variables and expressions
* 🔀 Conditional statements
* 🔁 Loops
* 🛠️ Functions
* 📦 Modules
* 🏗️ Classes
* 📊 Basic ML-oriented syntax
* 💻 IndLan IDE
* 🖥️ REPL support
* 📄 `.ind` source files

---

## 🚀 Installation

Install IndLan using pip:

```bash
pip install indlan
```

For ML-related packages:

```bash
pip install "indlan[ml]"
```

---

## ▶️ Run IndLan

### Start the IDE

```bash
indlan ide
```

### Start the REPL

```bash
indlan repl
```

### Run an IndLan file

```bash
indlan file.ind
```

Example:

```bash
indlan student.ind
```

---

## 📝 Your First IndLan Program

Create a file named:

```text
hello.ind
```

Write:

```indlan
chhap "Namaste, IndLan!"
chhap "Welcome to programming."
```

Run:

```bash
indlan hello.ind
```

Output:

```text
Namaste, IndLan!
Welcome to programming.
```

---

## 📚 Basic Syntax

### Variables

```indlan
maano naam = "Bhavya"
maano umar = 20

chhap naam
chhap umar
```

### Input

```indlan
maano naam = aalao "Apna naam likho: "
chhap "Hello", naam
```

### Condition

```indlan
agar umar >= 18 {
    chhap "You are eligible."
}
nahito {
    chhap "You are not eligible."
}
```

### Multiple Conditions

```indlan
agar marks >= 90 {
    chhap "Grade A+"
}
nahito_agar marks >= 75 {
    chhap "Grade A"
}
nahito {
    chhap "Keep improving."
}
```

### Loop

```indlan
maano i = 1

jabtak i <= 5 {
    chhap i
    maano i = i + 1
}
```

---

## 🎓 Simple Project Example

### Student Marks Calculator

```indlan
chhap "===== Student Marks Calculator ====="

maano naam = aalao "Student ka naam: "

number_dalao maths = aalao "Maths marks: "
number_dalao science = aalao "Science marks: "
number_dalao english = aalao "English marks: "

maano total = maths + science + english
maano percentage = total / 3

chhap "Student:", naam
chhap "Total Marks:", total
chhap "Percentage:", percentage

agar percentage >= 90 {
    chhap "Grade: A+"
}
nahito_agar percentage >= 75 {
    chhap "Grade: A"
}
nahito_agar percentage >= 60 {
    chhap "Grade: B"
}
nahito_agar percentage >= 50 {
    chhap "Grade: C"
}
nahito {
    chhap "Grade: F"
}
```

---

## 🤖 Machine Learning

IndLan also provides syntax designed for working with machine-learning concepts.

Example:

```indlan
aayat model ke_roop_mein

model.sikhao(data)

maano result = model.bhavishyavani(input)

chhap result
```

---

## 🏗️ How IndLan Works

```text
IndLan Source Code
        ↓
      Lexer
        ↓
      Parser
        ↓
       AST
        ↓
    Evaluator
        ↓
      Output
```

IndLan follows an interpreter-based architecture where source code is tokenized, parsed into an Abstract Syntax Tree (AST), and evaluated.

---

## 📁 File Extension

IndLan programs use:

```text
.ind
```

Example:

```text
hello.ind
calculator.ind
student.ind
game.ind
```

---

## 💻 IndLan IDE

IndLan includes an IDE for writing and running `.ind` programs.

```bash
indlan ide
```

The IDE provides a simple environment for students and developers to write IndLan programs.

---

## 🌐 Official Website

Visit the official IndLan website:

[www.indlan.me](https://www.indlan.me/?utm_source=chatgpt.com)

---

## 📦 PyPI

Install and explore IndLan on PyPI:

[IndLan on PyPI](https://pypi.org/project/indlan/?utm_source=chatgpt.com)

---

## 🐙 GitHub

Source code and development:

[IndLan GitHub Repository](https://github.com/BSS2707/indlan-2.0?utm_source=chatgpt.com)

---

## 🎯 Vision

IndLan aims to make programming more accessible by allowing learners to understand programming concepts through a familiar language while still learning real programming fundamentals.

> **Code in Your Language.**

---

## 👨‍💻 Creator

**Bhavya S. Solanki**

Creator & Developer of IndLan.

---

## 📄 License

See the repository license for the current licensing terms.

---

⭐ If you find IndLan useful, consider giving the project a star on GitHub.

**Made with ❤️ by Bhavya S. Solanki**
