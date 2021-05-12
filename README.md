# NLP_Behold_Project_dso560_2021spring_Team_Gold
Behold partnered with USC’s DSO-560 NLP class to collaborate on an alaytics problem.  

## This project has two objectives:

1. Create a classification algorithm to predict `brand_name` given a product's information (part A)
2. Build a recommender algorithm to recommend a complete outfit given a customer's search query (part B)

The code to achieve each objective is available in 5 Jupyter Notebooks in this repository.

## Part A: Getting predictions of brand name

### Option 1: To simply get the predictions from the final model
**Step 1:** Download `cleaned_data_final.csv` and `4_Final_Model_Training_Prediction.ipynb`

**Step 2:** Run the `4_Final_Model_Training_Prediction` notebook using the test data to get the brand name predictions  


### Option 2: For details of data cleaning, pre-processing and explored models
**Step 1:** Download the following files: 
- `Behold+product+data+04262021.xlsx`
- `1_Data_Cleaning_Feature_Creation.ipynb`
- `2_Prepare_Training_Data.ipynb`
- `3_Model_Exploration.ipynb`
- `4_Final_Model_Training_Prediction.ipynb`

 **Step 2:** Run the `1_Data_Cleaning_Feature_Creation.ipynb` Jupyter Notebook for details of the data cleaning steps. This will create a `cleaned_data_final.csv` file which is used as an input in the next step.

**Step 3:** Run `2_Prepare_Training_Data.ipynb` for details of the preprocessing techniques. Run `3_Model_Exploration.ipynb` for details of the models explored and their results.

**Step 4:** Run the `4_Final_Model_Training_Prediction` notebook using the test data to get the brand name predictions from the final model.

## Part B: Outfit Recommendation
To produce outfit recommendations, we created a funnel through which the user’s query gets passed. At each stage, based on cosine similarity and a rule-based heuristic to catch edge cases, we build a recommender function to produce a complete outfit comprising of atleast 3 categories out of top, bottom, one-piece, shoe and accessories. 

### Steps to get an outfit recommendation:

**Step 1:** Download the files `Recommender_Function.ipynb` and `Behold+product+data+04262021.xlsx`

**Step 2:** Run the sections from `Loading Stage` to the `Main Function` (3.2). Call the `outfit( )` function on the new query. This will produce an outfit recommendation

