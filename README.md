![Banner](https://github.com/MANISANKARDIVI/MANISANKARDIVI/blob/main/Banner.png)

<h1 align="center">Hi 👋, I'm DIVI MANI SANKAR</h1>

<h3 align="center">
DevOps & MLOps Engineer | Cloud | Kubernetes | ML Platform Engineering
</h3>

<p align="center">
Building scalable infrastructure, automated delivery pipelines, and production-ready machine learning platforms.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=manisankardivi&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views"/>
</p>

---

## 👨‍💻 About Me

I'm a **DevOps & MLOps Engineer** focused on building reliable cloud infrastructure, Kubernetes platforms, CI/CD pipelines, GitOps workflows, and production machine learning systems.

### What I Work On

- ☁️ Cloud Infrastructure & Automation
- ⚙️ DevOps & Platform Engineering
- ☸️ Kubernetes & Container Platforms
- 🔄 CI/CD & GitOps
- 🤖 MLOps & ML Platform Engineering
- 🧠 ML Training & Workflow Orchestration
- 📦 Data & Model Versioning
- 🚀 Model Deployment & Serving
- 📊 Monitoring & Observability

### Engineering Lifecycle

**Code → Build → Test → Deploy → Train → Validate → Register → Serve → Monitor → Retrain**

---

# ⚙️ DevOps

<p align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD"/>
  <img src="https://img.shields.io/badge/KEDA-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="KEDA"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>

### DevOps Focus

**AWS • Terraform • Docker • Kubernetes • Jenkins • GitHub Actions • Argo CD • KEDA • GitOps • CI/CD • Infrastructure as Code • Linux • Prometheus • Grafana • Monitoring • Observability**

---

## 🏗️ DevOps Architecture

```text
                           Git
                    Code + Configuration
                              |
                              v
                 +--------------------------+
                 |       CI / Build         |
                 |                          |
                 |   GitHub Actions         |
                 |   Jenkins                |
                 +------------+-------------+
                              |
                              v
                      +---------------+
                      |    Argo CD     |
                      | GitOps / CD    |
                      +-------+-------+
                              |
                              v
                      +---------------+
                      |  Kubernetes   |
                      +-------+-------+
                              |
                     +--------+--------+
                     |                 |
                     v                 v
                 Workloads          KEDA
                                      |
                                      v
                                  Autoscaling
                                      |
                                      v
                              +---------------+
                              |  Prometheus   |
                              +-------+-------+
                                      |
                                      v
                               +--------------+
                               |    Grafana   |
                               +--------------+
```

---

# 🤖 MLOps

<p align="center">
  <img src="https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white" alt="DVC"/>
  <img src="https://img.shields.io/badge/Feast-FF6F00?style=for-the-badge&logo=feast&logoColor=white" alt="Feast"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow"/>
  <img src="https://img.shields.io/badge/Kubeflow-326CE5?style=for-the-badge&logo=kubeflow&logoColor=white" alt="Kubeflow"/>
  <img src="https://img.shields.io/badge/KServe-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="KServe"/>
  <img src="https://img.shields.io/badge/Great%20Expectations-7A3E9D?style=for-the-badge&logoColor=white" alt="Great Expectations"/>
</p>

### MLOps Focus

**DVC • Feast • MLflow • Kubeflow • KServe • Data Validation • Feature Management • ML Pipelines • Experiment Tracking • Model Registry • Model Training • Model Validation • Model Deployment • Model Serving • Model Monitoring • Retraining Automation**

---

## 🏗️ MLOps Architecture

```text
                           Git
                    Code + ML Config
                              |
                              v
                    CI / GitOps Pipeline
                              |
                   +----------+----------+
                   |                     |
                   v                     v
             GitHub Actions           Jenkins
                   |                     |
                   +----------+----------+
                              |
                              v
                         Argo CD
                        GitOps / CD
                              |
                              v
                        Kubernetes
                              |
                              v

+-------------------------------------------------------------------+
|                         MLOps Platform                            |
|                                                                   |
|   Data Sources                                                    |
|   Snowflake / S3 / BigQuery                                       |
|              |                                                    |
|              v                                                    |
|      +----------------------+                                     |
|      | Great Expectations   |                                     |
|      | Data Validation      |                                     |
|      +----------+-----------+                                     |
|                 |                                                 |
|        +--------+--------+                                         |
|        |                 |                                         |
|        v                 v                                         |
|      DVC              Feast                                        |
|   Data / Artifact    Feature Store                                |
|   Versioning                                                        |
|        |                 |                                         |
|        +--------+--------+                                         |
|                 |                                                  |
|                 v                                                  |
|          +-------------+                                           |
|          |  Kubeflow   |                                           |
|          |  Pipelines  |                                           |
|          +------+------+                                           |
|                 |                                                  |
|                 v                                                  |
|        Feature Engineering                                        |
|                 |                                                  |
|                 v                                                  |
|         +---------------+                                          |
|         | Model Training|--------------------+                     |
|         +-------+-------+                    |                     |
|                 |                            |                     |
|                 v                            v                     |
|        Model Validation                 MLflow Tracking             |
|                                              |                     |
|                                  +-----------+-----------+          |
|                                  |                       |          |
|                                  v                       v          |
|                          Experiment Tracking      Model Registry    |
|                                                           |        |
|                                                           v        |
|                                                    MLflow Storage   |
|                                                    PostgreSQL       |
|                                                    S3 / Azure Blob  |
|                                                           |        |
|                                                           v        |
|                                                    Promotion Gate   |
|                                                           |        |
|                                                           v        |
|                                                       Argo CD       |
|                                                           |        |
|                                                           v        |
|                                                        KServe       |
|                                                           |        |
|                                                           v        |
|                                                   Model Serving     |
|                                                           |        |
|                                                           v        |
|                                              Monitoring & Metrics   |
|                                                           |        |
|                                                   +-------+-------+ |
|                                                   |               | |
|                                                   v               v |
|                                              Prometheus        Grafana|
|                                                   |               |
|                                                   v               |
|                                         Drift / Performance       |
|                                              Detection             |
|                                                   |               |
|                                                   v               |
|                                           Retraining Trigger       |
|                                                   |               |
|                                                   +-------> Kubeflow
|                                                                   |
+-------------------------------------------------------------------+
```

---

## 🔄 Production ML Lifecycle

```text
Data Sources
     |
     v
Data Validation
     |
     v
DVC / Feast
     |
     v
Kubeflow Pipelines
     |
     +----> Feature Engineering
     |
     +----> Model Training
                |
                +----> MLflow Tracking
                |       - Experiments
                |       - Parameters
                |       - Metrics
                |
                v
        Model Validation
                |
                v
         Promotion Gate
                |
                v
      MLflow Model Registry
                |
                v
             Argo CD
                |
                v
             KServe
                |
                v
        Model Serving
                |
                v
 Monitoring & Observability
          |             |
          v             v
     Prometheus       Grafana
          |
          v
 Drift / Performance Detection
          |
          v
   Retraining Trigger
          |
          +---------------> Kubeflow
```

---

# 🧰 Languages

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>

---

# 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=manisankardivi&show_icons=true&locale=en" alt="GitHub Stats"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=manisankardivi&show_icons=true&locale=en&layout=compact" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=manisankardivi" alt="GitHub Streak"/>
</p>

---

# 📫 Connect With Me

<p align="center">
  <a href="mailto:manisankar.divi@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<p align="center">
  <a href="mailto:manisankar.divi@gmail.com">
    manisankar.divi@gmail.com
  </a>
</p>

---

<p align="center">
  <b>⚙️ Automate • ☁️ Scale • ☸️ Orchestrate • 🤖 Train • 🚀 Deploy • 📊 Observe • 🔄 Improve</b>
</p>
