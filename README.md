# Obstacle Detection Using AI

## Project Overview

This project is designed for a website named **Obstacle**, which focuses on identifying and sharing road hazards such as potholes and manholes. The website enables users to:

- Upload photos of obstacles encountered on the roads.
- Provide the exact location of these obstacles.
- Share this information with others, allowing them to be aware of and avoid these hazards in advance.

To streamline this process, an AI model has been developed to automatically detect and classify the type of obstacle (pothole or manhole) from the uploaded images. This ensures accurate and timely updates for future users, making road navigation safer and more efficient.

---

## Dataset Preparation

### Initial Dataset

- **Potholes**: 50 images
- **Manholes**: 25 images

### Data Augmentation Techniques

To expand and balance the dataset, various data augmentation techniques were applied, including:

- **Flipping**: Horizontally and vertically flipping the images.
- **Blurring**: Introducing blur to simulate different weather or camera conditions.
- **Rotating**: Adjusting the angle to capture different perspectives.
- **Brightness Adjustment**: Modifying brightness to account for varying light conditions.
  
<img src="https://github.com/user-attachments/assets/04bba174-1ce2-4ecf-92c8-e95031640e47" alt="Image for Augmentation" width="700">

### Augmented Dataset

- **Potholes**: Expanded to 300 images
- **Manholes**: Expanded to 300 images

This resulted in a robust dataset for training the AI model, ensuring improved performance and generalization.

![stats image](https://github.com/user-attachments/assets/3b0c1f86-47da-4181-8110-31c24da90f9b)
---

## Model Architecture

### Techniques and Architectures Used

1. **Convolutional Neural Networks (CNNs)**

   - Initial training with CNNs to establish a baseline model.

2. **Pre-trained Models**

   - **ResNetV2**
   - **InceptionV3**

These architectures were fine-tuned to achieve optimal performance for this specific use case.

---

## Model Training and Performance
- The pre-trained models provided a significant boost in model performance by reducing the loss and achieving perfect training accuracy.
- Validation accuracy was slightly lower with pre-trained models but still within an acceptable range, indicating robust model generalization.
## Conclusion

This project successfully demonstrates the use of AI in automating obstacle detection for road safety. By leveraging data augmentation and state-of-the-art pre-trained models, the system provides:

- High accuracy and reliability in identifying road hazards.
- Improved user experience on the **Obstacle** website.
- A scalable solution that can adapt to additional obstacle types in the future.

---

## Future Work

- Expanding the dataset to include more diverse obstacle types.
- Optimizing the model for faster inference on low-resource devices.
- Incorporating real-time detection features into the website.

---

This README outlines the journey and efforts undertaken to develop a robust AI model for obstacle detection, ensuring safer roads for everyone.

ok.. 


