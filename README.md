# BIRDS-400-SPECIES-IMAGE-CLASSIFICATION-EFNET-LSTTM

The is an EfficientNtB4+LSTM based model using transfer learning. To reduce training time them odel was trained on 112 X 112 X 3 images. This model achieed a training accuracy of 99.82%, a validation accuracy of 98.05% and an averaged F1 score of 99.44%. It was trained for 10 epochs. On average each epoch takes about 5 minutes. To balance the training set each class (species) was limited to a maximum of 150 image samples. For classes with less than 150 image samples additional samples were created using augmentation such that all classes ended up with 150 training images. A custom Keras callback was used to control the leaning rate which significantly improves model performance.

