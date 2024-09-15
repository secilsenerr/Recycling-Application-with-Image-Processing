The topic of our project is developing a mobile application that promotes recycling using image processing and object detection technologies.

This application analyzes photos taken by users to automatically identify and categorize recyclable materials such as paper, metal, and plastic.

Users can then correctly sort their recyclable waste, contributing to the recycling process.

The app encourages users to earn points by recycling in different categories and offers a reward system in exchange for certain point thresholds.
In our project, the object detection process enables the recognition of recyclable materials (such as paper, metal, plastic) through image processing and machine learning methods.

**Loading and Processing the Dataset:**
The dataset consists of images containing recyclable materials. 
The images have been resized to specific dimensions and labeled according to their respective classes. Classes that are irrelevant to the project, such as clothing and shoes, have been removed. Separate classes for green, brown, and white glass have been merged under a single "glass" class, and unnecessary images were deleted to prevent overfitting.

**Splitting the Dataset into Training and Test Sets:**
The dataset was divided into 80% training and 20% test sets.
The training set is used for the model to learn, while the test set is used to evaluate the model's performance.

**Building the CNN Model:**
The Convolutional Neural Network (CNN) model was built using convolutional layers, max pooling layers, fully connected layers, and dropout layers.
These layers extract features from the images to perform the classification.

**Compiling the Model:**
The model was compiled using the Adam optimization algorithm and the sparse_categorical_crossentropy loss function. These processes help the model learn more quickly and effectively.

**Training the Model:**
The model was trained with the training data for 10 epochs and evaluated with validation data at the end of each epoch.
During the training process, the model's performance was monitored, and necessary adjustments were made.

**Saving the Model:**
The trained model was saved in .tflite format for future use.

**Visualizing Training Loss and Accuracy:**
The loss and accuracy values during the training process were visualized using graphs.
These graphs helped us understand how the model performed and improved.
![Ekran Görüntüsü (676)](https://github.com/user-attachments/assets/f33d7699-64d5-4387-80f6-7ade617726ac)
![Ekran Görüntüsü (677)](https://github.com/user-attachments/assets/776b3fcc-810b-4694-bdfe-3a0ed2963565)
![Ekran Görüntüsü (678)](https://github.com/user-attachments/assets/085e6cf6-4350-450e-807d-50eab4a4ba79)
![Ekran Görüntüsü (679)](https://github.com/user-attachments/assets/a631eb90-31c0-47f5-869f-0200fd4c3dcb)
![Ekran Görüntüsü (680)](https://github.com/user-attachments/assets/f2a8e8a3-4e90-4db3-a918-1db98e4e813f)
![Ekran Görüntüsü (681)](https://github.com/user-attachments/assets/8557130e-8e6a-4471-b7b2-e7373ba8b0fa)
![Ekran Görüntüsü (682)](https://github.com/user-attachments/assets/85dd939e-cb01-49ef-a601-8e734a12a3cf)
![Ekran Görüntüsü (683)](https://github.com/user-attachments/assets/4a956ad5-3c2d-44c3-ae44-2c6729680d6a)
![Ekran Görüntüsü (685)](https://github.com/user-attachments/assets/c6eb5bb7-f840-4291-a779-7f961500b704)
![Ekran Görüntüsü (686)](https://github.com/user-attachments/assets/e11ff027-42f9-48c7-9acb-476612885387)







![Ekran Görüntüsü (692)](https://github.com/user-attachments/assets/91d18d35-47f1-49ce-9b69-48e33afe6a22)
![Ekran Görüntüsü (691)](https://github.com/user-attachments/assets/8946bfaf-4376-41ad-b8b5-6a237df01607)
