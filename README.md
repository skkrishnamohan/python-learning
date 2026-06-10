# My Python Learning Journey

> **Who I am:** I'm a DevOps Engineer upskilling into Python — for automation, AI/MLOps, and LLMOps.  
> **Why Python:** Every tool I work with — Azure SDK, Kubernetes clients, MLflow, LangChain, FastAPI — is Python-first.  
> **This repo:** My personal class notes, written in my own words, with hands-on exercises themed around DevOps and AI/MLOps.

---

## Structure

Each `DayN.ipynb` notebook is one learning session. Notes are written like I'm in class — short comments, quick examples, real scenarios from my work context.

Every notebook ends with a **DevOps / AI-MLOps Practice** section with exercises tied directly to what I do as a DevOps engineer.

---

## Notebook Index

| Notebook | Topics Covered |
|----------|---------------|
| [Day1.ipynb](Day1.ipynb) | **Python Introduction** — What Python is, interpreted vs compiled, why Python dominates in 2024+, Python in my DevOps & MLOps world, how to install and run. Then: `print()` function — basic output, `sep`, `end` parameters |
| [Day2.ipynb](Day2.ipynb) | **Variables & Data Types** — Variable declaration, naming rules, `int`, `float`, `str`, `bool`, type casting (`int()`, `float()`, `str()`), `type()` function |
| [Day3.ipynb](Day3.ipynb) | **Operators** — Arithmetic, comparison, logical (`and`, `or`, `not`), assignment operators, membership (`in`, `not in`), identity (`is`, `is not`) |
| [Day4.ipynb](Day4.ipynb) | **Conditional Statements** — `if`, `elif`, `else`, nested conditions, ternary operator, real-world branching logic |
| [Day5.ipynb](Day5.ipynb) | **Loops, Lists & Tuples** — `for`, `while`, `break`, `continue`, nested loops, `range()`, `enumerate()`, list methods, tuple immutability |
| [Day6.ipynb](Day6.ipynb) | **Dictionaries & Sets** — Dict CRUD, nested dicts, `.update()`, `.get()`, looping over dicts, sets, set operations (union, intersection, difference) |
| [Day7.ipynb](Day7.ipynb) | **Functions** — `def`, parameters, default args, `*args`, `**kwargs`, return values, `None` return, lambda functions, scope |
| [Day8.ipynb](Day8.ipynb) | **OOP — Intro** — Classes, objects, `__init__`, `self`, instance attributes, instance methods, creating and using objects |
| [Day9.ipynb](Day9.ipynb) | **OOP — Encapsulation & Inheritance** — Public/private attributes, getters/setters, single, multilevel, hierarchical, multiple inheritance, `super()` |
| [Day10.ipynb](Day10.ipynb) | **OOP — Polymorphism & Abstraction** — Method overriding, duck typing, `ABC`, `@abstractmethod`, abstract base classes, real-world interface patterns |

---

## DevOps & AI/MLOps Exercises

Each notebook has a dedicated practice section at the bottom with exercises that mirror real work scenarios:

- **Days 1–3** — Output formatting for CI/CD logs, type-casting monitoring API data, system health checks with operators
- **Days 4–5** — Deployment gates with conditional logic, server CPU health monitoring loops, log file analyzers
- **Days 6–7** — Kubernetes config as nested dicts, config merge patterns, model experiment trackers, log formatter functions with `*args`
- **Days 8–10** — OOP: `Server` and `MLExperiment` classes, Azure resource hierarchies (`CloudResource → AzureVM / BlobContainer`), abstract cloud provider interfaces (swap `AzureProvider`/`OnPremProvider` without changing pipeline logic)

---

## Libraries I'm Building Toward

```
# DevOps automation
pip install requests azure-identity azure-mgmt-compute azure-storage-blob paramiko pyyaml kubernetes

# AI / MLOps
pip install pandas numpy scikit-learn mlflow langchain openai
```

---

## Setup

```bash
# Clone
git clone <repo-url>
cd python-learning

# Since I use Anaconda (recommended for beginners)
# 1. Open Anaconda Prompt
# 2. Go to the project folder
cd python-learning

# 3. Start Jupyter Notebook
jupyter notebook

# Optional but better: create a separate conda environment for this repo
conda create -n python-learning python=3.11
conda activate python-learning
jupyter notebook
```

### What is `venv`?

`venv` means **virtual environment**.

Think of it like a small isolated Python workspace just for one project.

Why this matters:

- Without a virtual environment, every package I install goes into one common Python setup on my machine.
- After some time, projects can start conflicting with each other because one project may need one package version and another project may need a different version.
- A virtual environment avoids that problem by keeping project dependencies separate.

Simple example:

- Project A may need `pandas==1.5`
- Project B may need `pandas==2.2`
- If both use the same global Python, this becomes messy.
- If each project has its own environment, both can work safely.

In my case, since I use **Anaconda**, I will mostly use a **conda environment** instead of `python -m venv`.

So for me, the idea is the same:

- `venv` = Python's built-in way to isolate packages
- `conda env` = Anaconda's way to isolate packages

Both solve the same problem: keeping each project clean and independent.

### Recommended for my workflow

Since I am learning in Jupyter Notebook and already using Anaconda:

- Use **Anaconda Prompt**
- Create one conda environment for this repo
- Open Jupyter Notebook from that environment

That is simpler and more practical for my current setup than learning `venv` first.

---

*Started as a DevOps engineer. Learning Python to automate everything and break into AI/MLOps.*

