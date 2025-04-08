
# Transfer Learning with MobileNetV2 on CIFAR-10
This project uses MobileNetV2 pre-trained on ImageNet to classify CIFAR-10 images via transfer learning. With a subset of 10,000 training samples and 10 epochs, it achieves 82% test accuracy.

## How to Run
1. Open in Google Colab or install TensorFlow locally.
2. Run the notebook end-to-end.

## Key Insights
- Proper preprocessing (raw [0, 255] data with `preprocess_input`) was critical to jump from 12% to 82% accuracy.
- Limited data caps performance; full dataset could push accuracy to 85-90%.

## Future Work
- Use full CIFAR-10 dataset.
- Fine-tune MobileNetV2 layers.
