# Image-Recognition-with-CNN

## 📸 Dataset

- **Training set**: 2,000 RGB images (cats and dogs) flattened to size `100x100x3`
- **Test set**: 400 RGB images
- Loaded from CSV files and reshaped into image tensors.

## 🛠️ Key Steps

1. Data loading and reshaping with NumPy
2. Image normalization
3. CNN architecture using Keras:
   - Conv2D → ReLU → MaxPooling → Flatten → Dense → Sigmoid
4. Model training with `binary_crossentropy` loss and `adam` optimizer
5. Random image display and prediction

## 🧪 Example Prediction

```python
The model prediction is a DOG
