### Bank-Note-Authentication

Banknotes are one of the most important assets of a country. Some miscreants introduce fake notes which bear a resemblance to original note to create discrepancies of the money in the financial market. It is difficult for humans to tell true and fake banknotes apart especially because they have a lot of similar features. Fake notes are created with precision, hence there is need for an efficient algorithm which accurately predicts whether a banknote is genuine or not.

In this we used machine learning techniques to evaluate authentication of banknotes. Supervised learning algorithms such as  Decision Tree Classifier algorithms is used for differentiating genuine banknotes from fake ones.

### Data Set Information:

Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

### EDA

Most of the data cleaning is done at the time of creating the dataset.There is no null values in the dataset. So it makes easier to perform the EDA.

### Model selection

Checked with differnent Classification algorithm and found that Decision Tree works the best.

### Model evaluation

Evaluation Metrics such as Accuracy Score and Confusion Matrix are used to check the strength of the model.
