\# Real-Time Sentiment Analysis Using Facial Emotion Recognition (FER)



This project implements a real-time sentiment analysis system using a deep learning model to recognize human emotions from facial expressions. The model is trained on the FER2013 dataset and uses a modified Xception architecture for accurate classification of emotions such as anger, disgust, fear, happiness, sadness, surprise, and neutrality.



---



\## 🔍 Problem Statement



The objective of this project is to build a real-time facial emotion recognition system that can classify the emotion from a given face image. The system uses deep learning to predict emotions, which can be used for applications like mental health monitoring, customer experience analysis, and human-computer interaction.



---



\## ⚙️ System Requirements



\- Python 3.7+

\- Jupyter Notebook / VS Code / Any IDE

\- GPU recommended (for training)



---



\## 📦 Libraries Used



| Library            | Purpose                         |

|--------------------|---------------------------------|

| TensorFlow / Keras | Deep learning and model training|

| NumPy              | Numerical operations            |

| Pandas             | Data manipulation               |

| OpenCV             | Image processing \& webcam input |

| Matplotlib         | Data visualization              |

| sklearn            | Evaluation metrics              |



---



\## 🧠 Algorithm Used



\- Model: Modified \*\*Xception\*\* architecture

\- Dataset: \*\*FER2013\*\*

\- Loss: `categorical\_crossentropy`

\- Optimizer: `Adam`

\- Metrics: `accuracy`



---



\## 📊 Performance



\- Achieved validation accuracy: \*\*~58%\*\*

\- Performance visualized using:

&nbsp; - Accuracy Curve (Train vs. Validation)

&nbsp; - Loss Curve (Train vs. Validation)



---



\## 🖼️ Input \& Prediction



The model takes in 48x48 grayscale images of human faces and classifies them into one of 7 emotions:

\- Anger, Disgust, Fear, Happy, Sad, Surprise, Neutral



---



\## 🚀 How to Run



1\. Clone this repo:

&nbsp;   ```bash

&nbsp;   git clone https://github.com/pardeevpatti08/Sentimental-Analysis

.git

&nbsp;   cd your-repo

&nbsp;   ```



2\. Install dependencies:

&nbsp;   ```bash

&nbsp;   pip install -r requirements.txt

&nbsp;   ```



3\. Run the notebook or the main Python script:

&nbsp;   ```bash

&nbsp;   python emotion\_predict.py

&nbsp;   ```



4\. To test on a new image:

&nbsp;   ```python

&nbsp;   predict\_emotion("path\_to\_image.jpg")

&nbsp;   ```



---



\## 📁 Dataset



\- \[FER2013 Dataset on Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)



---



\## 📌 Importance



Facial emotion recognition can improve user interaction in applications like virtual assistants, smart surveillance, and sentiment-aware interfaces. It also has applications in healthcare, education, and entertainment.



---



\## 🧠 Future Enhancements



\- Improve accuracy using attention mechanisms or transformer-based architectures.

\- Extend to video emotion tracking in real-time.

\- Integrate with web/mobile apps.



---



\## 📎 References



\- Kaggle FER2013 Dataset  

\- Keras Documentation  

\- \[Xception Paper](https://arxiv.org/abs/1610.02357)



---



\## 👨‍💻 Author



\*\*Pardeev Patti\*\*  

GitHub: \[@pardeevpatti08](https://github.com/pardeevpatti08)



---



> 📬 Feel free to fork this project, give it a ⭐️, and contribute!



