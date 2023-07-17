# Legal Case Outcome Prediction with RoBERTa

This repository contains code for a classifier built using the RoBERTa model from Hugging Face's transformers library. The classifier is used to predict the outcomes of legal cases.

## Dataset

The data for this project consists of legal cases, with each case having the following attributes:

- ID: A unique identifier for each case.
- first_party: The first party involved in the legal case.
- second_party: The second party involved in the legal case.
- facts: A summary of the facts of the legal case.
- first_party_winner: A binary attribute indicating whether the first party won the case (1 indicates a win, 0 indicates a loss). This is the target attribute that the model will predict.

Here's an example of the data:

| ID         | first_party       | second_party       | facts                                | first_party_winner |
| ---------- | ----------------- | ------------------ | ------------------------------------ | ------------------ |
| TRAIN_0000 | Phil A. St. Amant | Herman A. Thompson | "On June 27, 1962, Phil St. Amant... | 1                  |
