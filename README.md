# ♻️ E-Waste Generation Classification 

This project classifies electronic waste images into 10 different categories using deep learning and transfer learning with EfficientNetV2B0. It aims to automate the sorting and identification of e-waste for smarter and faster recycling.

---

## 🚀 Project Highlights

- ✅ Image classification of 10 e-waste categories
- ✅ Transfer Learning using EfficientNetV2B0
- ✅ Data augmentation for model generalization
- ✅ Real-time classification with Gradio UI
- ✅ Training visualization and performance analysis
- ✅ Scalable folder-based dataset structure

---

## 📁 Dataset Structure

e-waste-dataset/
├── train/
├── test/
│   ├── Battery/
│   ├── Mobile/
│   └── ...
├── val/
│   ├── Battery/
│   ├── Mobile/
│   └── ...


Each folder contains labeled images of different e-waste items such as PCBs, cables, batteries, etc.

---

## 📌 Classes

- Battery
- Mobile
- PCB
- Charger
- Keyboard
- Mouse
- Laptop
- Monitor
- Cable
- Remote

---

## 🛠️ Tools & Technologies Used

| Category           | Tools/Frameworks                             |
|--------------------|----------------------------------------------|
| Language           | Python 3.x                                    |
| Deep Learning      | TensorFlow, Keras                             |
| Pretrained Model   | EfficientNetV2B0 (ImageNet weights)           |
| Visualization      | Matplotlib, Seaborn                           |
| Web UI             | Gradio                                        |
| Data Augmentation  | tf.keras.layers (Flip, Zoom, Rotation, etc.) |

---

## 📊 Model Performance

- Optimizer: `Adam` with LR scheduling
- Loss Function: `Sparse Categorical Crossentropy`
- Accuracy: > 90% (on test set)
- Evaluation: Confusion matrix, classification report

---

## 🧪 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/indrasensingh823/E-Waste-Generation-Classification.git
cd E-Waste-Generation-Classification

```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
Or manually install:
```bash
pip install tensorflow gradio matplotlib seaborn scikit-learn pillow
```
### 3. Run the Notebook
```bash
jupyter notebook e-waste-classification.ipynb
```
### 4. Launch Gradio Interface
```bash
iface.launch(share=True)
```
## Future Enhancements
- Add image preprocessing pipeline outside notebook
- Integrate with Streamlit or Flask for deployment
- Use cloud storage for dataset
- Add more waste categories for fine-grained classification

## 🧑‍💻 Developed By

**🎓 Name:** Indrasen Singh  
**📘 Course:** B.Tech – Computer Science and Engineering 
**🏛️ Institute:** Veer Bahadur Singh Purvanchal University, Jaunpur, Uttar Pradesh  
**📫 Email:** [indrasensingh770@gmail.com](mailto:indrasensingh770@gmail.com)  
**🌐 GitHub:** [github.com/indrasensingh823](https://github.com/indrasensingh823)

---
_"Committed to building smart solutions with AI & ML."_ 🚀





