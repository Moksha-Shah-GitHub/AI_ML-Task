# Metal Classification using Support Vector Machine (SVM)

This project aims to classify metal images into two categories: "Brass Metal" and "Non-Brass Metal" using a Support Vector Machine (SVM) classifier.

## Project Description

Metal classification is an essential task in various industries, including manufacturing and recycling. This project utilizes machine learning techniques to automate the process of classifying metal images, thereby improving efficiency and accuracy.

## Dataset

The dataset directory should be organized as follows:


Ensure that the images are organized into subdirectories according to their respective categories.

## Data Preparation

1. Set the `input_dir` variable to the path of your dataset directory.
2. Modify the `categories` list to include the categories present in your dataset.
3. Run the provided Python script to prepare the data, split it into train and test sets, and train the SVM classifier.

## Usage

1. Ensure that you have Python installed on your system.
2. Install the required Python libraries by running `pip install numpy scikit-learn opencv-python`.
3. Clone or download the project repository.
4. Set up your dataset directory as described in the "Dataset" section.
5. Navigate to the project directory.
6. Open the provided Python script (`metal_classification.py`) in a text editor.
7. Modify the `input_dir` variable to point to your dataset directory.
8. Run the Python script (`python metal_classification.py`).

## Results

The trained SVM classifier will be evaluated on the test set, and the accuracy score will be printed to the console.

## Contributing

Contributions are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
