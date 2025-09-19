# MNIST Handwritten Digit Recognizer

This project implements a **Convolutional Neural Network (CNN)** to recognize handwritten digits from the **MNIST dataset**.  
It is built using **PyTorch** and other data science libraries.

## Project Structure

```
.
├── DigitRecognizer.ipynb   # Jupyter notebook with the full implementation
├── data/                   # Folder containing dataset files (if provided)
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

## Installation

1. Clone this repository or download the files.
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook DigitRecognizer.ipynb
```

## Dependencies

Main libraries used:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- torch
- torchvision

## Dataset

The project uses the **MNIST dataset**, which contains 70,000 handwritten digit images (0–9).  
If not already in the `data/` folder, it will be automatically downloaded by `torchvision`.

## Results

The CNN model achieves high accuracy in classifying handwritten digits.

---

📌 This project is for learning and experimentation purposes.
