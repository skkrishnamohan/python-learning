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
| [Day10.ipynb](Day10.ipynb) | **OOP — Polymorphism** — Method overriding, polymorphism with loops, method overloading (not supported in Python), deployment strategy patterns |
| [Day11.ipynb](Day11.ipynb) | **OOP — Abstraction** — `ABC`, `@abstractmethod`, abstract base classes, abstract vs concrete methods, cannot-instantiate rule, multiple abstract methods, abstraction vs encapsulation, real-world interface patterns |
| [Day12.ipynb](Day12.ipynb) | **Practice Questions — Basics & OOP Revision** — Variables, data types, operators, conditionals, loops, strings, lists/tuples/dicts/sets, functions (`*args`, `**kwargs`, lambda), OOP (encapsulation, inheritance, polymorphism, abstraction), tricky interview-style questions (reference vs copy, class vs instance attributes, `is` vs `==`) |
| [Day13.ipynb](Day13.ipynb) | **OOP Hands-On Practice Part 1** — Classes with user input & `self`, inheritance with `super()` (extending vs replacing), abstract classes (`Device`, `Shape`), multiple inheritance with MRO (`Teacher`/`Mentor`/`Guide`), abstract class with `__init__` (`Ride` fare calculator) |
| [Day14.ipynb](Day14.ipynb) | **OOP Hands-On Practice Part 2** — Ride Booking System (abstraction with method params), hierarchical inheritance (`Teacher`), Student Result System (conditional logic in classes), polymorphism with loops (`Animal`), Food Delivery App (multiple inheritance with `__init__`), Online Ordering (abstraction), encapsulation getter/setter, factorial & palindrome functions, lambda & `*args`, method overloading (not supported in Python) |
| [Day15.ipynb](Day15.ipynb) | **NumPy — Introduction** — What are Python libraries, documentation, why NumPy over lists (speed, vectorisation, memory, homogeneity), `import numpy as np`, creating arrays (`np.array()`), type coercion (`int < float < string`), `type()` vs `.dtype`, array dimensions (0D scalar, 1D vector, 2D matrix, 3D stack), array attributes (`.ndim`, `.shape`, `.size`, `.dtype`), inhomogeneous shape errors |
| [Day16.ipynb](Day16.ipynb) | **PCA — Principal Component Analysis** — What is dimensionality & why reduce it, the full PCA pipeline, `load_digits` dataset, `StandardScaler` (why scaling matters), covariance matrix, eigenvalues & eigenvectors (intuition), explained variance & cumulative variance, scree plot, choosing number of components (90%/95% threshold), `sklearn.decomposition.PCA`, full pipeline with Logistic Regression + accuracy, when to use vs not use PCA |
| [Day17.ipynb](Day17.ipynb) | **Strings — Deep Dive** — String indexing & slicing, string immutability, essential methods (`.upper()`, `.lower()`, `.strip()`, `.split()`, `.join()`, `.replace()`, `.find()`, `.count()`, `.startswith()`, `.endswith()`, `.isdigit()`, `.isalpha()`), f-strings (formatted string literals), escape characters, raw strings |
| [Day18.ipynb](Day18.ipynb) | **List Comprehensions & Dict Comprehensions** — List comprehension syntax, filtering with `if`, `if-else` in comprehensions, nested comprehensions, dict comprehensions, set comprehensions, `zip()`, when to use comprehensions vs loops |
| [Day19.ipynb](Day19.ipynb) | **File Handling** — `open()` with file modes (`r`, `w`, `a`), `read()`, `readline()`, `readlines()`, `write()`, looping through files, the `with` statement (context managers), JSON files (`json.load()`, `json.dump()`), log file parsing |
| [Day20.ipynb](Day20.ipynb) | **Exception Handling** — Syntax errors vs exceptions, `try/except`, catching specific exceptions (`ValueError`, `TypeError`, `KeyError`, `FileNotFoundError`), `else` and `finally` blocks, `raise`, creating custom exceptions, best practices |
| [Day21.ipynb](Day21.ipynb) | **Modules & Packages** — `import`, `from...import`, `import...as`, built-in modules (`math`, `random`, `os`, `datetime`), `os.path`, environment variables, `strftime()`, `timedelta`, `if __name__ == '__main__'`, `pip`, `requirements.txt` |
| [Day22.ipynb](Day22.ipynb) | **\*\*kwargs, Decorators & Generators** — `**kwargs` explained, combining `*args` and `**kwargs`, dict unpacking with `**`, writing decorators from scratch, `@staticmethod`, `@classmethod`, `@property`, generators with `yield`, `next()`, generator expressions, memory efficiency |
| [Day23.ipynb](Day23.ipynb) | **NumPy — Deep Dive** — Array creation (`arange`, `linspace`, `zeros`, `ones`, `full`, `eye`, `random`), 1D/2D indexing & slicing, `reshape`, `flatten`, `transpose`, element-wise operations, broadcasting, statistical functions (`mean`, `sum`, `min`, `max`, `std`, `argmin`, `argmax`), `axis` parameter, boolean indexing, `np.where`, `vstack`/`hstack`/`concatenate` |
| [Day24.ipynb](Day24.ipynb) | **Pandas — Part 1 (Series & DataFrame Basics)** — Series (labelled 1D array), DataFrame creation (from dicts, lists, NumPy), `head`/`tail`/`info`/`describe`, selecting columns (single & multiple), `loc` vs `iloc`, filtering with conditions (`&`, `|`, `isin`, `str.contains`, `between`), adding/renaming/dropping columns, `read_csv`/`to_csv`, `sort_values` |
| [Day25.ipynb](Day25.ipynb) | **Pandas — Part 2 (GroupBy, Merge & Missing Data)** — `groupby` (split-apply-combine), `agg` (multiple functions), `apply` (custom row/column transforms), `value_counts`, `merge` (inner/left/right/outer joins), `concat`, missing data (`isna`, `fillna`, `dropna`), `nunique` |
| [Day26.ipynb](Day26.ipynb) | **Matplotlib — Data Visualisation** — `plt.plot` (line), `plt.bar`/`barh`, `plt.scatter`, `plt.hist`, `plt.pie`, subplots (`fig, axes = plt.subplots`), customisation (colours, markers, grid, labels, legends, `figsize`), `axhline`/`axvline`, pandas built-in `.plot()`, `plt.savefig` |

