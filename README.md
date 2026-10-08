# Robair Farag — Applied AI & Systems Engineer

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat&logo=nvidia&logoColor=white)

Applied AI and systems engineer focused on getting models and software to run on real hardware: edge deployment on NVIDIA Jetson, ML infrastructure, and autonomous systems. M.S. in Applied Artificial Intelligence, University of San Diego (2026).

**Focus areas:** Edge AI deployment · Real-time embedded software · ML infrastructure · Autonomous systems · Anomaly detection

> Some of my embedded and autonomous-systems work (real-time C++/Python on Jetson) was done under NDA and is not shown here.

---

## 🚀 Projects

| Project | Description | Stack |
|---|---|---|
| [**PEREGRINE**](https://github.com/Robair26/PEREGRINE) ([live](https://peregrine.bitshadow.dev)) | Aerospace object detection: a Capsule Network (Hinton 2017 dynamic routing, implemented from scratch) benchmarked against ResNet on 68,000 DIOR aerial images. Exported to ONNX and running at 2.65 ms on a Jetson Orin Nano, with Prometheus/Grafana monitoring and KS-test drift detection. | PyTorch, ONNX, Jetson, FastAPI, MLflow, Prometheus, Grafana, Docker, K3s |
| [**Adaptive Anomaly Monitoring**](https://github.com/Robair26/adaptive-anomaly-monitoring) | Capstone: time-series anomaly detection comparing a rolling Z-Score, Isolation Forest, and an LSTM Autoencoder on four NAB datasets, plus a hybrid detector that flags an anomaly only when both ML models agree. | PyTorch, scikit-learn |
| [**AXIOM**](https://github.com/Robair26/AXIOM) ([live](https://axiom.bitshadow.dev)) | Edge-cloud hybrid AI assistant: voice interaction, tool calling, multi-agent debate, and a web interface. Runs on a laptop, a cloud server, and a Jetson Orin Nano. | Python, Flask, Docker, K3s, Claude API, Prometheus |
| [**BitShadow**](https://bitshadow.dev) ([code](https://github.com/Robair26/bitshadow-phishing-detector)) | Phishing URL detector with ML classification and rule-based scoring. | FastAPI, Streamlit, ML |
| [**Shadow Tribunal**](https://github.com/Robair26/shadow-tribunal) | Local LLM inference app running models privately. | Ollama, FastAPI, Python |
| [**Signal Sunday Bot**](https://github.com/Robair26/signal-sunday-readings-bot) | Automation bot that delivers weekly readings by message. | Python |

---

## 🔬 PEREGRINE results

I implemented dynamic routing by agreement from scratch and compared a CapsNet with a ResNet baseline on 68,000 aerial images from DIOR.

- ResNet has higher overall accuracy: 89.97% vs 82.99% for CapsNet.
- In a rotation test, CapsNet scored higher than ResNet at all 6 angles (single run), with the largest gap of +8.0 points at 60°. Both models degrade sharply at large rotations.
- Edge deployment: 12.2 MB ONNX model at 2.65 ms inference on a Jetson Orin Nano.

---

## 🛠️ Tech Stack

**ML:** PyTorch · scikit-learn · ONNX · TensorRT · computer vision · time-series anomaly detection · LLM applications

**MLOps:** MLflow · Prometheus · Grafana · drift detection · GitHub Actions · GitLab CI/CD

**Systems:** Linux · Docker · Kubernetes (K3s) · FastAPI · Flask · REST APIs · JWT

**Embedded / edge:** NVIDIA Jetson (ARM) · C/C++ · NVIDIA Nsight Systems · ROS · ArUco pose estimation

**Cloud:** AWS (EC2, S3, CloudWatch, Athena) · DigitalOcean · Cloudflare

**Languages:** Python · C/C++ · Bash · SQL · Java · JavaScript

---

## 📜 Certifications

Red Hat OpenShift & Kubernetes · AWS Cloud Foundations · Google Cybersecurity · Google Data Analytics · Cisco Network Automation

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/robairfarag)
[![PEREGRINE Live](https://img.shields.io/badge/PEREGRINE-Live_Demo-76B900?style=flat)](https://peregrine.bitshadow.dev)
[![AXIOM Live](https://img.shields.io/badge/AXIOM-Live_Demo-00d4ff?style=flat)](https://axiom.bitshadow.dev)
