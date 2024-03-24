# CNN Classifier
##Introduction:
This report compares the performance of various models for classifying the MNIST handwritten digit dataset using PyTorch. We explore a Convolutional Neural Network (CNN), Faster R-CNN, fine-tuned VGG16 and AlexNet models, and analyze their accuracy, F1 score, loss, and training time.

##Models:
1.CNN: This is a standard CNN architecture with convolutional and pooling layers followed by fully connected layers.
2.Faster R-CNN: This is an object detection model, which might be an overkill for MNIST where we only have digit classification.
3.Fine-tuned VGG16 and AlexNet: We utilize pre-trained VGG16 and AlexNet models and fine-tune them on the MNIST dataset.


Key Learnings:

CNN Architecture: I successfully built a CNN architecture for digit classification, achieving an accuracy of 3/3 .![mean](https://github.com/SoukainaElidrissi/Atelier2/assets/128905801/ff0a2986-f24b-4632-bbd5-b0579cb06b0c)


Faster R-CNN: Explored the application of Faster R-CNN for MNIST (object detection model), which might be less suitable than CNNs for simple classification tasks.
Fine-tuning Pre-trained Models: Fine-tuning pre-trained models like AlexNet and VGG16 yielded the highest accuracy (99.13% and 99.16% respectively) compared to the basic CNN. This highlights the advantage of deeper architectures in capturing complex features.
Trade-off between Accuracy and Efficiency: While fine-tuning offers better accuracy, it can be computationally expensive. For smaller datasets like MNIST, a simpler CNN might be more efficient.with results of ![mean2](https://github.com/SoukainaElidrissi/Atelier2/assets/128905801/6d23d962-a259-419a-8ad1-bfd2414917cf)

