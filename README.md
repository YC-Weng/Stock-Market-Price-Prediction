# Stock-Market-Price-Prediction
Our research aims to provide an accurate prediction on the stock prices of the Taiwan 50 Index. Therefore, we had conducted numerous experiments and tried different features along with different models in order to minimize the difference between the predicted prices and the real prices. After weeks of adjustment, we had our best models and best selected features according to different stocks.
## Data
| Folder        | Start Day     | End Day     | Purpose     |
| ------------- | ------------- | ----------- | --------    |
| 0050-KY       | 2022-11-14    | 2023-11-10  | Training    |
| 0050-K        | the day the stock was listed  | 2023-12-8 | Training  |
| 0050-1224     | 2023-9-26     | 2023-12-22  | Prediction  |
## Files
| File                  | Purpose |
| -------------         | ------- | 
| final_model.csv       | recording the selected hyperparameters for each stock    | 
| final_save.ipynb      | training the models using the selected hyperparameters and saving them to a folder  | 
| final_predict.ipynb   | using the trained models to make predictions     | 

## Setup
* download the zip of the repository
* unzip and upload it to the root directory of your google drive
* open the ***final_save.ipynb*** and execute all (Note that you might suffer *out of RAM* problem when you are trying to train all the 50 models, therefore it is recommended to train a small portion of models at a time by modifying the _company\_list_ in the second code block)
* open the ***final_predict.ipynb*** and execute all
* your result will be in the folder ***0050-1224*** 
