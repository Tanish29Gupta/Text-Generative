# Text Generator using LSTM

## Overview
This project demonstrates a Text Generation model using Long Short-Term Memory (LSTM) neural networks. The goal is to predict and generate coherent text based on given sequences of text data. The model has been fine-tuned on a dataset of Medium article titles to ensure accurate and meaningful predictions.

## Key Features
• Bidirectional LSTM: Used to capture context from both directions in sequences, improving accuracy.

• Embedding Layer: Converts text sequences into dense vector representations for efficient learning.

• High Accuracy: Achieved 91.96% accuracy on validation data.

• Dataset: Preprocessed 48,461 sequences from Medium article titles.

## Requirements
Ensure the following dependencies are installed:

• Python 3.8+

• TensorFlow 2.8+

• NumPy

• Pandas

• Matplotlib

Install the dependencies using the following command:

pip install -r requirements.txt

## Files Included
• TextGen_code.ipynb : Jupyter notebook with the implementation of the text generator model.

• Dataset: A preprocessed dataset of Medium article titles (available upon request).

## Usage
1. Clone the repository:

   git clone https://github.com/username/Text-Generator-LSTM.git cd Text-Generator-LSTM

2. Install dependencies:

   pip install -r requirements.txt

3. Open the Jupyter Notebook to train and test the model:
   
   jupyter notebook TextGen_code.ipynb

4. Follow the notebook instructions to:
   
   • Preprocess text data.
   
   • Train the LSTM Model.

   • Generate text sequences.

## Result
The model achieves 91.96% accuracy on validation data and generates coherent Medium article titles based on input sequences. The use of Bidirectional LSTMs significantly enhances context understanding.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve this repository.

## License
This project is licensed under the MIT License.

