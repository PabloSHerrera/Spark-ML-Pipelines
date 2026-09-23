# Spark ML Pipelines

Machine learning pipelines built with **Apache Spark (PySpark MLlib)**, covering classification and regression models. The project runs in a containerized environment with **Docker**, making it fully reproducible on any machine.

## Highlights

- End-to-end ML workflows using Spark's `Pipeline` API: feature engineering, model training, and evaluation
- Classification and regression models trained on distributed data structures
- Reproducible setup with Docker and Docker Compose, with no local Spark installation required

## Repository Structure

| Path | Description |
|---|---|
| `notebooks/` | Jupyter notebooks with the ML pipelines and analysis |
| `working_dir/` | Data and working files |
| `dockerfile` | Container image definition |
| `docker-compose.yml` | Environment orchestration |

## Tech Stack

Python · Apache Spark · PySpark MLlib · Docker · Jupyter Notebook

## How to Run

1. Clone the repository:

```bash
   git clone https://github.com/PabloSHerrera/Spark-ML-Pipelines.git
   cd Spark-ML-Pipelines
```
2. Start the environment:

```bash
   docker-compose up
```
3. Open Jupyter in your browser using the URL shown in the terminal, then run the notebooks in `notebooks/`.

---

*Developed as part of the Data Science course at Universidad del Valle de Guatemala.*

**Authors:** Pablo Herrera · Silvia Illescas
