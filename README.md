# Face-Mask-Classification

This is a simple CNN model that I tried to improve the performance of my original project of face mask image classificaiton done with my classmates (https://github.com/Szhang577/STAT_451_Final_Project). I was not able to upload the dataset due to the large size of pictures, but they can be easily downloaded from https://www.kaggle.com/datasets/andrewmvd/face-mask-detection. Great thanks to the contributors of the dataset and notebooks!

We used six classification models, and XGBoost reached an accuracy of 94.88%, but while predicting on our own photos, the predictions were not accurate at all. We proposed that other models more suitable for image classification could be used in the future exploration, so I spent some time learning basics of deep learning and implemented the proposition on my own. The size of the dataset is fairly small, and number of pictures in each class is unbalanced, so I used data augmentation to increase the size. The final CNN model reached accuracy of 97.13% on the test data, which is a great improvement from our original models.
![Unknown](https://user-images.githubusercontent.com/52028491/190357011-cae39411-60a6-4a95-8bd6-191399241292.png)

When I tried to predict labels in a picture full of people, I surprisingly found out that the predictions were far more accurate. Of course the predictions were not perfect, so I will learn more about machine learning and tune the model better. I also got much insight into how data science can affect the real world and help in many aspects.

Some of the faces got predicted:

![Unknown-4](https://user-images.githubusercontent.com/52028491/190361186-cd92228c-ae19-4862-9cdf-245bd4bbc0c3.png)
![Unknown-8](https://user-images.githubusercontent.com/52028491/190361254-533fcfe1-0a18-4188-a30f-a5383b329993.png)
![Unknown-9](https://user-images.githubusercontent.com/52028491/190361267-f6a46803-6d9f-420a-9e73-dde7da7f7ab8.png)

