## Project README



### Screenshots
Here is a screenshot from the tutorial video showing the project in action:

![Tutorial Screenshot](youtube.png)


### Overview
This project explores the extraction of text from images using Python, following Rob MULLA's tutorial on YouTube. The comparison focuses on three prominent libraries: `pytesseract`, `easyocr`, and `keras_ocr`. The examples and demonstrations are based on the TextOCR dataset available on Kaggle.

### Data Source
The dataset used in this project can be found on Kaggle:
- **TextOCR Dataset**: Contains images with annotated text, used for OCR tasks.

### Setup and Dependencies
Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `matplotlib`
- `PIL`
- `pytesseract`
- `easyocr`
- `keras_ocr`

These libraries can typically be installed using `pip`:
```bash
pip install pandas numpy matplotlib Pillow pytesseract easyocr keras-ocr
```

### Usage
1. **Loading Data**: Utilize `pandas` to load annotation and image data from the provided dataset.
2. **Visualizing Images**: Use `matplotlib` to visualize images from the dataset, displaying annotations where applicable.
3. **Performing OCR**:
   - **Method 1: pytesseract**: Implement Tesseract OCR for text extraction.
   - **Method 2: easyocr**: Utilize EasyOCR for OCR tasks.
   - **Method 3: keras_ocr**: Deploy Keras OCR for text recognition.

### Example Usage
- **Visualizing Images**: Display images with annotations:
  ```python
  import matplotlib.pyplot as plt
  
  img_path = './data/train_images/example.jpg'
  img = plt.imread(img_path)
  plt.imshow(img)
  plt.axis('off')
  plt.show()
  ```

- **Performing OCR**:
  ```python
  import pytesseract
  from easyocr import Reader
  import keras_ocr
  
  # Example usage of each OCR method
  # (Code snippets provided in the project)
  ```

### Results
- **OCR Results Comparison**: Compare results from `easyocr` and `keras_ocr` for accuracy and performance.

### Conclusion
This README outlines the project setup, dependencies, and usage instructions for extracting text from images using Python libraries. The project follows the tutorial by Rob MULLA and utilizes the TextOCR dataset from Kaggle. For detailed implementation and exploration, refer to the provided Python scripts and notebooks.

Tutorial Video: [Extracting Text from Images with Python](https://www.kaggle.com/code/robikscub...) by Rob MULLA.