---

## DevOps & AI/MLOps Exercises

Each notebook has a dedicated practice section at the bottom with exercises that mirror real work scenarios:

- **Days 1–3** — Output formatting for CI/CD logs, type-casting monitoring API data, system health checks with operators
- **Days 4–5** — Deployment gates with conditional logic, server CPU health monitoring loops, log file analyzers
- **Days 6–7** — Kubernetes config as nested dicts, config merge patterns, model experiment trackers, log formatter functions with `*args`
- **Days 8–9** — OOP: `Server` and `MLExperiment` classes, Azure resource hierarchies (`CloudResource → AzureVM / BlobContainer`), encapsulation with private attributes and getters/setters
- **Days 10–11** — OOP: Polymorphism with deployment strategies (Rolling/BlueGreen/Canary), abstract cloud provider interfaces (swap `AzureProvider`/`OnPremProvider` without changing pipeline logic), CI/CD pipeline abstraction
- **Day 12** — Revision: Server inventory manager (classes + loops + conditionals), Kubernetes/Docker config validators (abstraction + encapsulation), ML experiment tracker combining all 4 OOP pillars
- **Day 13** — OOP Hands-On: Monitoring alert system (abstraction), container runtime hierarchy (inheritance + super()), cloud resource manager (multiple inheritance with Taggable + Billable)
- **Day 14** — OOP Hands-On: Deployment order system (K8s vs App Service abstraction), ML experiment grading (classes with conditional logic), cloud compute + networking (multiple inheritance), fare calculator with `*args`
- **Day 15** — NumPy: Server CPU metrics as 2D arrays, ML experiment accuracy tracking with vectorised operations, multi-region API latency monitoring as 3D arrays
- **Day 16** — PCA: MLOps pipeline monitoring (adding PCA to speed up training), server metrics PCA with correlated features (cpu/memory/disk/temp), debugging a PCA pipeline (missing StandardScaler)
- **Day 17** — Strings: Log line parser, URL builder for Azure API, config value cleaner (strip/split messy config lines), deployment banner generator with f-strings
- **Day 18** — Comprehensions: Server inventory filter, log level counter, config transformer (uppercase keys, filter by prefix), MLOps experiment filter and promotion logic
- **Day 19** — File Handling: Log file analyser (count by level, write summary), Kubernetes config generator (JSON), server inventory manager (read/write/append JSON), deployment report writer
- **Day 20** — Exceptions: Safe config reader (handle missing/invalid JSON), API retry with error handling, deployment validator (custom exceptions for ports, replicas, environment), safe model loader
- **Day 21** — Modules: System info script (`os` module), log rotator (`os` + `datetime`), deployment timer with timestamps, project dependency checker (`importlib`)
- **Day 22** — Advanced: Logging decorator (function name, args, timing), retry decorator with max attempts, K8s deployment config builder with `**kwargs`, lazy log reader generator for large files
- **Day 23** — NumPy Deep Dive: Server metrics dashboard (2D array, axis stats), ML model accuracy comparison (mean, std, normalise), API latency analysis (percentiles, boolean filtering, np.where)
- **Day 24** — Pandas Part 1: Server health report (filter, sort, describe), ML experiment tracker (DataFrame from dicts, filter, sort), Azure cost analysis (column operations, CSV read/write)
- **Day 25** — Pandas Part 2: Infrastructure cost report (groupby team/env, agg), MLOps experiment comparison (merge, groupby model), log analysis pipeline (value_counts, groupby service × level)
- **Day 26** — Matplotlib: Server monitoring dashboard (2×2 subplots: CPU/memory line, bar, histogram), ML training progress (loss/accuracy curves), deployment analytics report (grouped bars, success rate line, pie chart)

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

