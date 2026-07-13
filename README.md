# Hi, I'm Terrance 👋

I'm a grad student and data scientist who likes solving real problems with machine learning and statistics.

## Background

I'm getting my M.S. in Data Science at UVA (graduating August 2026) and have a B.S. in Applied Mathematics from James Madison University. My work spans machine learning, statistical modeling, and fraud detection, with a recent focus on deep learning for audio classification.

Outside of data science, I breakdance - there's something satisfying about both finding patterns in datasets and nailing a new move.

## What I Work With

**Languages:** Python, R, SQL, SAS, LaTeX

**Main tools:** Pandas, NumPy, scikit-learn, PyTorch, Matplotlib, Tidyverse (ggplot2 for R), FastAPI, Git, Jupyter, Azure

**What I focus on:** Machine learning (supervised, deep learning), agentic AI, statistical modeling, feature engineering, data visualization

## Projects I've Worked On

### [Frequency-Based Speech Isolation for Keyword Spotting](https://github.com/tksluangrath/ds6050-audio-projects)
Team research project comparing a CNN and Audio Spectrogram Transformer (AST) for keyword spotting under noisy conditions. We tested three preprocessing strategies (no filtering, bandpass, and spectral gating) across five SNR levels using Google Speech Commands and the MUSAN noise corpus. The CNN consistently outperformed the AST across every configuration (93.42% clean, 81.94% at -5 dB with bandpass). My contributions were the spectrogram conversion pipeline, spectral gating implementation, and several sections of the paper.

### [AURA-ED: AI-Powered Emergency Department Risk Profiling](https://github.com/XinnieMai/AURA-ED)
Course project for DS 5003: Healthcare Data Science. Built a clinical decision-support tool that uses LLMs to synthesize fragmented ED patient data (vitals, labs, and medical history) into structured early risk profiles. The idea came from how much time emergency physicians spend on indirect care tasks rather than actual patient decisions. Uses the Stanford MC-MED dataset (118,385 adult ED visits) from PhysioNet.

### [Oregon Trail Fitness](https://github.com/RichyKim12/Gold-Rush-Fitness)
Built at HoosHack 2026 in the Health and Wellness category. An Oregon Trail-themed iOS fitness tracker that pulls real step data from Apple HealthKit and maps your progress along the trail. I worked on the FastAPI backend and the HealthKit integration — getting live step counts, daily goal tiers, and streak tracking off a physical iPhone (HealthKit doesn't work in simulators, which made development interesting). The app also tracks hydration, party health stats, and trail milestones.

### [Fraud Detection ML Pipeline](https://github.com/tksluangrath/fraud-detection-app)
A fraud-detection pipeline trained on 6.3M+ PaySim transactions, achieving 94% recall and 0.99 ROC-AUC on a severely imbalanced dataset (0.13% fraud). Deployed to Azure ML for training and Azure Container Apps for live serving, with a shared train/serve pipeline so the model behind the API always matches what was validated in training. The bigger challenge wasn't the model itself but the imbalance: at that fraud rate, a model that never flags anything scores 99.87% accurate, so getting to meaningful recall took deliberate tuning.

## Get in Touch

**Author: Terrance Luangrath**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/terranceluangrath/) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:tksluangrath@gmail.com)

---
Feel free to check out my repos or reach out if you want to collaborate on something.
