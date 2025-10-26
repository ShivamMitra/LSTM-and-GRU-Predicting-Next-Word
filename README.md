# LSTM-and-GRU-Predicting-Next-Word
A hands-on project demonstrating next-word prediction using Recurrent Neural Networks (RNNs) — specifically the Long Short‑Term Memory (LSTM) and Gated Recurrent Unit (GRU) architectures — implemented in Python with Jupyter Notebooks.

## Table of Contents
- [About](#about)  
- [What’s Included](#whats-included)  
- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [Dependencies](#dependencies)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)  

## About  
In this project, you will explore how to build and train RNN-based models to **predict the next word** in a sequence of text. Key focus areas include:  
- Preprocessing text sequences, tokenisation, and sequence generation  
- Building an LSTM model to learn word-level dependencies  
- Building a GRU model as an alternative recurrent architecture  
- Comparing performance and insights between LSTM vs. GRU for next-word prediction  
- Providing a ready-to-use notebook for experimentation and extension  

This project is ideal if you are learning Natural Language Processing (NLP), sequence modelling, or deep learning architectures for text generation and language modelling. Resources and tutorials show how next-word prediction is a core task in language modelling. 

## What’s Included  
Here’s what you’ll find in the repository (adjust if necessary):  
- `next_word_prediction_lstm.ipynb` — Notebook implementing next-word prediction using LSTM  
- `next_word_prediction_gru.ipynb` — Notebook implementing next-word prediction using GRU  
- `data/` — Placeholder folder (or actual) containing text dataset(s) used for modelling  
- `models/` — (Optional) Folder to save trained model weights/checkpoints  
- `utils.py` — Helper functions for preprocessing, tokenisation, sequence creation  
- `requirements.txt` — Python dependencies  
- `README.md` — This file  

## Getting Started  
To get up and running:

1. Clone the repository:  
   ```bash
   git clone https://github.com/ShivamMitra/LSTM-and-GRU-Predicting-Next-Word.git
   cd LSTM-and-GRU-Predicting-Next-Word

2. (Recommended) Create a Python virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate

3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
Open one of the notebooks (next_word_prediction_lstm.ipynb or next_word_prediction_gru.ipynb) and follow the cells.

## Usage
- Run the notebook step by step: data loading, preprocessing, model building, training, evaluation, and prediction.
- Change hyperparameters: sequence length, embedding size, recurrent layer units, batch size, number of epochs.
- Try using your own text corpus instead of the provided dataset to experiment with different domains.
- Compare LSTM vs GRU in terms of training speed, accuracy, loss curves, and qualitative predictions of “next word”.

## Dependencies
Typical Python packages used in this project:
- numpy
- pandas
- tensorflow / keras
- matplotlib / seaborn (for visualisations)
- jupyter
- scikit-learn (optional for evaluation/preprocessing)
You can fine-tune exact versions in requirements.txt for reproducibility.

## Project Structure
LSTM-and-GRU-Predicting-Next-Word/
│
├── data/                      ← dataset(s) used for training
├── models/                    ← saved trained model files (optional)
├── utils.py                   ← helper functions for preprocessing etc.
├── next_word_prediction_lstm.ipynb  ← main notebook for LSTM approach
├── next_word_prediction_gru.ipynb   ← notebook for GRU approach
├── requirements.txt           ← python dependencies
└── README.md                  ← this file

## Contributing
Contributions are very welcome! Feel free to open an Issue if you encounter bugs or want to request new features — for example:
- Additional dataset support
- Adding word-embeddings (e.g., GloVe, Word2Vec)
- Exploring bidirectional RNNs, attention mechanisms

Extending to next-sentence prediction or larger language models
To contribute:
- Fork the repository
- Create a new branch: git checkout -b feature-xyz
- Make your changes and commit: git commit -m "Add …"
- Push to your branch: git push origin feature-xyz
- Open a Pull Request with a clear description of your changes.

## License
This project is licensed under the MIT License (or whichever you prefer) — see the LICENSE file for details.
