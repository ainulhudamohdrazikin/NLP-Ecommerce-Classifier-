# **E-commerce Classifier using NLP**
 ![ecomme](https://github.com/user-attachments/assets/3bbc02a6-8234-4016-893a-508141a0e218)  

This NLP model was trained using nearly 50K word from E-commerce platforms to filter the products into different categories.

## **Descriptions:**
1. **_Objective:_** To categorize specific types of products that are trending in e-commerce platforms using Neutral Language Processing model specifically LSTM.
2. This datasets contain crucial information which might shape the market trends or influence the investment flows.
3. This model using 5000 tokens with 200 output sequence length for the tokenization process.

### *Model Architecture:-*
![model](https://github.com/user-attachments/assets/6f719bc7-15f3-46fe-a0f4-a0fd1eca6ecc)

#### The model consists of 4 main layers which are TextVectorization, Embedding, Bidirectional and Dense. 

## **Results:**

### *Model Score Evaluation:-*
![model_evaluation](https://github.com/user-attachments/assets/aee17bd2-401f-406b-bd88-8ed4c3d97641) 
![F1_score](https://github.com/user-attachments/assets/efaa0c96-4f70-4911-b81d-7d0a930adad3)
#### The model succesfully achieved higher accuracy (F1 value) which nearly 97% with the value of loss quite small, 0.124. 

#### Graph Model Accuracy:-
![Accuracy_Evaluation](https://github.com/user-attachments/assets/42d4d2c9-e35e-4f16-abae-48e0c8731b18)

#### Graph Model Loss:-
![Model_Loss_graph](https://github.com/user-attachments/assets/52c37ae5-0726-43f7-a48f-ad5dac855e06)

### *Training Epoch Accuracy:-*
![epoch_accuracy](https://github.com/user-attachments/assets/3e6355d7-d89e-4e66-9607-af94cc645523)

### *Training Epoch Loss:-*
![tb_loss_graph](https://github.com/user-attachments/assets/94e176e5-5d92-43e9-92ae-e5818a9e2e86)

## **Discussions:**
1. From Dataset there are 4 unique categories which are 'Electronis', 'Household','Books', and 'Clothing&Accessories'.
2. For overall accuracy, there is slightly overfitting for this model due to the limited scope application.
3. For epoch accuracy, can be seen that the model training were stopped before the model could overfit because of the early stopping.
4. For bot epoch and overal loss, this model was overfit even there was early stopping, this might be less the generalization process or there were higher differences distribution between each class that might affected the model to be overfit.

## **Credit:**
The source of the dataset are by Saurabh Shahane from Kaggle.
Check out the dataset by just one click away 😇 :  [Datasets](https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification)
