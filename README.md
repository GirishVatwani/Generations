# 🧬 CS50 Inheritance: Simulating Genetic Traits

This project, part of Harvard's [CS50x](https://cs50.harvard.edu/x/) curriculum, explores how genetic traits are passed from one generation to the next using the C programming language. You'll simulate a family tree in which each person has two "blood type" alleles (A, B, or O), inherited from their parents, and visualize how inheritance works across generations.

---

## 🚀 What Does the Program Do?

- **Recursively creates a multi-generation family tree of people**
- **Assigns blood type alleles** to each person, randomly for the oldest generation and through inheritance for younger generations
- **Prints each generation's blood types** in a readable family tree structure
- **Demonstrates recursion, pointers, and memory management in C**

---

## 🧬 Genetic Inheritance Overview

- Each person has two blood type alleles.
- The base generation (oldest ancestors) is assigned alleles randomly.
- Each descendant receives one allele from each parent at random.
- The result is a realistic simulation of genetic inheritance.

---

## 📋 How To Use

1. **Download** (start with the [inheritance.c](https://cs50.harvard.edu/x/2025/psets/5/inheritance/) file).
2. **Compile** the program:
    ```
    make inheritance
    ```
3. **Run** the program:
    ```
    ./inheritance
    ```
    (Optionally, modify the code to experiment with different numbers of generations!)

---

## 📂 Project Files

- `inheritance.c`: Main C file for this simulation
- `README.md`: This documentation file

---

## 📊 Example Output

Running the program might produce output like this (output will vary each time):

Child (Generation 0): blood type AA
Parent (Generation 1): blood type AO
Grandparent (Generation 2): blood type AO
Grandparent (Generation 2): blood type OO
Parent (Generation 1): blood type AA
Grandparent (Generation 2): blood type AB
Grandparent (Generation 2): blood type AA

---

## 🎥 Related Video: Inheritance Explained by Ted-Ed

Discover the broader context behind inheritance—genetic and otherwise—in this excellent TedEd talk:  
**[A new way to think about inheritance | David York | TED](https://embed.ted.com/talks/david_york_a_new_way_to_think_about_inheritance)**

---

## 📚 References

- [CS50x Inheritance Problem Set](https://cs50.harvard.edu/x/2025/psets/5/inheritance/)
- [TedEd: A new way to think about inheritance (video)](https://embed.ted.com/talks/david_york_a_new_way_to_think_about_inheritance)

---

## ✨ Credits

Project created as part of CS50x — Harvard University's Introduction to Computer Science.

---

*Explore genetics and C programming—simulate your own family tree today!*
