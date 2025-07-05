# Violence Detection using CNN + LSTM 🚨

This project is a complete deep learning pipeline to detect violence in videos using frame sequences. It uses a CNN + LSTM model trained on the [RWF-2000 dataset](https://www.kaggle.com/datasets/vulamnguyen/rwf2000) and includes adversarial testing, real-time alerts, and environmental robustness checks.

---

## 🧠 Features
- CNN + LSTM model for spatiotemporal video analysis
- Frame extraction & classification
- Adversarial testing (occlusion, sports, clothing, motion)
- Environmental testing (brightness, contrast, blur, nighttime)
- Speed robustness (slow/fast motion)
- Telegram bot alert system
- Training visualization & evaluation reports

---

## 📁 Project Structure
violence-detection-cnn-lstm/
├── dataset/               # Raw and organized video data
├── frames/                # Extracted frames from videos
├── models/                # Saved models (.h5) and training logs
├── scripts/               # All Python scripts (training, testing, etc.)
├── logs/                  # TensorBoard logs or training logs
├── results/               # Evaluation outputs, graphs, predictions
├── README.md              # Project overview and usage instructions
├── requirements.txt       # All required dependencies
├── .gitignore             # Files/folders to be excluded from Git






---

## 🔧 Requirements
- Python 3.8+
- TensorFlow, OpenCV, Matplotlib, NumPy
- Kaggle CLI
- Telegram Bot API

---

## 🚀 Quick Start
1. Clone the repo
2. Set up Kaggle credentials
3. Run `scripts/extract_frames.py`
4. Train using `scripts/train_model.py`
5. Test with `scripts/test_model.py`

---

## 📜 License
MIT License © Abhinand S
