<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Kunj Patel: Data Scientist · ML & Data Engineer" src="assets/header-light.svg" width="100%">
</picture>

I build data systems end to end, from a 25 GB Spark pipeline to the model and the dashboard someone actually opens. Before grad school I spent a year shipping production software: a hospital information system used by 1,000+ healthcare workers, and a sales-analytics platform where I went from intern to leading a team of five.

What I care about: **picking the metric that matters, not the one that's easy.** It keeps coming up in my work: ranked by clinical cost, a 5th-place heart-disease model saves the most lives, and in my trading backtests the two *least* accurate models made the most money.

- 🎓 &nbsp;M.S. Applied Data Analytics, **Boston University** (GPA 3.8)
- 🔭 &nbsp;Looking for **Data Science / ML / Data Engineering** internships and new-grad roles
- 📫 &nbsp;[LinkedIn](https://linkedin.com/in/kunj2710) · [kunjpatel271002@gmail.com](mailto:kunjpatel271002@gmail.com) · Boston, MA

<br>

## Selected work

**[WikiFlow](https://github.com/Kunj2710/wikiflow)**: Predicting Wikipedia editor dropout from 60M revision events
<br><sub>Logistic regression and K-Means written from scratch on Spark RDDs, a distributed Keras DNN, and live scoring of the Wikipedia edit stream through Kafka. Runs on GCP Dataproc and BigQuery. &nbsp;`PySpark` `Kafka` `GCP` `Keras`</sub>

**[Beyond Accuracy](https://github.com/Kunj2710/cvd-referral-cost-classifier)**: Choosing a heart-disease model by what mistakes actually cost
<br><sub>Six classifiers on 70K patients. Once they're ranked by clinical cost, a model that placed 5th on accuracy saves **$9.7M and 65 missed diagnoses per 10K patients**. Includes fairness, robustness and sensitivity audits. &nbsp;`scikit-learn` `pandas`</sub>

**[RAG Document Q&A](https://github.com/Kunj2710/rag-document-qa)**: Ask questions across PDFs, web pages, Wikipedia and arXiv
<br><sub>LangChain pipeline with pluggable vector stores (Chroma, FAISS, ObjectBox) and LLMs (OpenAI, Groq, local), served through a Streamlit UI and a FastAPI/LangServe API. &nbsp;`LangChain` `FastAPI` `Streamlit`</sub>

**[Cassandra vs MongoDB](https://github.com/Kunj2710/cassandra-vs-mongodb-benchmark)**: Benchmarking four workloads on 13M NYC taxi trips
<br><sub>Cassandra writes **2.2× faster**; MongoDB deletes **30× faster** and aggregates **5× faster**. Also covers the async-write mistake that made my first results wrong. &nbsp;`Cassandra` `MongoDB` `GCP`</sub>

**[Football Market Value](https://github.com/Kunj2710/football-market-value-analysis)**: What actually drives a player's transfer price?
<br><sub>Regression, ANOVA, chi-square and odds ratios on 900 top-5-league players. Finds an "aging star discount" of about €14M. &nbsp;`R`</sub>

<br>

<!-- more-projects:start -->
## More projects

| | Project | Result |
|:--|:--|:--|
| 📈 | [**Can ML beat buy-and-hold?**](https://github.com/Kunj2710/stock-trading-ml-backtest) | Backtested 10 classifiers on 5 years of Coca-Cola stock; only 3 beat buy-and-hold, and the least accurate earned the most |
| ⚡ | [**Big data algorithms in PySpark**](https://github.com/Kunj2710/spark-big-data-algorithms) | External merge sort, NYC-taxi analytics, TF-IDF kNN and gradient descent written on RDDs, without MLlib |
| 🏠 | [**Disability prediction, AHS 2023**](https://github.com/Kunj2710/ahs-disability-prediction) | 70+ models on Census data; undersampling beat SMOTE, and gradient boosting catches 73.6% of disability households (AUC 0.84) *(team project)* |
| 🫀 | [**Fetal health from CTG**](https://github.com/Kunj2710/fetal-health-ctg-classifier) | 88.8% accuracy, but only 63% of abnormal cases caught: why imbalance hides failure |
| 🏢 | [**BU building energy benchmarks**](https://github.com/Kunj2710/boston-building-energy-benchmarks) | 82 BU buildings run about 40% above Boston's average energy intensity (city BERDO data) |
| 💵 | [**Banknote forgery detection**](https://github.com/Kunj2710/banknote-forgery-detection) | From a 71% hand-written rule to 100% with kNN, plus a feature-ablation study |
| 🔗 | [**Clustering Dow Jones stocks**](https://github.com/Kunj2710/dow-jones-stock-clustering) | Residual-return k-means over 60 months; sector peers don't reliably move together |
| 🧰 | [**Data mining in R**](https://github.com/Kunj2710/r-data-mining-toolkit) | Feature selection (CFS, Boruta, RFE), LASSO, caret ensembles, Apriori, k-means |
<!-- more-projects:end -->

<br>

## Experience

**Software Developer** · Artem HealthTech &nbsp;<sub>2024</sub>
<br><sub>Cut page-load time 35% on a hospital information system used by 1,000+ healthcare workers. A Redis caching layer reduced database load 40% and saved $3K/month.</sub>

**Project Leader** · Wellnest Tech &nbsp;<sub>2024 · promoted from intern in 3 months</sub>
<br><sub>Led 5 developers on an Angular/.NET sales-analytics platform for 200+ daily users. Built CI/CD that cut deploys from 3 days to 4 hours.</sub>

**Software Developer Intern** · Telnet &nbsp;<sub>2023</sub>
<br><sub>Built an Angular recipe platform for 500+ beta users. Its one-click cart reached 70% adoption in two weeks.</sub>

<br>

## Toolbox

**Daily** &nbsp;Python · SQL · pandas · scikit-learn · PySpark · Git · Jupyter
<br>**Also shipped with** &nbsp;R · Kafka · LangChain · FastAPI · Streamlit · TensorFlow/Keras · XGBoost · FAISS
<br>**Data & cloud** &nbsp;PostgreSQL · MySQL · MongoDB · Cassandra · Redis · BigQuery · GCP · AWS (S3, EC2) · Docker
<br>**BI & web** &nbsp;Tableau · Power BI · Angular · .NET · TypeScript
