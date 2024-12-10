This is my own AI project, I wanted to work with more complex 2D colour images.
I've chosen 2 dog breed Kaggle datasets for this project, in the end I had used the cleaner dataset for my algorithm.
I decided to classify dog breeds, because as a dog owner and genetics grad, I am very familiar with dog breeds and can more easily assess the performance of my AI model.

For this project, I wrote a 7 layer Convolutional Neural Network (CNN), based on famous VGG16 model, since I had a lot of classes and thousands of images.
I did extensive data preprocessing, removed classes with too few images, removed blurred or wrong format images (PNG worked best for the model), transformed images
to generate more data for the model.
I also tested my model on the images of my own dog to identify what breed it is.

In the end, my model did well with training dataset, but struggled with test and validation datasets, because there were too few images overall.
I used classic train-test-split of 70% images for training, 10% for validation and 20% for testing (never seen before by the model).
