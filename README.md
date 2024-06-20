# language-translation
English to Yoruba Translation Model
This project demonstrates a simple English to Yoruba translation model using a Bidirectional GRU-based sequence-to-sequence model with TensorFlow/Keras.

Setup
Install dependencies:

pip install numpy tensorflow scikit-learn
Prepare your dataset:

Replace the placeholder sentences in the script with your actual English and Yoruba sentences.
Usage
Train the model:

The script tokenizes the input sentences, pads them, and splits them into training and validation sets.
It builds, compiles, and trains a Bidirectional GRU model.
The trained model is saved to eng_to_yor_translation_model.h5.
Evaluate the model:

Use the evaluate_model function to translate an English sentence to Yoruba with the trained model.
