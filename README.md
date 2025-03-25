# Music Generation with LSTM Neural Networks

This project delves into automatic music generation using Recurrent Neural Networks (RNN) with Long Short-Term Memory (LSTM). The primary goal is to develop a model capable of learning musical patterns from MIDI files to generate coherent and innovative compositions.

## 📁 Notebook Structure
* **Note Extraction:** Loading and parsing MIDI files to extract distinct notes and chords.

* **Data Preprocessing:** Converting notes into a numerical representation suitable for model training.

* **Dataset Preparation:** Creating input sequences (length 40) and targets for prediction.

* **LSTM Model:** Building and training the model using PyTorch.

* **Music Generation:** Creating new MIDI sequences based on the trained model.

## 📦 Requirements and Dependencies

* Python 3.x  
* Docker  
* torch  
* music21  
* sklearn  

## 🚀 How to Use the Project

Clone the repository and place MIDI files in the `dataset/` folder.

Install dependencies with:

```bash
pip install -r requirements.txt
```

Run the module.ipynb notebook to:

- Extract notes from MIDI files.

- Perform data preprocessing.

- Train the LSTM model.

- Generate new music.

# 🔊 Output
Generated MIDI files are saved in the img/ directory as output.mid.
