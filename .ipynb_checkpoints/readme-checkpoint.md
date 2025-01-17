
## Retrieval images using Wasserstein distance

- Run the notebook model on colab otherwise the data cannot be download
### Model Training

The model has not been trained yet. You can change the dataset size in the `subset_size` variable and adjust the number of epochs. With a reasonable number of epochs and a dataset of size 20,000, training can be fast. To modify the training, you can adjust the parameters accordingly.

### Input Text

To run the retrieval task with a different input, modify the `input_text` variable with your desired text. Once the text is updated, running the code will display the closest image corresponding to that text.

### Running the Code

1. Change the `input_text` variable to the text you want to search for.
2. Modify the `subset_size` if needed to adjust the dataset size.
3. Run the code, and the closest image to your input text will be displayed.

### Focus of the Project

This project primarily focuses on the theoretical foundations outlined in the referenced paper. We provide a basic application for image-text retrieval using Wasserstein distance. However, there are several areas that still require further development.

### Limitations

- The model has not been trained yet.
- The current implementation is a proof of concept, and further optimization and tuning are required for better performance.
