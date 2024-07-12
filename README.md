# Industry-copper-modelling

## Project Objectives

This initiative is dedicated to crafting two sophisticated machine learning models catered to the intricacies of the copper industry. The primary goals include enhancing the accuracy of selling price predictions and streamlining lead classification. Traditional manual predictions are often resource-intensive and may fall short in yielding optimal pricing decisions or capturing leads accurately. To overcome these challenges, our models employ cutting-edge methodologies such as data normalization, outlier identification and management, rectification of incorrectly formatted data, exploration of feature distributions, and harnessing the power of tree-based models—specifically, the decision tree algorithm.

### Regression Model Highlights

Within the realm of sales and pricing data in the copper industry, challenges like skewness and noisy data are prevalent. This model addresses such complexities by incorporating advanced techniques like data normalization, outlier identification and management, correction of improperly formatted data, understanding feature distributions, and utilizing the decision tree algorithm.

### Classification Model Insights

Lead classification poses another formidable challenge in the copper industry. Our model evaluates and classifies leads based on their likelihood to convert into customers. Leveraging the `STATUS` variable, designating 'WON' as a success and 'LOST' as a failure, the model excludes data points with STATUS values other than 'WON' or 'LOST'.

## Solution Approach

The solution methodology encompasses the following pivotal steps:

1. In-depth exploration of skewness and outliers in the dataset.
2. Transformation of data into a suitable format, including requisite cleaning and pre-processing steps.
3. Construction of a machine learning regression model predicting the continuous variable 'Selling_Price' using the decision tree regressor.
4. Development of a machine learning classification model predicting the Status ('WON' or 'LOST') using the decision tree classifier.
5. Creation of a user-friendly Streamlit interface, allowing users to input column values and receive predicted Selling_Price or Status outcomes.

## Requirements

The successful execution of this project necessitates the installation of the following libraries:

- NumPy
- Pandas
- Scikit-learn
- Streamlit

## Getting Started

1. Clone the repository.
2. Install the required libraries.
3. Launch the Streamlit app using the command: `streamlit run app.py`.
4. Input values for each column to obtain predicted Selling_Price or Status ('Won' or 'Lost').
