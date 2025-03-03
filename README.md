# Fake-Beef-Detection-Using-Lightweight-Convolutional-Neural-Networks

This repository contains the implementation of a lightweight convolutional neural network (CNN) model for detecting fake beef. The model is optimized for efficiency while maintaining high accuracy in distinguishing real beef from substitutes like pork and buffalo meat.

## 📌 Features
- Uses **MobileNetV2** for lightweight and efficient classification.
- Preprocessing with **HSV color space** and edge detection.
- Trained on a dataset containing real and fake beef images.
- Achieves **>90% accuracy** on the test set.
- Real-time detection capability.

## 🛠 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fake-beef-detection.git
   cd fake-beef-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Dataset
The dataset consists of images of real and fake beef collected from various sources (Kaggle, iStock, and real-world samples). If you need access, download it from **[Google Drive Link]** (replace with actual link).

## 🚀 Training the Model
Run the following command to train the model:
```bash
python train.py --epochs 50 --batch_size 32
```

## 🔍 Inference
To test the model on a new image:
```bash
python detect.py --image sample.jpg
```

## 📄 Research Paper
For a detailed explanation of the methodology, refer to the [research paper](./paper.pdf).

## 📝 TODO
- [ ] Improve dataset diversity
- [ ] Optimize model for embedded systems
- [ ] Publish trained model weights

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Feel free to fork this repository and submit pull requests! Contributions are welcome.
