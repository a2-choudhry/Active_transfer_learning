
# Active Learning and Transfer Learning for Image Classification

This GitHub repository contains a critical review and implementation of a solution that combines 'Active Learning' and 'Transfer Learning' for image classification. The project aims to enhance the accuracy of image classification models by intelligently selecting informative samples for labeling (Active Learning) and leveraging pre-trained models (Transfer Learning). The implemented solution utilizes the popular 'CIFAR-10' dataset and explores the application of 'Uncertainty Sampling' as the Active Learning strategy. The primary focus is to optimize the model's performance efficiently, considering computational power limitations and time constraints. The project showcases results, including accuracy scores, confusion matrices, and graphs, for evaluating the effectiveness of the different approaches used.

## Key Features:

- Active Learning with Uncertainty Sampling: Efficiently selects informative unlabeled samples for labeling, reducing the need for labeling the entire dataset.
- Transfer Learning with Pre-trained Models: Utilizes 'VGG16' and 'ResNet50' pre-trained models, fine-tuned on the 'CIFAR-10' dataset, to improve classification accuracy.
- Grid Search (Removed): Initial attempt at fine-tuning, providing insights into model performance when used with 'Transfer Learning.'
- Results and Reflections: Detailed evaluation of base model and 'VGG16' performance, along with reflections on implementation insights.
- Challenges and Future Enhancements:
- The project highlights challenges related to dataset size, computational power, and time limitations, which impacted the approach taken. Future improvements could include more preprocessing for better initial accuracy, GPU integration to speed up the grid search process, and exploring other Active Learning strategies like 'Query-By-Committee.'


## Conclusion
Overall, this repository presents a comprehensive exploration of combining Active Learning and Transfer Learning for image classification, showcasing the benefits of these techniques in enhancing model accuracy and providing valuable insights for future improvements. 

