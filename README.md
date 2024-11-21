Big Mart Sales Prediction


Predicting sales for a retail dataset using Machine Learning techniques.
📋 Table of Contents

    Project Overview
    Technologies Used
    Dataset
    Installation
    Usage
    Results
    Contributing
    License

📖 Project Overview

Big Mart is a large retail chain, and the goal of this project is to predict the sales of various products in its stores based on historical data. By analyzing product features, store information, and sales history, we use machine learning models to predict the sales figures.

This project is designed to help retailers understand:

    Which products are likely to sell well.
    How store characteristics affect sales.
    How to optimize inventory management.

💻 Technologies Used

    Python 3.12
    Libraries:
        Pandas
        NumPy
        Matplotlib
        Seaborn
        Scikit-Learn
        XGBoost
        LightGBM

📂 Dataset

The dataset is sourced from Big Mart Sales Data.
Columns:

    Item_Identifier: Unique product ID
    Item_Weight: Weight of product
    Item_Fat_Content: Fat content of the product
    Item_Visibility: The percentage of total display area of all products in a store
    Item_Type: Type of product
    Outlet_Identifier: Store ID
    Outlet_Size: Size of the store
    Outlet_Location_Type: City type where the store is located
    Item_Outlet_Sales: Sales of the product in a store (target variable)

🛠 Installation

    Clone this repository:

git clone https://github.com/yourusername/BigMartSalesPrediction.git  
cd BigMartSalesPrediction  

Install required dependencies:

    pip install -r requirements.txt  

    Ensure the dataset is placed in the data/ folder.

🚀 Usage

    Preprocess Data: Run the script to clean and preprocess the dataset:

python preprocess.py  

Train the Model: Use the training script:

python train_model.py  

Make Predictions: Predict sales for new data:

    python predict.py --input new_data.csv --output predictions.csv  

    Notebook Option: Open BigMartSalesPrediction.ipynb for an interactive exploration of the analysis and model training.

📊 Results

The final model achieved:

    R² Score: 0.87
    RMSE: 1132.45

The best performing model was XGBoost.
🤝 Contributing

Contributions are welcome!

    Fork the repository.
    Create a new branch: git checkout -b feature-name.
    Commit your changes: git commit -m 'Add feature'.
    Push to the branch: git push origin feature-name.
    Submit a pull request.

📝 License

This project is licensed under the MIT License.
