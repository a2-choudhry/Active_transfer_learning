## Active_transfer_learning

Active Learning and Transfer Learning for Image Classification

This GitHub repository contains a critical review and implementation of a solution that combines 'Active Learning' and 'Transfer Learning' for image classification. The project aims to enhance the accuracy of image classification models by intelligently selecting informative samples for labeling (Active Learning) and leveraging pre-trained models (Transfer Learning). The implemented solution utilizes the popular 'CIFAR-10' dataset and explores the application of 'Uncertainty Sampling' as the Active Learning strategy. The primary focus is to optimize the model's performance efficiently, considering computational power limitations and time constraints. The project showcases results, including accuracy scores, confusion matrices, and graphs, for evaluating the effectiveness of the different approaches used.

Key Features:

Active Learning with Uncertainty Sampling: Efficiently selects informative unlabeled samples for labeling, reducing the need for labeling the entire dataset.
Transfer Learning with Pre-trained Models: Utilizes 'VGG16' and 'ResNet50' pre-trained models, fine-tuned on the 'CIFAR-10' dataset, to improve classification accuracy.
Grid Search (Removed): Initial attempt at fine-tuning, providing insights into model performance when used with 'Transfer Learning.'
Results and Reflections: Detailed evaluation of base model and 'VGG16' performance, along with reflections on implementation insights.
Challenges and Future Enhancements:
The project highlights challenges related to dataset size, computational power, and time limitations, which impacted the approach taken. Future improvements could include more preprocessing for better initial accuracy, GPU integration to speed up the grid search process, and exploring other Active Learning strategies like 'Query-By-Committee.'

Overall, this repository presents a comprehensive exploration of combining Active Learning and Transfer Learning for image classification, showcasing the benefits of these techniques in enhancing model accuracy and providing valuable insights for future improvements.



# Introduction
-Critical review of the solution combining Active Learning and Transfer Learning for image classification.
-Aim to improve image classification accuracy using these techniques.
-Use of 'CIFAR-10' dataset and Uncertainty Sampling for Active Learning.
Utilization of 'VGG16' and 'ResNet50' pre-trained models for Transfer Learning.
Challenges Faced
Issues with large dataset, 'STL-10' dataset found corrupted, switched to 'CIFAR-10'.
Computational power limitations affected training efficiency and grid search process.
Time constraints influenced number of epochs used and grid search removal.
Approach Taken
Implemented Active Learning with Uncertainty Sampling for informative sample selection.
Utilized 'VGG16' and 'ResNet50' pre-trained models, fine-tuned on 'CIFAR-10'.
Simulated human input for faster results and compared with Transfer Learning only.
Design & Methodology
Flowchart diagram illustrating the overall process of the project.
Splitting 'CIFAR-10' dataset into training and testing data.
Data preprocessing, normalization, and one-hot encoding for labels.
Creation of base model with Dense and Dropout layers, trained with Adam optimizer.
Evaluation
Base model achieved 38% accuracy after 10 epochs.
'VGG16' pretrained model showed improved accuracy compared to the base model.
Confusion matrices generated for evaluating model performance.
Further Reflections
Consider additional preprocessing for higher initial accuracy.
GPU integration for faster grid search process.
Explore other Active Learning strategies like Query-By-Committee.
Conclusion
Successful implementation of Active Learning and Transfer Learning for image classification.
Insights gained for potential enhancements and future improvements.
A detailed evaluation of model performance and results presented.
