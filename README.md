# Cat and Dog Image Classifier using Transfer Learning

- This project is inpsired by [FreeCodeCamp](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/cat-and-dog-image-classifier). The project revolves around a dataset with high-quality images but poses a challenge due to its relatively small size. Additionally, each image within the dataset varies in dimensions, complicating the resizing process and potentially leading to information loss.
- The assignment expected a 70% validation accuracy which was fairly easy to achieve with my own model architecture and a little hypertuning.
- I further used transfer learning to try and achieve a higher validation accuracy. I experimented with different pre-trained models like MobileNetV2, ResNet50, ResNet101, InceptionV3 etc. Transfer learning with InceptionV3 for 10 epochs resulted in a validation accuracy of 98.5%. Further fine-tuning pushed the validation accuracy of 99.3%.
