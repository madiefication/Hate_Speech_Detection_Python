# Hate-Speech_Detection
Hate Speech Detection using Machine Learning

![hatespeech](https://github.com/user-attachments/assets/90f3af67-2d86-4056-b8c4-826ba64da516)


---
This project focuses on detecting hate speech in text using a machine learning model. The notebook provides a step-by-step approach to building and evaluating a hate speech detection model using various natural language processing (NLP) techniques.

### Project Structure
- __Data Preprocessing:__ Text data is cleaned and transformed into a format suitable for machine learning models.
- __Feature Extraction:__ The cleaned text is converted into numerical features using techniques like Count Vectorization.
- __Model Training:__ A decision tree classifier is trained to classify text as either "Hate Speech", "Offensive Language", or "Neither".
- __Evaluation:__ The model is evaluated on test data, and performance metrics are provided.
- __Prediction Examples:__ The model is used to predict the category of new text samples.

### Steps to perform Hate-Speech-Detection:
- __Data Cleaning:__ Run the cells related to text cleaning to prepare your data for feature extraction.
- __Feature Extraction:__ Use Count Vectorizer to convert text into numerical features.
- __Model Training:__ Train the decision tree model using the provided dataset.
- __Model Evaluation:__ Evaluate the model performance on the test set.
- __Prediction:__ Use the trained model to predict the category of new text inputs.

### Results
The model can classify text into three categories:
- __Hate Speech:__ Text that contains hate speech.
- __Offensive Language:__ Text that contains offensive language but is not classified as hate speech.
- __Neither:__ Text that is neither hate speech nor offensive.

### Limitations
- The model's accuracy is highly dependent on the quality and diversity of the training data.
- The decision tree model might not generalize well to unseen data compared to more complex models.

### Conclusion
This project successfully demonstrates the power of machine learning in identifying and categorizing hate speech. By leveraging natural language processing techniques and a decision tree classifier, the model can effectively distinguish between hate speech, offensive language, and neutral content.This approach sets the stage for creating better systems that help make online spaces safer and more welcoming.

### License
This project is licensed under the MIT License.

