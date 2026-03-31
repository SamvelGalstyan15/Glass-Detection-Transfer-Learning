👓 Glass Detection (Transfer Learning)

A binary classifier designed to detect whether a person is wearing glasses. Built with MobileNetV2 and optimized for real-world deployment.

 🌟 Key Features:
    High Performance: Achieved 90%+ validation accuracy despite a small dataset.
    On-the-fly Augmentation: Integrated data augmentation layers directly into the model architecture to prevent overfitting.
    Production Ready: Built-in normalization layer means you can feed raw images directly to the model.

🛠 Tech Stack:
    Framework: TensorFlow / Keras
    Base Model: MobileNetV2 (Pre-trained on ImageNet)
      Techniques: Transfer Learning, Image Augmentation, Normalization Layers.

📊 Model Architecture:
The model leverages the pre-trained feature extractor of MobileNetV2, followed by custom Global Average Pooling and Dense layers for binary classification (Glasses / No Glasses).



⚙️ Installation

To set up the environment and install all dependencies, run the following commands:

```bash
 Create virtual environment
   python -m venv venv

 Activate virtual environment
   On Windows:
     venv\Scripts\activate
   On macOS/Linux:
     source venv/bin/activate

 Install dependencies
   pip install -r requirements.txt
```


    

Results:


<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/30faf334-3305-45b3-a0dd-96771643eb33" />



<img width="679" height="132" alt="image" src="https://github.com/user-attachments/assets/f0b6fe64-8bec-43f1-be96-221e8b2c93ab" />

