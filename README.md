# ANN-based-Banking-Churn-Prediction-Model
- This is a machine learning and deep learning based banking churn prediction ANN model.
- Explore the dataset of a fictional bank of 10,000 customers.
- Then predict the customers who are at higher risk of leaving the bank.

## Dataset
![Screenshot from 2020-11-27 13-09-50](https://user-images.githubusercontent.com/43890931/100425992-336e9b80-30b6-11eb-9706-1f9c41ec0241.png)

### Input(Independent/Predictor Variables)
![Screenshot from 2020-11-27 13-10-14](https://user-images.githubusercontent.com/43890931/100427551-a24cf400-30b8-11eb-91d4-8a9cfcb9937e.png)

### Output(Dependent/Target Variable) 
![Screenshot from 2020-11-27 13-10-26](https://user-images.githubusercontent.com/43890931/100427678-cf010b80-30b8-11eb-8d62-fa80bd062bd8.png)
- Its binary type (0 OR 1)
- 0 -> Customer left the bank.
- 1 -> customer stays in the bank.

## Analysis and Accuracy
- The Prediction engine is built over a deep **Artificial Neural Network** backed with **[Keras](https://www.tensorflow.org/guide/keras)**.
- I have achieved an accuracy of around **~85%** on both training and testing data.</br>
- The network is Tuned over **100 epoch** for generating the best possible prediction.
### Few starting epochs...
![Screenshot from 2020-11-27 13-34-45](https://user-images.githubusercontent.com/43890931/100427968-4b93ea00-30b9-11eb-9b12-2b3f4e1fcb28.png)
### Last epochs...
![Screenshot from 2020-11-27 13-39-38](https://user-images.githubusercontent.com/43890931/100427984-52226180-30b9-11eb-9160-454f4bb30816.png)
## Predicted test set results
![Screenshot from 2020-11-27 14-05-51](https://user-images.githubusercontent.com/43890931/100428443-f99f9400-30b9-11eb-8b6d-4ad31b6d8d5d.png)
## Confusion Matrix
![Screenshot from 2020-11-27 14-06-18](https://user-images.githubusercontent.com/43890931/100428463-00c6a200-30ba-11eb-9af3-3f25261f86e2.png)
