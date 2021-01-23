# Snake-classification

The objective is to detect the species of snakes into 35 different categories from its image.

Collected Dataset from different web resources, then performed image data transformation using helper functions provided by FastAI. Increased data size using Image Data Augmentation.

Used pre-trained model of resnet50 to train on my dataset, and obtained the optimum learning rate.

Used weighted F1-score as my model evaluation metric. Obtained F1-score of 47.106 on validation set and of 51.236 on test.
