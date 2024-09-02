### Key Insights from Datasets and Model Training Results

#### Imbalanced Datasets
Imbalanced data can bias the model towards predicting the majority class ("False"). With only 388 "True" and 2,278 "False" in the Churn data, oversampling the minority class can help balance the dataset.

#### Label Encoding
For binary categorical variables like "True/False" or "Yes/No," label encoding converts these categories into numerical values.

#### Normalization (Min-Max Scaling)
Normalization rescales data between 0 and 1, which is beneficial when the data does not follow a normal (Gaussian) distribution.

#### Applying PCA for Dimensionality Reduction
PCA was applied to reduce features from 18 to 13 principal components, capturing 99% of the dataset's information. PCA works best with normalized data.

#### Model Performance Results
- **Random Forest**: Best among traditional models with an accuracy of 98%.
- **Seq2Seq with LSTM**: Best among deep learning models with an accuracy of 98%.

#### Recommendation
Deep Learning models like Seq2Seq with LSTM generally capture complex relationships in data better than traditional models, achieving the highest accuracy of 98%.
