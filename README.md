
# Joy-o-Meter 🎉 — Predicting Happiness Intensity with NLP

This project implements a simple linear neural network that predicts the **happiness intensity** of a text using pretrained language embeddings. The work leverages PyTorch, Hugging Face's `transformers`, and other essential tools to build a Joy-o-Meter that quantifies how happy a piece of text sounds.

> **Course:** CS224 — Spring 2025  
> **Assignment:** Homework 1 — Joy-o-Meter  
> **Author:** Ranjitha Narasimhamurthy  

---

## 📝 Project Description

The Joy-o-Meter analyzes text samples and predicts the **happiness score** based on pretrained language representations. You'll:

✅ Use Hugging Face Transformers for pretrained language models  
✅ Extract text embeddings  
✅ Implement a simple linear neural network in PyTorch  
✅ Fit model weights using a closed-form analytic solution  
✅ Visualize predictions and evaluate performance  

---

## 📁 Files

| File                | Description                                  |
|---------------------|----------------------------------------------|
| `Joy_o_meter.ipynb` | Main Jupyter notebook with full implementation and explanation |
| `README.md`         | Project overview and setup instructions |

---

## ⚡ Requirements

Make sure to have the following installed:

```bash
pip install torch transformers pandas matplotlib scikit-learn
```

Alternatively, you can run the notebook on **Google Colab**, which has most required packages pre-installed.

---

## 🚀 How to Run

### Run Locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/joy-o-meter.git
   cd joy-o-meter
   ```

2. Install dependencies:
   ```bash
   pip install torch transformers pandas matplotlib scikit-learn
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Joy_o_meter.ipynb
   ```

4. Follow the instructions in the notebook to:
   - Load data
   - Extract embeddings
   - Train the linear model
   - Evaluate and visualize results

---

### Run on Google Colab:

1. Open the notebook in Colab:
   - Upload `Joy_o_meter.ipynb` to [Google Colab](https://colab.research.google.com)
   
2. Run the cells step by step — Colab comes pre-installed with most required packages.

---

## 📊 Example Output

The notebook generates visualizations and metrics showing how well the model predicts happiness intensity for given text samples.

---

## 📚 Dependencies

- [PyTorch](https://pytorch.org/)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/)

---

## 🙌 Acknowledgments

- Stanford CS224 Course Materials  
- Hugging Face for providing state-of-the-art NLP tools  

---

## ⚠️ Disclaimer

This project is intended for educational purposes as part of CS224 coursework. Do not use this as a real-world happiness prediction tool without further validation.
