# 🌿 Leaf Health Predictor

Leaf Health Predictor is a lightweight desktop application that uses a trained deep learning model to classify plant leaf images as either **Healthy** or **Unhealthy**.  
It provides an intuitive drag-and-drop interface built with Tkinter and performs real-time predictions using a Keras model.

This project is designed to assist users—especially those in agriculture or plant research—in analyzing leaf health quickly and offline using artificial intelligence.

---

## 🖥️ Features

- Drag-and-drop interface for easy image input  
- Real-time prediction using a pre-trained `.h5` model  
- Binary classification: Healthy vs. Unhealthy  
- Clean and modern UI with custom dark background  
- Displays prediction label and confidence score instantly

---

## 🚀 Getting Started
📁 **Note for contributors:**  
This repository uses [Git LFS](https://git-lfs.github.com/) to store the `model.h5` file.  
To clone and use the model file properly, make sure Git LFS is installed on your system before running `git clone`.

**1. Clone the repository**

`git clone https://github.com/your-username/LeafHealthPredictor.git`  
`cd LeafHealthPredictor`

**2. Install dependencies**

Install required Python packages using:

`pip install -r requirements.txt`

Make sure you have Python 3.7+ installed.

**3. Run the application**

`python app.py`

Then drag and drop a leaf image into the window to get a prediction.

---

## 🧠 Training the Model (Optional)

If you'd like to train the model yourself, make sure your dataset is structured as follows:

```
dataset/
├── Train/
│   ├── Healthy/
│   └── Unhealthy/
└── Validation/
    ├── Healthy/
    └── Unhealthy/
```

Then run:

`python training.py`

The trained model will be saved as `model.h5`.

---

## 📈 Example Output

`'leaf_12.jpg': Unhealthy (92.34%)`

---

## 🔮 Future Improvements

This project can be further developed to:

- Classify specific plant diseases (e.g. rust, mildew, blight)  
- Add batch image processing  
- Deploy to mobile or web platforms  
- Visualize model attention with techniques like Grad-CAM  
- Integrate with automated decision systems for smart agriculture

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

- Built using TensorFlow and Keras  
- GUI powered by Tkinter and `tkinterdnd2`  
- Background color inspired by Encycolorpedia (`#293133`) 🌘
