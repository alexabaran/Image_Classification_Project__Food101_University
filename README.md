# 🍔 Food101 Image Classification Project

> ⚠️ **Note:** All Jupyter notebooks are written in **Polish**, as this project was created as a final assignment for the course **"Sztuczna inteligencja w chmurze"** (Artificial Intelligence in the Cloud).

---

## 🎓 Project Topic

The goal of the project was to build an application based on artificial intelligence in the cloud.  
The task involved training a machine learning model to recognize food categories from images using the **Food101 dataset**, and creating a simple web application to interact with the trained model using **Gradio**.

The project includes:
- Preparing and training models using cloud tools (Google Colab)
- Comparing performance of two different models
- Deploying a simple image classification interface via Gradio

---

## 🧠 Project Goals

- Train two different neural network models on the Food101 dataset  
- Compare their performance  
- Build an interactive image classification app  
- Use **Gradio** to make the model accessible and easy to use  

---

## 📁 Project Structure

├── Food101_model.ipynb       # Notebook for training and comparing two models (Polish)
├── Food101_app.ipynb         # Notebook with a Gradio web app for food prediction (Polish)
├── mobilenet_food101.pth     # Saved MobileNet model trained on Food101 dataset
├── requirements_model.txt    # Required packages for training
├── requirements_app.txt      # Required packages for running the app


## 🏗️ What Has Been Done

### ✅ Model Training (`Food101_model.ipynb`)

- Loaded the **Food101** dataset from TensorFlow Datasets.
- Built and trained **two models**:
  - A **custom CNN (Convolutional Neural Network)**
  - A **MobileNet** model (pre-trained and fine-tuned)
- Compared the performance of both models based on accuracy and training time.
- Saved the trained MobileNet model to a `.pth` file for later use.

### 🌐 Web App (`Food101_app.ipynb`)

- Created an interactive app using **Gradio**.
- The app allows users to upload an image and instantly get a prediction of the food category.
- The trained MobileNet model is loaded and used in the app for predictions.

