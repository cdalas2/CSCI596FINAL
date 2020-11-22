# CSCI596FINAL
<img src="CloverSurfaces.png " width="250" height="750">

> Protein-induced bilayer deformation calculations

---

### Table of Contents

- [Description](#description)
- [How To Use](#computational-problem)
- [References](#references)
- [Author Info](#author-info)

---

## Description

#### Physical Problem

Using a classical elastic continuum model for lipid bilayers, what is the lipid bilayer deformation induced by a protein of arbitrary shape?

#### Mathematical Objective

<img src="equations.png " width="1200" height="300">


#### Computational Objective

Since Basset function grow exponentially with increasing order n, floating point overflow issues and matrix conditioning issues manifest. We use Arblib library for arbitrary precision floating point calculations, choosing an appropriate precision to avoid overflow and to offset numerical instability when solving the linear system of boundary equations. 

[Back To The Top](#CSCI596FINAL)

---

#### Software

- C++
- Arblib library (version 2.17 or newer)
- Carlos_Membrane_Project
- OpenMP
- OpenMPI

[Back To The Top](#CSCI596FINAL)

---

## How To Use
1. $ make clover
2. $ bash job
#### Installation
1. Download github repo. This will contain the necessary make file, bash script, and source code files
2. Install Arblib library by Frederick Johansson (version 2.17 or newer). You can build from source [1] or download as a package through anaconda3.
3. Install OpenMP.
4. Install OpenMPI (if you want to do multiple protein runs)


#### Thread count speed up and efficiency benchmarks

[Back To The Top](#CSCI596FINAL)

---

## References
[Back To The Top](#CSCI596FINAL)

---

## Author Info

- LinkedIn - [Carlos Alas LI](https://www.linkedin.com/in/carlos-alas-6a4643160/)
- ResearchGate - [Carlos Alas RG](https://www.researchgate.net/profile/Carlos_Alas3)

[Back To The Top](#CSCI596FINAL)
