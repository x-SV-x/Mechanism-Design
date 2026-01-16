# Computational Explorations in Mechanism Design
This repository contains Python notebooks developed alongside a theoretical course in **Mechanism Design** taught by [Dr. Parikshit De](https://eco.iiserb.ac.in/profile_parikshit_de.php)  at [IISER Bhopal](https://www.iiserb.ac.in).

The objectice is to complement formal definitions and proofs with computational implementations that help build applied intuition.
Rather than focusing on large-scale algorithms, the emphasis here is on **conceptual clarity**: translating abstract ideas into explicit code, simulations, and finite examples.

For consistency, nost of the notations and definitions are borrowed from **Professor Debasis Mishra's** notes (Indian Statistical Institute, New Delhi) - [Mechanism Design notes](https://www.isid.ac.in/~dmishra/gmdoc/mdnotes.pdf).

All other relevant sources are cited where applicable.

---

## Motivation

Mechanism Design is typically taught in a highly theoretical manner, with emphasis on axioms, definitions, and impossibility results.  
To deepen understanding, this repository implements key concepts computationally, allowing systematic experimentation with examples, counterexamples, and finite domains.

The goal is to bridge the gap between theory and application while remaining faithful to the underlying mathematics.

---

## Topics Covered

Topics covered in each notebook are as follows:
01. **Mechanism_Design_01 :** A well known result in Mechanism Design for finite alternatives and urestricted preference domain is that, a social choice function(**scf**) is strategyproof if and only if it is monotonic. Proving that strategyproofness implies monotonicity does not involve use of any notion of unrestricedness of the preference domain hence the result holds true even for restricted domain. However proving the converse i.e. monotonicity => strategyproofness involves the notion of unrestricted domain. Hence, the converse does not hold true for restricted domain in general.

  In this notebook we show that the converse holds true for the case of three alternatives and two agents even when the domain is restricted.

**Objectives :**
- Implementing preferences, alternatives, and domains in python in both restricted and unrestricted cases.
- Implementing and checking conditions such as monotonicity and strategyproofness.
- Constructing social choice functions using python lists and dictionaries.

---

## How to View and Use

- All notebooks can be viewed directly on GitHub.
- For easy referencing and shareability, PDF versions of the notebooks are attached (exported via **LaTeX**).
- To run the code locally, open the notebook using Jupyter lab or Jupyter Notebook.

---

## Author

**Vaibhav Thakur**  
Undergraduate student, IISER Bhopal  
Coursework in Economics and Mathematics

---

## License

This project is licensed under the MIT License.


