# Project Euler — Algorithmic Number Theory Solutions

<div align="center">

[![CI Verified](https://github.com/Amanatar/Project_euler/actions/workflows/ci-verify.yml/badge.svg)](https://github.com/Amanatar/Project_euler/actions)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![SymPy](https://img.shields.io/badge/SymPy-1.12+-green?logo=sympy&logoColor=white)](https://sympy.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

</div>

Computational number theory, prime factorization routines, modular arithmetic, dynamic programming, and combinatorial algorithms solving Project Euler problems 0 through 26 in pure Python.

## Problem Domains Covered

- **Prime Sieve Algorithms & Factorization:** Sieve of Eratosthenes, largest prime factors (Problem 3), 10001st prime generation (Problem 7), summation of primes (Problem 10).
- **Combinatorics & Lattice Paths:** Catalan/binomial path calculations (Problem 15), factorials and digit sum arithmetic (Problem 20).
- **Number Theory & Modular Arithmetic:** Fibonacci sequences (Problem 2), smallest multiple / LCM (Problem 5), Pythagorean triplets (Problem 9), amicable numbers (Problem 21), reciprocal cycles (Problem 26).
- **Dynamic Programming:** Maximum path sum through triangular numeric grids (Problem 18).

## Repository Structure

```
Project_euler/
├── "problem 0- 26.ipynb"  # Sequential vectorized & iterative algorithmic solutions
├── requirements.txt       # Environment dependencies
└── README.md
```

## Setup & Execution

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook "problem 0- 26.ipynb"
```
