# DL Project : Human Activity Recognition

# Results

After training, we get the results for both models: GRU and LSTM. See table below
# Table : LSTM and GRU Model Performance

| Model | Trainable Parameters | Validation Accuracy |    Test Accuracy    |
|-------|----------------------|---------------------|---------------------|
| LSTM  | 84,578               | 69.94%              |        82.35%       |
| GRU   | 86,424               | 80.48%              |        83,5%        |

The result of confusion matrix for GRU is demonstrated in Figure 2.

<p align="center">
    <img src="visualization/gru.jpg" alt="visualization/gru.jpg" style="display:block; margin:auto;" />
</p>

                                                Figure 2: confusion matrix for GRU

The result of confusion matrix for LSTM is shown in Figure 3.

<p align="center">
    <img src="visualization/lstm.jpg" alt="visualization/lstm.jpg" style="display:block; margin:auto;" />
</p>
                                                Figure 3: confusion matrix for LSTM