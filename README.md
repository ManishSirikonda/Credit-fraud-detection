# Credit Card Fraud Detection Using Machine Learning

This project demonstrates a machine learning approach to detect fraudulent credit card transactions using various classification algorithms. The dataset used contains anonymized features representing financial transactions, and the goal is to classify transactions as fraudulent or genuine.

## Features

- **Data Preprocessing**:
  - Handled missing or null values.
  - Balanced the dataset using appropriate techniques to address class imbalance.
  - Scaled features to improve model performance.

- **Model Development**:
  - Implemented the following machine learning models:
    - Logistic Regression
    - Random Forest
    - Support Vector Machine (SVM)
    - Decision Tree
  - Evaluated each model's performance using metrics such as:
    - Accuracy
    - Precision
    - Recall
    - F1 Score

- **Performance Evaluation**:
  - Compared the performance of different models on training and testing datasets.
  - The best-performing models were identified based on F1 Score and Test Accuracy.

## Results

| Model                  | Train Accuracy | Test Accuracy | Train Precision | Test Precision | Train Recall | Test Recall | Train F1 Score | Test F1 Score |
|------------------------|----------------|---------------|-----------------|----------------|--------------|-------------|----------------|---------------|
| Logistic Regression    | 0.9728         | 0.9420        | 0.9732          | 0.9421         | 0.9728       | 0.9420      | 0.9725         | 0.9411        |
| Random Forest          | 1.0000         | 0.9493        | 1.0000          | 0.9527         | 1.0000       | 0.9493      | 1.0000         | 0.9477        |
| Support Vector Machine | 0.7138         | 0.7101        | 0.5095          | 0.5043         | 0.7138       | 0.7101      | 0.5946         | 0.5898        |
| Decision Tree          | 1.0000         | 0.9348        | 1.0000          | 0.9343         | 1.0000       | 0.9348      | 1.0000         | 0.9340        |

## Dataset

The dataset used in this project is publicly available and contains anonymized features for privacy reasons. Ensure you download and place it in the appropriate directory before running the code.

## Future Enhancements

- Implement additional machine learning models.
- Explore deep learning techniques for improved performance.
- Integrate real-time fraud detection systems.
- Perform hyperparameter optimization for the models used.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
