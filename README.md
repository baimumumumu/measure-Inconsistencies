# measure-Inconsistencies
## NER Based on BERT+Bi-LSTM+CRF 

Step 1: Download the pre-trained BERT model and store it in the /cekps directory, using the name of the pre-trained BERT model as the filename.

Step 2: Process the dataset using Preprocess.ipynb.py to preprocess the raw data. Then, place the resulting dataset into the /dataset_real/processed_data directory.

Step 3: Please open 'BERT+Bi_LSTM+CRF.ipynb' to run the codes. You can see that I re-process the preprocessed data into three '.txt' files for training, validating, and testing.

Step 4: Execute main.py to start training the data.

## RE Based on BERT
Step 1: Download the pre-trained BERT model and store it in the /cekps directory, using the name of the pre-trained BERT model as the filename.

Step 2: Create a new folder named dataset_real, and then execute preprocess.py, preprocess2_step.py, and preprocess3_step.py sequentially to obtain the dataset.

Step 3: Use main.py to train the model.

Step 4: Use test_to_result.py to test the dataset and obtain the results.
