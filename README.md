# Diamond_Analysis

A personal project demonstrating basic data science tools, including data visualization, machine learning, and deep learning originally for completion of a Boot Camp Final requirement. \
The project has three main objectives and completed using four separate Python notebooks.\
The notebooks are run using Google Colab with very limited computing power but the codes are written with scalability in mind so optimizations can be performed easily with higher computing resources.

## Data Pre-Processing
The first notebook is to perform initial data munging to prepare the tabular data of more than 6000 data points about diamonds with 14 columns originally saved in separate CSV files.\
tools: Pandas

## Data Visualization
Explores and creates insightful data visualizations about the pricing and properties of diamonds that are available in the market.
tools: Matplotlib, Seaborn

##  Deep Learning
Develop a Convolutional Neural Network Model that can predict the price (cost per weight/price_per_carat) of a diamond based on its image alone. The model is trained using thousands of images of the same diamonds used above. (Aims to give customers, who knows little to nothing about properties of diamonds, a price estimate)\
tools: Scikit


## Machine Learning
Create a machine learning model that can predict the total price of a diamond based on its tabular properties. Tests different models and ended up using Random Forest Regression with the best performance. (Aims to help gem cutters, who are knowledgeable about diamond properties, decide how to cut raw diamonds, and predict how much they can sell it)
tools: TensorFlow
