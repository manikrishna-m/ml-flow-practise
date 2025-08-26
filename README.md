# ML Flow Practise

This repository demonstrates an end-to-end machine learning pipeline utilizing MLflow for experiment tracking and model lifecycle management. The project focuses on binary classification tasks, showcasing how MLflow can be integrated into the workflow for tracking experiments, managing models, and ensuring reproducibility.([GitHub][1])

---

## 📁 Project Structure

The repository is organized as follows:

```

.
├── mlruns/                 # Directory for storing MLflow experiment data
├── .gitignore              # Git ignore rules
├── README.md               # Project documentation
├── experiment.ipynb        # Jupyter notebook for initial experiments
├── ml_flow_binary_classification.ipynb  # Jupyter notebook for binary classification task
├── mlflow.db               # SQLite database for MLflow backend store
├── mlflow_exp.ipynb        # Jupyter notebook for MLflow experiments
└── requirements.txt        # Python dependencies
```



---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

* [Python 3.6+](https://www.python.org/)
* [pip](https://pip.pypa.io/en/stable/)
* [MLflow](https://mlflow.org/)([GitHub][2])

### Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/manikrishna-m/ml-flow-practise.git
   cd ml-flow-practise
   ```



2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```



3. **Run the Jupyter Notebooks**

   Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```



Open and run the notebooks in the following order:

* `experiment.ipynb`
* `ml_flow_binary_classification.ipynb`
* `mlflow_exp.ipynb`([GitHub][3])

---

## 🧪 MLflow Integration

This project utilizes MLflow for:

* **Experiment Tracking**: Logging and comparing machine learning experiments.
* **Model Management**: Packaging and storing models for reproducibility.
* **Reproducibility**: Ensuring consistent results across different environments.([GitHub][1], [GitHub][4])

To start the MLflow UI and view experiments:

```bash
mlflow ui
```



Then, navigate to [http://localhost:5000](http://localhost:5000) in your browser.

---

## 📄 License

This project is licensed under the MIT License.

---

For more detailed information and to explore the project's components, please visit the [ml-flow-practise repository](https://github.com/manikrishna-m/ml-flow-practise).

---

[3]: https://github.com/manikrishna-m/ml-flow-practise?utm_source=chatgpt.com "GitHub - manikrishna-m/ml-flow-practise"
[4]: https://github.com/peterma/ml-flow?utm_source=chatgpt.com "GitHub - peterma/ml-flow: Open source platform for the machine learning ..."
