# 🐱🐶 Cat vs Dog Image Classification using CNN (PyTorch)

A Deep Learning project built using **PyTorch** to classify images of cats and dogs with high accuracy using a custom Convolutional Neural Network (CNN).

## 🚀 Project Highlights

* Built a custom CNN architecture from scratch
* Applied **Batch Normalization**, **Dropout**, and **Data Augmentation**
* Used **Adam Optimizer** with **Weight Decay** for better generalization
* Visualized:

  * Training vs Validation Loss
  * Confusion Matrix
  * Classification Report
* Achieved **88.34% Test Accuracy**

---

## 🛠️ Tech Stack

* Python
* PyTorch
* Torchvision
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Model Architecture

The CNN contains:

* 4 Convolutional Blocks
* Batch Normalization
* ReLU Activation
* MaxPooling Layers
* Fully Connected Layers with Dropout

---

## 📈 Results

### Final Performance

* **Train Accuracy:** 86.88%
* **Validation Accuracy:** 86.52%
* **Test Accuracy:** 88.34%

### Confusion Matrix

* Cat correctly predicted: **555**
* Dog correctly predicted: **506**

The model generalized well with balanced performance across both classes.

---

## 📌 Key Learning Outcomes

* Understanding CNN architecture design
* Preventing overfitting using dropout & augmentation
* Working with image datasets using ImageFolder & DataLoader
* Evaluating models using confusion matrix and classification report
* Training deep learning models on GPU with PyTorch

---

## 🔗 Future Improvements

* Hyperparameter Tuning
* Deploying using Streamlit or Flask
* Training on larger datasets

⭐ If you like this project, feel free to star the repository!
