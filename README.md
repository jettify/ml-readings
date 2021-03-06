# Readings In ML And Distributed Systems

List of papers I find interesting.

## ML

* [Learning from Imbalanced Data](http://www.ele.uri.edu/faculty/he/PDFfiles/ImbalancedLearning.pdf)
* [XGBoost: A Scalable Tree Boosting System](https://arxiv.org/pdf/1603.02754.pdf)


## Model Interpretation
* ["Why Should I Trust You?" Explaining the Predictions of Any Classifier](https://arxiv.org/pdf/1602.04938.pdf) (2016) -- *Describes explanation technique that explains the predictions of any classifier in an in- terpretable and faithful manner, by learning an interpretable model locally around the prediction.*

* [Anchors: High-Precision Model-Agnostic Explanations](https://homes.cs.washington.edu/~marcotcr/aaai18.pdf) (2018) -- *Paper inntroduces a novel model-agnostic system that explains the behavior of complex models with high-precision rules called anchor.*

* [A Unified Approach to Interpreting Model Predictions](http://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions.pdf) (2017) -- *Paper shows that several methods in the literature used for explaining individual model predictions fall into the category of "additive feature attribution" methods. New kind of additive feature attribution method based on the concept of Shapely values and call the resulting explanations the SHAP values*

## Machine Learning In Production

* [Data Management Challenges in Production Machine Learning](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45a9dcf23dbdfa24dbced358f825636c58518afa.pdf) (2017) *Tutorial about data-management issues that arise in the context of machine learning pipelines deployed in production.*

* [What’s your ML Test Score? A rubric for ML production systems](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45742.pdf) (2016) -- *Using machine learning in real-world production systems is complicated by a host of issues not found in small toy examples or even large offline research experiments. Testing and monitoring are key considerations for assessing the production-readiness of an ML system. Authors present an ML Test Score rubric based on a set of actionable tests to help quantify these issues.*

* [Hidden Technical Debt in Machine Learning System](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) (2015) -- *Authors explore several ML-specific risk factors to account for in system design. These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, configuration issues, changes in the external world, and a variety of system-level anti-patterns.*

* [A framework for monitoring classifiers’ performance: when and why failure occurs?](https://www3.nd.edu/~nchawla/papers/KAIS09.pdf) (2009) *This article implements a comprehensive evaluation framework to proactively detect breakpoints in classifiers’ predictions and shifts in data distributions through a series of statistical tests.*

* [Rules of Machine Learning: Best Practices for ML Engineering](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf) (2017) -- *This document is intended to help those with a basic knowledge of machine learning get the benefit of best practices in machine learning from around Google.*

* [The Data Linter: Lightweight, Automated Sanity Checking for ML Data Sets](http://learningsys.org/nips17/assets/papers/paper_19.pdf) (2017) -- *Paper introduces the data linter, ML tool that automatically inspects ML data sets to 1) identify potential issues in the data and 2) suggest potentially useful feature transforms.*
