# Next-Word Prediction Using LSTM

## Project Overview
This project predicts the next word based on the words entered by a user. It uses an LSTM (Long Short-Term Memory) neural network implemented with TensorFlow and Keras.

## Objective
To develop a basic next-word prediction system similar to the word suggestions provided by smart keyboards.

## Dataset
- Text source: *The Adventures of Sherlock Holmes*
- Prepared sentences: 4,901
- Vocabulary size: 8,615

## Technologies Used
- Python
- Google Colab
- TensorFlow and Keras
- NumPy
- Scikit-learn

## Methodology
1. Load and clean the text dataset.
2. Split the text into sentences.
3. Tokenize words and create a vocabulary.
4. Generate input-target sequences.
5. Split the data into training and testing sets.
6. Build an Embedding-LSTM-Dropout-Dense model.
7. Train the model for 10 epochs.
8. Evaluate the model and predict the top five next-word suggestions.

## Model Results
- Test loss: 6.0505
- Top-1 accuracy: 13.40%
- Top-5 accuracy: 30.85%

## Example
Input: `he looked at`

Top prediction: `the` — 52.45%

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Run the notebook cells in order.
3. Train the model and test your own phrases.

## Conclusion
The project demonstrates next-word prediction using an LSTM neural network. The results can be improved with a larger, more diverse dataset and further model tuning.
