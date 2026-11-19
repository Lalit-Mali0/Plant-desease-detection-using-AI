# 🌿 Plant Disease Detection using Deep Learning

**A deep-learning model that takes a photo of a plant leaf and predicts whether it is healthy or which disease it has.** Built so farmers and plant owners can catch problems early, before they spread and cause crop loss.

![Demo](images/demo.gif)

## 📌 At a glance
| | |
|---|---|
| **Problem** | Plant diseases are hard to spot early by eye, and late detection means crop loss |
| **Solution** | An image classifier trained on labelled leaf photos |
| **Input** | A photo of a single leaf (JPG / PNG) |
| **Output** | Predicted disease class, or "healthy" |
| **Accuracy** | 98% ([test / validation] set), up from 85% in the first version |
| **Interface** | Drag-and-drop image upload, built for mobile and desktop |
| **Dataset** | [Dataset name + link, e.g. PlantVillage] · [number] images · [number] classes |

## 🧪 Proof of results

**Accuracy and loss during training**

![Training curves](images/accuracy_curve.png)

**Confusion matrix on unseen images**

![Confusion matrix](images/confusion_matrix.png)

**How accuracy went from 85% to 98%**

| Version | What I changed | Accuracy |
|---|---|---|
| v1 | Baseline model | 85% |
| v2 | [e.g. added data augmentation] | [xx%] |
| v3 | [e.g. tuned learning rate, more epochs] | [xx%] |
| Final | [last change you made] | 98% |

## 🛠️ Tech stack
Python · [TensorFlow / Keras / PyTorch] · [NumPy, Pandas, Matplotlib] · Jupyter Notebook · [HTML/CSS/JS for the upload page]

## ▶️ How to run
1. Clone: `git clone https://github.com/Lalit-Mali0/Plant-desease-detection-using-AI.git`
2. Install: `pip install -r requirements.txt`
3. Open the notebook in the `Plant_Disease_Detection` folder and run all cells

## 📂 What's in this repo
| File | What it is |
|---|---|
| `Plant_Disease_Detection/` | Main project: model training and upload interface |
| `Sentiment_Analysis_.ipynb` | Sentiment analysis notebook |
| `exercise-machine-learning-competitions.ipynb` | Machine learning competition exercise |

## 🔮 Next steps
- [e.g. add more plant species]
- [e.g. deploy it online so anyone can try it]

## 👤 Author
**Lalit Mali** · MCA (AI), Parul University · [LinkedIn](https://www.linkedin.com/in/lalit-mali-313527291) · lalitmali13142@gmail.com
