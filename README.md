# Hi, I'm Rafael

M.Sc. student in **Image Analysis and Machine Learning** at Uppsala University (Sep 2025 – Jun 2027), building on a B.Sc. in **Data Science** from NOVA IMS (Lisbon) and an Erasmus semester at Lund University. I work on **computer vision and deep learning**, and I'm currently a research intern at **Furhat Robotics** (Stockholm) on multimodal perception. Portuguese, based between Stockholm and Uppsala.

## What I've been working on

**Computer vision & medical imaging**

- **Semi-supervised distillation for multimodal cancer-cell classification** — on a hard, patient-disjoint 12-patient Kaggle benchmark, I grew the effective training set with hard pseudo-labels (Lee 2013) then soft-target knowledge distillation (Hinton 2015) on a dual EfficientNet-B0 with AdaBN — the change that mattered more than scaling the network. Full LaTeX methodology write-up and an honest failure analysis. → [multimodal-microscopy-distillation](https://github.com/rafallex/multimodal-microscopy-distillation)
- **Vision Transformers for emotion recognition** — fine-tuned ViT-Base on RAF-DB for facial-emotion recognition, feeding the dialogue layer of a Furhat social-robot tutor (group project). → [furhat-emotion-tutor](https://github.com/rafallex/furhat-emotion-tutor)
- **Classical image analysis from the toolbox up** — hand-written histogram operations, Otsu and iterative thresholding, colour segmentation, spatial filtering, multispectral Landsat imagery, and rigid image registration (intensity- and feature-based) in MATLAB. → [classical-image-analysis](https://github.com/rafallex/classical-image-analysis)

**Machine learning & statistics**

- **Time-to-detection in microfluidic bacterial growth** — benchmarking Gaussian processes, changepoint detection, bootstrap, HMMs, and functional data analysis to find the earliest reliable call that an antibiotic is working. → [bacterial-growth-detection](https://github.com/rafallex/bacterial-growth-detection)
- **Gradient-boosted pass-danger model** — flags passes likely to create a shot from StatsBomb event data and ranks passers across five leagues, with pitch-control and circular-statistics run analysis. → [football-pass-danger-model](https://github.com/rafallex/football-pass-danger-model)
- **Deep learning from scratch** — a NumPy-only fully-connected network with hand-written backprop, then a PyTorch progression to a residual CNN on MNIST. → [mnist-from-scratch-to-resnet](https://github.com/rafallex/mnist-from-scratch-to-resnet)

**LLMs, multimodal & human–robot interaction**

- **Furhat social robot for student mental-health check-ins** — a group HRI study (1MD043) testing whether empathetic vs. neutral robot behaviour changes how students perceive a wellbeing check-in (between-subjects, *n* = 23, RoPE + Godspeed scales); I contributed to the experimental design and analysis and added a Gemini LLM backend. → [HRI_Furhat](https://github.com/rafallex/HRI_Furhat)
- **Multimodal mushroom-ID chatbot** — a Gradio app that reads a photo, extracts a strict-JSON description, and answers as a mycology assistant with a safety guard against foraging advice; runs on Google Gemini or a Hugging Face pipeline (Llama 3.1 + BLIP captioning). → [mushroom-id-chatbot](https://github.com/rafallex/mushroom-id-chatbot)
- **LoRA fine-tuning of Qwen3-0.6B** — a small-LLM SFT experiment on a BeautifulSoup-scraped corpus, with a Gradio base-vs-fine-tuned comparison. → [greek-mythology-chatbot](https://github.com/rafallex/greek-mythology-chatbot)

## Tools I reach for

**Languages:** Python (daily), SQL, R, MATLAB, Bash
**Deep learning & computer vision:** PyTorch, Hugging Face Transformers, timm; Vision Transformers, CNNs, transfer learning, knowledge distillation, semi-supervised learning, PEFT / LoRA
**Also:** scikit-learn, scikit-image, NumPy, SciPy, Pandas; Gradio; Git, Jupyter, Kaggle; LLM APIs (OpenAI, Gemini)

## Currently

Research intern at **Furhat Robotics** (Jun – Dec 2026). Looking for **computer-vision, ML / AI engineering, and deep-learning research** roles — and a master's thesis — in Sweden and the EU.

## Reach me

- **Email:** rafaeltproenca@gmail.com
- **LinkedIn:** [linkedin.com/in/rafael-alexandre-proenca](https://linkedin.com/in/rafael-alexandre-proenca)
