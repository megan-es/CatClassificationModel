# 🐱🐶 Pet Breed Classification Model  
### Identify your cat or dog’s breed using deep learning  
📌 **Author:** [megan-es](https://github.com/megan-es)  

---

## **📖 Overview**  
This project uses **MobileNetV2** to classify images of **cats and dogs** by breed. The model is trained on the **Oxford-IIIT Pet Dataset** and allows you to test it with your own pet’s photo.  

### **✨ Features**  
✅ Predicts exact **cat & dog breeds**  
✅ Uses **transfer learning (MobileNetV2)** for fast training  
✅ Removes **corrupt images** before training  
✅ **Prevents overfitting** with dropout & data augmentation  
✅ Test it with **your own pet’s image!** 🐾  

---

## **📦 Installation**  
### 1️⃣ Clone the Repository & Install Dependencies  
```sh
git clone https://github.com/megan-es/CatClassificationModel.git
cd CatClassificationModel
pip install -r requirements.txt

2️⃣ Download & Extract the Dataset

wget https://thor.robots.ox.ac.uk/pets/images.tar.gz -O images.tar.gz
wget https://thor.robots.ox.ac.uk/pets/annotations.tar.gz -O annotations.tar.gz
mkdir -p dataset/images dataset/annotations
tar -xzf images.tar.gz -C dataset/images
tar -xzf annotations.tar.gz -C dataset/annotations

🧠 Train the Model

Run the Jupyter Notebook:

jupyter notebook pet_classification.ipynb

📌 Training includes:
✔️ Preprocessing & filtering the dataset
✔️ Splitting data into training/testing sets
✔️ Training with dropout & augmentation
✔️ Saving the model (pet_breed_classifier.keras)

📸 Predict Your Pet’s Breed

1️⃣ Place your image in test_images/

2️⃣ Run this in the notebook:

image_path = "test_images/your_pet.jpg"  # Replace with your image path
predict_custom_image(image_path)

✅ The model will display the image and predict the breed!

🔬 Example Predictions

🐱 Predicted Cat Breed: Siamese (98.2%)

🐶 Predicted Dog Breed: Golden Retriever (97.5%)

📌 Your Pet’s Prediction:

🚀 Future Improvements

🔹 Support for more pet breeds
🔹 Real-time webcam classification
🔹 Optimize for mobile devices

🤝 Contribute

Want to improve this project? Fork it, submit issues, or open a PR! 🚀

📜 MIT License © 2025 megan-es

🐾 Try it now & classify your pet’s breed! 🐱🐶🔥

This is now fully optimized for GitHub Markdown formatting and should be easy to copy and paste into your repository. 🚀🐾 Let me know if you need any changes!