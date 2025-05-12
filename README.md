# Effortful Retrieval in Artificial Neural Networks

This repository contains experiments inspired by **retrieval-based learning** from cognitive psychology, adapted to **convolutional neural networks (CNNs)**. The goal is to explore how CNNs respond to effortful retrieval conditions such as noise, occlusion, and spaced learning, and whether these effects mimic human memory patterns.

## Experiments

### **Experiment 1: Spaced vs. Massed Learning**
- CNNs trained on 2-label batches.
- Compared **massed retrieval** (immediate evaluation) vs. **spaced retrieval** (delayed evaluation).
- Measured average number of learning periods required to reach an accuracy threshold.
- Includes statistical testing and threshold sweep.

### **Experiment 2: Gaussian Noise Retrieval Difficulty**
- CNNs trained on noisy images and tested on clean images.
- Noise levels: σ = 0.0, 0.1, 0.3, 0.5.
- Tracked learning effort (number of training periods) as a function of retrieval difficulty.

### **Experiment 3: Occlusion Retrieval Difficulty**
- Same structure as Experiment 2, but used occlusion instead of noise.
- Occlusion levels: 0%, 25%, 50%, 75%.
- Measured and visualized how occlusion affects retrieval effort and generalization.

### **Experiment 4: Future Work / Extended Designs**
- Placeholder for additional modifications to the retrieval framework.

## Outputs

Final plots and CSV data from each experiment are saved in:
- `prelimresults/` — rough outputs from exploratory or debug runs.
- `finalresults/` — cleaned outputs.

## How to Run

Open `experiments.ipynb` in Jupyter or Google Colab. All experiments are self-contained and run sequentially with minimal setup. Make sure `torch`, `torchvision`, `numpy`, `scipy`, and `matplotlib` are installed.



