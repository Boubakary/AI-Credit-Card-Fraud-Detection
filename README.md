# AI Credit Card Fraud Detection

## Overview

Detecting fraudulent credit card transactions is a crucial task in financial systems to prevent financial losses and protect customers. This project aims to develop a machine learning model to accurately identify fraudulent transactions based on a dataset of past credit card transactions. By leveraging the power of AI, we aim to create a model that can distinguish between legitimate and fraudulent transactions with high accuracy, thereby enhancing the security measures of financial institutions.

## Project Structure
AI-Credit-Card-Fraud-Detection/

<img width="344" alt="Screenshot 2024-07-20 at 17 34 59" src="https://github.com/user-attachments/assets/10dd35e8-f65a-48fe-8dfe-5434c2d745fa">

- `data/`: Store raw and processed data files.
- `notebooks/`: Keep Jupyter notebooks for data exploration, model training, and evaluation.
- `scripts/`: Store Python scripts for data preprocessing, model training, and utility functions.
- `models/`: Save trained models and related files.
- `reports/`: Include any reports, figures, and documentation.

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/AI-Credit-Card-Fraud-Detection.git
    cd AI-Credit-Card-Fraud-Detection
    ```

2. Create a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
## Dataset

The dataset used in this project is crucial for training and evaluating the machine learning models. Here is how you can handle the dataset:

1. **Download the Dataset**:
   - The dataset can be downloaded [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Ensure you have the appropriate permissions to use and share the data.

2. **Store the Dataset**:
   - Place the downloaded dataset in the `data/raw/` directory. For example:
     ```
     AI-Credit-Card-Fraud-Detection/data/raw/dataset.csv
     ```
3. **Dataset Format**:
   - Ensure the dataset is in CSV format or any other format that can be easily loaded using pandas or similar libraries.

## Usage

1. **Data Preprocessing**:
   - Run the data preprocessing script to clean and preprocess the dataset:
     ```sh
     python scripts/data_preprocessing.py
     ```
     - The processed data will be saved in the `data/processed/` directory.

2. **Exploratory Data Analysis**:
   - Use the notebooks in the `notebooks/` directory to explore and visualize the data.

3. **Model Training**:
   - Train the model using the model training script:
     ```sh
     python scripts/model_training.py
     ```

4. **Evaluation**:
   - Evaluate the trained model and view the results in the `reports/` directory.

## Contributing

We welcome contributions to improve this project! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The [dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) used in this project was obtained from Kaggle. 
- Inspiration and resources from various online tutorials and documentation.

## Contact

For any questions or suggestions, please feel free to contact me.

---
