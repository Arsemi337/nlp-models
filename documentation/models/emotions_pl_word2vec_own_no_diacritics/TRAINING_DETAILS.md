# Training details

Word2Vec trained with our own emotion dataset but with diacritics removed

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch | Fitting time | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                |                                Notes                                 |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:--------------------------------------------------------------------:|
|      1       |     40k      |     80%     |    10%    |    10%     |     16     |   10   |     3      |     N.A      |     0.3956     |   1.4464   |    0.3753    |  1.5287  |    0.3660     |  1.5180   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |                                  Ok                                  |
