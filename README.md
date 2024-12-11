# Detect-images-with-scratches
Building a model to classify images as good (clear text) or bad (scratched text)  

File  Detect images with scratches.pynb is in the second branch named as **master ** which contain all the code of pyhton and all the model trained in it .

Testing the Best Model
a. Prepare the Test Dataset
Use 10% of the dataset that the model has never seen (not part of training or validation).
Ensure the test data has a balanced representation of "good" and "bad" images.
b. Load the Trained Model
Save the best model's weights during training (e.g., best_model.pth for PyTorch or best_model.h5 for TensorFlow).
Load these weights into the corresponding model architecture.

Run Predictions
Use the test dataset to evaluate the model's performance.
Calculate metrics like accuracy, precision, recall, and F1-score.

 Visualize Results
For classification: Display a few test images with their predicted labels.
For object detection/segmentation: Overlay bounding boxes or masks on images.
