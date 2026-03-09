# 🍓 Fruit Image Classification

This project is a simple deep learning model that can recognize different fruits from images. The idea is to train a Convolutional Neural Network (CNN) so that it learns the visual patterns of fruits like color, shape, and texture, and then predicts which fruit is present in an image.

I built this project to explore how image classification works using **TensorFlow and Keras**, and to understand how neural networks process visual data.

# 📌 What this project does

The model takes an image of a fruit and predicts which fruit it is.
For example, if we input an image of a banana, the model should classify it as **banana**.

Behind the scenes, the model learns features like:

* Color patterns
* Shape of the fruit
* Surface texture

These features help the neural network differentiate between fruits.

# 🛠 Tools and Libraries Used

This project was built using:

* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Matplotlib**
* **PIL (Python Imaging Library)**
* **Kaggle Notebook**

# 📂 Project Structure

```text
fruit-image-classification/
│
├── fruit_classifier.ipynb   # Main notebook containing the model and training code
├── dataset/                 # Fruit image dataset
│
└── README.md                # Project documentation
```

# 📊 Dataset

The model was trained on a dataset of fruit images where each folder represents a fruit category.

Example structure:

```
dataset/
   apple/
   banana/
   orange/
   mango/
```

Each folder contains many images of that particular fruit.
This helps the model learn what makes each fruit visually different.

# 🧠 How the Model Works

The project uses a **Convolutional Neural Network (CNN)**, which is commonly used for image classification.

The model generally follows these steps:

1. Load and preprocess the images
2. Resize images to a fixed size
3. Pass images through convolution layers to extract features
4. Use pooling layers to reduce complexity
5. Use dense layers to classify the fruit

Finally, the model outputs the predicted fruit category.

# ▶️ Running the Project

1. Clone the repository

```bash
git clone https://github.com/yourusername/fruit-image-classification.git
```

2. Install the required libraries

```bash
pip install tensorflow numpy matplotlib pillow
```

3. Open and run the notebook

```
fruit_classifier.ipynb
```

Run all the cells to train and test the model.

---

# 📈 Results

After training, the model is able to correctly classify fruit images with good accuracy on the validation dataset.

The training process also shows:

* Accuracy improvement over epochs
* Loss decreasing as the model learns

# 🚀 What I Learned

While building this project, I learned:

* How **CNNs work for image classification**
* How to preprocess image datasets
* How to train and evaluate deep learning models
* How to run machine learning experiments using Kaggle notebooks

# 🔮 Future Improvements

Some things that could make this project better:

* Using **transfer learning** (ResNet, MobileNet, EfficientNet)
* Adding more fruit categories
* Building a small **web app to upload fruit images**
* Deploying the model

# 🤝 Contributions

If you'd like to improve the project or experiment with the model, feel free to fork the repository and try your own ideas.

