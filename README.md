# dogs-vs-cats-classification-computer-vision

- Final model gives 94%  accuracy in classificaiton of dogs and cats dataset 

## About the dataset
- This dataset is taken from [kaggle](https://kaggle.com/competitions/dogs-vs-cats/) 
- I have trained the model by downloading the entire dataset, however trained with 1000 cats and 1000 dogs due to unsufficient computational resources

## Preprocessing
- converted all the Images to square 200 x 200 images

## Models used

- I have used `one block VGG`,`two block VGG` , `three block VGG` , plotted the graphs between `loss,val_loss`, `accuracy,val_accuracy` and figured out, at which epoch , the overfitting occurs

## Data Augmentation
- Data Augmentation is one of the regression technique, and it has improved the accuracy to around 60%.

## Dropout
- Dropout is also a regularization technique, however it gave a accuracy of only 48%

## Final Model
- Final model used is VGG 16, using transfer learning , I have trained the model and achieved a accuracy of 96% in classification of dogs and cats .

## Inference
- Using Sample Image, I have tested the model and the Final Model predicted correctly
- 
