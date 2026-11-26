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
| [Day19.ipynb](Day19.ipynb) | **File Handling** — `open()` with file modes (`r`, `w`, `a`), `read()`, `readline()`, `readlines()`, `write()`, looping through files, the `with` statement (context managers), JSON files (`json.load()`, `json.dump()`), log file parsing, **CSV (`csv.DictReader`) & JSON Lines (`app_logs.jsonl`)** |
| [Day20.ipynb](Day20.ipynb) | **Exception Handling** — Syntax errors vs exceptions, `try/except`, catching specific exceptions (`ValueError`, `TypeError`, `KeyError`, `FileNotFoundError`), `else` and `finally` blocks, `raise`, creating custom exceptions, best practices |
| [Day21.ipynb](Day21.ipynb) | **Modules & Packages** — `import`, `from...import`, `import...as`, built-in modules (`math`, `random`, `os`, `datetime`), `os.path`, environment variables, `strftime()`, `timedelta`, `if __name__ == '__main__'`, `pip`, `requirements.txt` |
| [Day22.ipynb](Day22.ipynb) | **\*\*kwargs, Decorators & Generators** — `**kwargs` explained, combining `*args` and `**kwargs`, dict unpacking with `**`, writing decorators from scratch, `@staticmethod`, `@classmethod`, `@property`, generators with `yield`, `next()`, generator expressions, memory efficiency |
| [Day23.ipynb](Day23.ipynb) | **NumPy — Deep Dive** — Array creation (`arange`, `linspace`, `zeros`, `ones`, `full`, `eye`, `random`), 1D/2D indexing & slicing, `reshape`, `flatten`, `transpose`, element-wise operations, broadcasting, statistical functions (`mean`, `sum`, `min`, `max`, `std`, `argmin`, `argmax`), `axis` parameter, boolean indexing, `np.where`, `vstack`/`hstack`/`concatenate` |
| [Day24.ipynb](Day24.ipynb) | **Pandas — Part 1 (Series & DataFrame Basics)** — Series (labelled 1D array), DataFrame creation (from dicts, lists, NumPy), `head`/`tail`/`info`/`describe`, selecting columns (single & multiple), `loc` vs `iloc`, filtering with conditions (`&`, `|`, `isin`, `str.contains`, `between`), adding/renaming/dropping columns, `read_csv`/`to_csv`, `sort_values`, **Parquet, `chunksize=` streaming & `category` memory optimization** |
| [Day25.ipynb](Day25.ipynb) | **Pandas — Part 2 (GroupBy, Merge & Missing Data)** — `groupby` (split-apply-combine), `agg` (multiple functions), `apply` (custom row/column transforms), `value_counts`, `merge` (inner/left/right/outer joins), `concat`, missing data (`isna`, `fillna`, `dropna`), `nunique`, **SQLite (`pd.read_sql`), time-series `resample()`, `drop_duplicates()`, & ETL pipelines** |
| [Day26.ipynb](Day26.ipynb) | **Matplotlib — Data Visualisation** — `plt.plot` (line), `plt.bar`/`barh`, `plt.scatter`, `plt.hist`, `plt.pie`, subplots (`fig, axes = plt.subplots`), customisation (colours, markers, grid, labels, legends, `figsize`), `axhline`/`axvline`, pandas built-in `.plot()`, `plt.savefig` |
| [Day27.ipynb](Day27.ipynb) | 🆕 **Streamlit & Gradio — ML Demo UIs** — Why demo UIs matter for MLOps, Streamlit basics (`st.title`, `st.write`, `st.dataframe`, `st.metric`), interactive widgets (`st.slider`, `st.selectbox`, `st.file_uploader`), plotting in Streamlit (`st.pyplot`, `st.plotly_chart`), Gradio `Interface` and `Blocks`, building a quick ML model demo, layout and theming, deploying Streamlit apps |
| [Day28.ipynb](Day28.ipynb) | **Scikit-learn — Part 1 (ML Fundamentals & Regression)** — What is ML, supervised vs unsupervised, sklearn workflow (`fit` → `predict` → `evaluate`), train/test split, Linear Regression, evaluation metrics (MAE, MSE, R²), `StandardScaler` |
| [Day29.ipynb](Day29.ipynb) | **Scikit-learn — Part 2 (Classification & Pipelines)** — Classification vs regression, Logistic Regression, Random Forest, confusion matrix, accuracy/precision/recall/F1, `Pipeline`, `cross_val_score` |
| [Day30.ipynb](Day30.ipynb) | **XGBoost & Optuna — Hyperparameter Tuning** — XGBoost (eXtreme Gradient Boosting), hyperparameters vs parameters, `GridSearchCV`, Optuna (smart search with `create_study`, `optimize`), XGBoost + Optuna pipeline |
| [Day31.ipynb](Day31.ipynb) | **Joblib — Model Serialization** — Why save models, `pickle` (Python built-in), `joblib` (better for ML), saving/loading sklearn pipelines, saving individual components, model metadata (version, metrics, features) |
| [Day32.ipynb](Day32.ipynb) | 🆕 **Deep Learning Intro (PyTorch)** — Why deep learning matters for MLOps/LLMOps, tensors vs NumPy arrays, `torch.tensor`, autograd and gradients, building a neural net (`nn.Module`, `nn.Linear`, `nn.ReLU`), forward pass, loss functions (`CrossEntropyLoss`, `MSELoss`), optimizers (`SGD`, `Adam`), the training loop, GPU basics (`to('cuda')`), saving/loading models (`state_dict`), when to use deep learning vs classical ML |
| [Day33.ipynb](Day33.ipynb) | **PyYAML — Working with YAML Files** — YAML syntax basics, `yaml.safe_load()` (read), `yaml.dump()` (write), nested structures, multi-document YAML (`safe_load_all`), YAML ↔ JSON conversion, safe loading security |
| [Day34.ipynb](Day34.ipynb) | **MLflow — Experiment Tracking & Model Registry** — `mlflow.log_param()`, `mlflow.log_metric()`, `mlflow.log_artifact()`, `mlflow.sklearn.autolog()`, `search_runs()`, `log_model()`/`load_model()`, Model Registry (register, version, stages), MLflow UI |
| [Day35.ipynb](Day35.ipynb) | **DVC — Data & Model Versioning** — `dvc init`, `dvc add`, `.dvc` pointer files, remote storage (Azure Blob, S3), `dvc push`/`dvc pull`, switching data versions, DVC Pipelines (`dvc.yaml`, `params.yaml`, `dvc repro`), DVC vs MLflow comparison |
| [Day36.ipynb](Day36.ipynb) | 🆕 **Data Validation (Pandera & Great Expectations)** — Why data quality matters in MLOps pipelines, Pandera `DataFrameSchema` and `Column` checks, type/range/nullability validation, `@pa.check_types` decorator for function I/O, Great Expectations suites and expectations, automated data quality gates in CI/CD, failing pipelines on bad data before it reaches the model |
| [Day37.ipynb](Day37.ipynb) | 🆕 **Feature Stores (Feast)** — What is a feature store and why it matters, the training-serving skew problem, Feast concepts (entity, feature view, data source, feature service), `feast init` and `feast apply`, offline feature retrieval for training (`get_historical_features`), online feature serving for inference (`get_online_features`), feature engineering best practices, Feast vs manual feature pipelines |
| [Day38.ipynb](Day38.ipynb) | 🆕 **Model Monitoring & Data Drift (Evidently AI)** — Why models degrade in production, data drift vs concept drift vs prediction drift, Evidently `Report` and presets (`DataDriftPreset`, `DataQualityPreset`, `ClassificationPreset`), column-level drift detection (PSI, KS test, Wasserstein), generating HTML drift reports, automated drift alerts in pipelines, integrating drift checks with MLflow/Prefect for retraining triggers |
| [Day39.ipynb](Day39.ipynb) | **FastAPI — API for Model Serving** — `FastAPI()`, `@app.get`/`@app.post`, path & query parameters, Pydantic `BaseModel` validation, serving ML models via `/predict`, batch predictions, `HTTPException`, Kubernetes health probes (`/healthz`, `/readyz`), Swagger UI auto-docs |
| [Day40.ipynb](Day40.ipynb) | 🆕 **Prometheus Client & Metrics Instrumentation** — Observability: logs vs metrics vs traces, the `prometheus_client` library, metric types (Counter, Gauge, Histogram, Summary), instrumenting a FastAPI app with custom metrics, `/metrics` endpoint for Prometheus scraping, tracking prediction count, latency, error rates, Prometheus scrape config basics, Grafana dashboard awareness |
| [Day41.ipynb](Day41.ipynb) | **Pytest — Testing** — `test_` naming, `assert`, `pytest.raises`, fixtures (`@pytest.fixture`), `@pytest.mark.parametrize`, testing ML code (data shapes, accuracy thresholds, model save/load), mocking (`unittest.mock.patch`), pytest CLI commands |
| [Day42.ipynb](Day42.ipynb) | **Type Hinting & Pydantic** — `typing` module (`List`, `Dict`, `Optional`), dynamic vs static typing, Pydantic `BaseModel`, validation with `Field`, regex constraints, config management with `BaseSettings` |
| [Day43.ipynb](Day43.ipynb) | **Asyncio & Concurrency** — Synchronous vs Asynchronous (I/O vs CPU bound), `async def`, `await`, `asyncio.sleep`, concurrent execution with `asyncio.gather`, async HTTP requests with `httpx` |
| [Day44.ipynb](Day44.ipynb) | **Production Logging** — The `logging` module, log levels (DEBUG to CRITICAL), `StreamHandler`, `FileHandler`, `RotatingFileHandler`, JSON structured logging (`python-json-logger`) |
| [Day45.ipynb](Day45.ipynb) | **Building CLI Tools (Typer)** — Why CLIs matter, `typer.run`, Arguments vs Options (defaults), subcommands with `@app.command()`, interactive prompts (`typer.confirm`), colored output (`typer.secho`) |
| [Day46.ipynb](Day46.ipynb) | **Python Containerization (Docker)** — Slim vs Alpine images, layer caching (`COPY requirements.txt` first), multi-stage builds for ML C-extensions, running as non-root user, `gunicorn` + `uvicorn` production servers |
| [Day47.ipynb](Day47.ipynb) | 🆕 **Kubernetes Python Client** — The `kubernetes` library, loading kubeconfig (`config.load_kube_config`), listing pods/deployments/services, creating deployments programmatically, patching replicas and HPA, watching events with `watch.stream`, deleting resources, namespace management, label selectors, real-world K8s automation scripts for Day-2 operations |
| [Day48.ipynb](Day48.ipynb) | **Cloud SDKs & Automation** — Using Python instead of bash/Terraform for day-2 ops, `DefaultAzureCredential`, `azure-mgmt-compute`, listing VMs, async operations (`begin_deallocate`), `boto3` for AWS equivalent |
| [Day49.ipynb](Day49.ipynb) | 🆕 **Secrets Management** — Why hardcoded secrets are dangerous, `python-dotenv` and `.env` files, `azure-keyvault-secrets` SDK with `DefaultAzureCredential`, reading/writing/listing secrets from Azure Key Vault, `hvac` for HashiCorp Vault, secrets in CI/CD pipelines (GitHub Actions secrets), rotating secrets programmatically, best practices (never log secrets, use environment variables) |
| [Day50.ipynb](Day50.ipynb) | 🆕 **CI/CD Pipeline Automation (GitHub Actions + Python)** — Anatomy of a GitHub Actions workflow YAML, writing Python scripts for CI/CD steps, the `pytest` → build → push → deploy pipeline, matrix testing across Python versions, Python-based smoke tests (verify deployed API health), artifact upload/download, triggering pipelines from Python (`requests` + GitHub API), branch protection and status checks |
| [Day51.ipynb](Day51.ipynb) | **Workflow Orchestration** — What is a DAG?, Apache Airflow (`PythonOperator`, `BashOperator`, bitshift `>>` dependencies), cron alternative, Prefect (`@flow`, `@task` decorators), pipeline retry logic |
| [Day52.ipynb](Day52.ipynb) | 🆕 **Webhooks & Event-Driven Patterns** — What are webhooks and why they matter, building a FastAPI webhook receiver, parsing GitHub/GitLab webhook payloads, signature verification with `hmac` for security, triggering ML retraining on data push events, event-driven architecture patterns, connecting webhooks to Prefect/Airflow DAGs, idempotency and retry handling |
| [Day53.ipynb](Day53.ipynb) | **AIOps: Time-Series Forecasting** — AI for IT Operations, `prophet`, handling seasonality, `ds` and `y` dataframes, predicting future CPU load for proactive auto-scaling |
| [Day54.ipynb](Day54.ipynb) | **AIOps: Log Anomaly Detection** — Unsupervised learning, Isolation Forests (`contamination`), finding weird deployments without hardcoded regex, plotting anomalies in 2D space |
| [Day55.ipynb](Day55.ipynb) | **LLMOps: The OpenAI API & Prompts** — Shifting from MLOps to LLMOps, OpenAI python client, System vs User prompts, Zero-shot vs Few-shot, enforcing JSON output (`response_format`) |
| [Day56.ipynb](Day56.ipynb) | **LLMOps: The LangChain Framework** — `PromptTemplate`, LCEL pipe operator (`|`), Chatbot Memory (`ConversationBufferMemory`), Agents (giving LLMs access to Python functions/tools) |
| [Day57.ipynb](Day57.ipynb) | **LLMOps: RAG & Vector Databases** — Retrieval-Augmented Generation, overcoming LLM hallucinations, `DirectoryLoader`, Text Splitting, Embeddings, ChromaDB, Semantic Search vs SQL |
| [Day58.ipynb](Day58.ipynb) | 🆕 **LangGraph — Agentic AI Workflows** — Why chains aren't enough for complex tasks, stateful agents with LangGraph `StateGraph`, defining nodes (functions) and edges (transitions), conditional routing, tool-calling agents with persistent state, cycles and loops in agent graphs, human-in-the-loop approval nodes, multi-agent patterns, building a DevOps agent that decides → executes → validates → reports |
| [Day59.ipynb](Day59.ipynb) | **LLMOps: Open Source Models & HuggingFace** — Privacy and vendor lock-in, downloading local models, `transformers` pipeline, integrating HuggingFace models seamlessly into LangChain |
| [Day60.ipynb](Day60.ipynb) | **LLMOps: Evaluation & Tracing** — Why standard metrics fail for LLMs, Tracing with LangSmith, LLM-as-a-Judge for automated grading, MLflow LLM autologging |
| [Day61.ipynb](Day61.ipynb) | 🆕 **LLM Guardrails & Safety** — Why LLMs need guardrails in production, NeMo Guardrails / Guardrails AI, input validation (prompt injection detection), output validation (factuality, format, toxicity), Pydantic output parsers for structured LLM responses, rate limiting and cost tracking, responsible AI practices, building a safety wrapper for autonomous agents |
| [Day62.ipynb](Day62.ipynb) | **The Ultimate Capstone Project** — The Autonomous AI SRE combining DevOps, MLOps, AIOps, and LLMOps into a single FastAPI/Docker application with Prometheus metrics, K8s deployment, drift monitoring, guardrails, and end-to-end CI/CD |

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
- **Day 27** — Streamlit & Gradio: Server monitoring dashboard (live CPU/memory metrics with `st.metric` and auto-refresh), ML experiment results viewer (interactive model comparison with sliders and dropdowns), deployment status board with Gradio `Blocks`
- **Day 28** — Scikit-learn Part 1: Server response time predictor (Linear Regression), cost estimator with feature scaling, server health classification baseline
- **Day 29** — Scikit-learn Part 2: Server health classifier (Random Forest, Logistic Regression), API latency classifier, full pipeline with cross-validation
- **Day 30** — XGBoost & Optuna: Server health prediction with XGBoost, hyperparameter tuning with GridSearchCV and Optuna, DevOps metric anomaly detector
- **Day 31** — Joblib: Model artifact manager (save/load with metadata), model versioning (compare v1/v2/v3), deployment-ready model package (model + metadata + requirements)
- **Day 32** — PyTorch: Simple server health predictor (neural net vs scikit-learn comparison), understanding model complexity (count parameters, compare architectures), tensor operations for batch metrics processing, GPU awareness check script
- **Day 33** — PyYAML: Kubernetes manifest generator, CI/CD pipeline config builder, ML experiment config loader for training scripts
- **Day 34** — MLflow: Automated training pipeline with experiment logging, model promotion script (registry stages), experiment dashboard and comparison reports
- **Day 35** — DVC: Data versioning manager (hash-based tracking), CI/CD pipeline config generator (dvc.yaml), reproducibility checker for ML pipelines
- **Day 36** — Data Validation: Kubernetes pod metrics validator (Pandera schema for CPU/memory/restarts DataFrame), ML training data quality gate (check feature ranges, null rates, duplicate rows, class balance), CI/CD data validation step that blocks training on bad data
- **Day 37** — Feature Stores: ML feature registry for server health prediction (define CPU, memory, request_count features), training-serving consistency checker (compare offline vs online feature values), feature engineering pipeline with timestamps and aggregations
- **Day 38** — Model Monitoring: Production drift detector (compare training data distribution vs live inference data), model accuracy decay alerter (track precision/recall over time windows), automated retraining trigger when drift exceeds threshold
- **Day 39** — FastAPI: Server health prediction API (single + batch), A/B testing endpoint for model versions, Dockerized API with K8s health probes
- **Day 40** — Prometheus: FastAPI model serving metrics (prediction request counter, inference latency histogram, error rate gauge, model version info), custom MLOps metrics exporter (training duration, data freshness, drift score as Prometheus gauges)
- **Day 41** — Pytest: K8s config validator tests, ML pipeline CI/CD gate tests (accuracy threshold, latency, model size), API integration tests with mocking
- **Day 42** — Pydantic: Kubernetes Deployment YAML validator, MLOps Hyperparameter Config Validator
- **Day 43** — Asyncio: Async Health Checker (pinging multiple server `/healthz` endpoints concurrently with `httpx`)
- **Day 44** — Logging: MLOps Standard Logger (configuring JSON output with custom fields like `environment` for Kubernetes/Datadog scraping)
- **Day 45** — Typer: MLOps Toolkit CLI (commands for `train`, `deploy`, `status` with interactive confirmation prompts)
- **Day 46** — Docker: The Ultimate ML Dockerfile (slim image, optimized caching, multi-stage, non-root user, gunicorn entrypoint)
- **Day 47** — Kubernetes Python Client: Automated pod restarter (detect CrashLoopBackOff and restart), deployment scaler (patch replicas based on load predictions), namespace resource auditor (list all resources, check limits/requests), event watcher that triggers alerts on warnings
- **Day 48** — Cloud SDKs: The ML Environment Provisioner (Scripting Azure SDK to start/stop expensive GPU instances via CLI)
- **Day 49** — Secrets Management: ML model API key rotator (rotate OpenAI/HuggingFace keys from Azure Key Vault), secure config loader (replace all hardcoded secrets in a config file with Key Vault references), environment-aware secret resolver (dev vs staging vs prod)
- **Day 50** — CI/CD: ML model CI pipeline script (pytest → train → evaluate accuracy gate → register in MLflow → build Docker → push), Python smoke test runner (verify deployed API returns valid predictions), automated rollback script (if smoke test fails, redeploy previous version)
- **Day 51** — Orchestration: The MLOps DAG (Prefect pipeline for checking data drift, retraining, and pushing to MLflow)
- **Day 52** — Webhooks: GitHub push webhook receiver (trigger ML retraining when data repo gets new commits), model registry webhook (auto-deploy model to staging when promoted in MLflow), deployment event notifier (post to Slack/Teams on successful deployment)
- **Day 53** — AIOps (Forecasting): The Predictive Auto-Scaler (Prophet model predicting tomorrow's CPU spikes for proactive scaling)
- **Day 54** — AIOps (Anomalies): The Alerting Pipeline (Isolation Forest detecting latency anomalies in live JSON logs)
- **Day 55** — LLMOps (Prompting): The Automated Incident Responder (OpenAI analyzing Java stack traces and outputting JSON mitigation steps)
- **Day 56** — LLMOps (LangChain): The Azure Cloud Agent (LangChain Agent autonomously running Azure SDK tools to restart VMs via natural language)
- **Day 57** — LLMOps (RAG): The SRE Runbook Assistant (Loading markdown runbooks into ChromaDB for instant Q&A context)
- **Day 58** — LangGraph: Stateful incident responder (diagnose → decide action → execute → validate result → report loop), multi-agent DevOps assistant (K8s agent + monitoring agent + docs agent collaborating), human-in-the-loop deployment approver (agent proposes changes, waits for human approval before executing)
- **Day 59** — LLMOps (HuggingFace): The Secure Log Analyzer (Running Mistral locally for sensitive PII log classification)
- **Day 60** — LLMOps (Eval): The CI/CD Prompt Gate (GitHub Actions script using LLM-as-a-Judge to test prompt changes before deployment)
- **Day 61** — Guardrails: Prompt injection detector for DevOps chatbot (block malicious inputs), output validator (ensure LLM responses are valid YAML/JSON before applying to K8s), cost tracker for LLM API usage (log token counts, estimate costs per request), safety wrapper for autonomous agents (prevent destructive actions like `kubectl delete namespace production`)
- **Day 62** — Capstone: The Autonomous AI SRE v2 (FastAPI + Prometheus Metrics + Docker + K8s Python Client Deploy + Evidently Drift Monitor + AIOps Trigger + LangGraph Agent with Guardrails + RAG Runbooks + MLflow Tracking + CI/CD Pipeline)

---

## Libraries I'm Building Toward

```
# DevOps automation
pip install requests azure-identity azure-mgmt-compute azure-storage-blob paramiko pyyaml kubernetes

# AI / MLOps
pip install pandas numpy scikit-learn mlflow langchain openai

# Deep Learning
pip install torch torchvision

# Data Validation & Feature Stores
pip install pandera great-expectations feast

# Model Monitoring
pip install evidently

# Metrics & Observability
pip install prometheus-client

# LLMOps & Agentic AI
pip install langchain-openai langgraph chromadb transformers nemoguardrails

# Demo UIs
pip install streamlit gradio

# Secrets Management
pip install azure-keyvault-secrets hvac python-dotenv

# API & CLI
pip install fastapi uvicorn gunicorn typer httpx
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
