# EEVEE (Efficient Evaluation process Evolution Engine)

**EEVEE**: A machine learning framework for optimizing model evaluation processes by identifying high-value benchmark subsets.

## Abstract

Model evaluation is a cornerstone of machine learning, guiding model design and progress measurement. Designing generalizable evaluation processes remains a challenge. In this paper, we propose EEVEE, a method that frames evaluation process design as a learning problem. By analyzing a large number of evaluation metrics from diverse benchmarks and models, EEVEE identifies a smaller subset of tasks with high predictive power over the full set of evaluation metrics, reducing evaluation time.

Our results identify subsets of benchmarks providing a pareto-optimal signal for model generalization. We structure the subsets into three tiers for 12, 24, and 36 GPU-hour budgets and package them into a unified, efficient, and user-friendly Python framework built with the researcher in mind.

## Installation

To install the necessary dependencies, you can use the provided `requirements.txt` or `requirements-dev.txt` files.

### Using `requirements.txt`

This file includes the basic dependencies required to run EEVEE.

```bash
pip install -r requirements.txt
```

### Using requirements-dev.txt
This file includes additional dependencies for development purposes, including testing and linting tools.

```bash
Copy code
pip install -r requirements-dev.txt
```

### Usage
To be updated: This section will provide details on how to use the EEVEE framework.

### License
This project is licensed under the MIT License.