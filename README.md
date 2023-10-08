
# Computer Vision Project

![image](https://github.com/anuragbagri/Computer_vision_Project_using_Tensorflow2.0/assets/129725994/1c315bf2-2abf-4c22-a99e-5526ebfc3254)


Welcome to the Food101 Computer Vision Project! This project leverages TensorFlow 2.0 and Keras to perform image classification on the Food101 dataset using the EfficientNetB3 model. I have applied transfer learning techniques and precision training to achieve accurate food image recognition.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Model Architecture](#model-architecture)
- [License](#license)


## Overview

Food recognition plays a crucial role in various applications, including dietary monitoring, restaurant recommendation, and nutrition analysis. This computer vision project aims to automatically classify food items from images using state-of-the-art deep learning techniques.

### Project Goals

- **Accurate Food Classification:**  primary goal is to develop a model that can accurately classify a wide variety of food items from images.

- **Efficient Model:** I have chosen the EfficientNetB3 architecture, known for its balance of accuracy and efficiency, as the backbone for our model.

- **Transfer Learning:** I have take advantage of transfer learning by initializing our model with pre-trained weights on a large dataset, allowing me to achieve excellent results with relatively little data.

- **Precision Training:** In addition to transfer learning, i have implemented precision training techniques to further improve model performance and reduce training time.

### Why Food101 Dataset?

The Food101 dataset is a diverse and challenging dataset that contains over 100,000 images spanning 101 food categories. This dataset presents a real-world scenario for food image recognition, making it an ideal choice for project.

### Key Features

- **EfficientNetB3:** utilizes the EfficientNetB3 model architecture, which has proven effective in various computer vision tasks.

- **Transfer Learning:** By leveraging pre-trained weights from a large dataset, it can save training time and achieve competitive results with limited labeled data.

- **Precision Training:** this fine-tune our model using precision training techniques to enhance its accuracy.

- **Open Source:** This project is open-source and welcomes contributions from the community.

## Getting Started

To get started with this project, we have to get access to Google Colab with a GPU that has a computing capacity above 7.0. Google Colab provides free access to GPUs, making it an excellent choice for deep learning tasks.

### Precision Training

For precision training, it's essential to have a GPU with a high enough computing capacity. Ensure that the GPU allocated to your Colab notebook meets this requirement. The computing capacity should be above 7.0 for optimal performance.

Now we're ready to start using the project. we can explore the provided notebooks, train the model, make predictions, and experiment with various aspects of food image recognition.


## Prerequisites


```bash
# - Python 3.7 or higher
# - TensorFlow 2.0
# - Keras
# - Transfer learning
# - Mixed Precision Training
```

## Model Architecture

```python
# Load EfficientNetB3 model with pre-trained weights
from tensorflow.keras.applications import EfficientNetB3

model = EfficientNetB3(weights='imagenet', include_top=False, input_shape=(224, 224, 3))
```



## License
```text
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
