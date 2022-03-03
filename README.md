# Encipher-Instabase-2022-Project

A model that will help to classify the legal clauses extracted from Credit Agreements into it’s legal clause type.

I have used Multi-Class classifier Artificial Neural Networks.

1. Open the given .ipynb file in google colaboratory.
2. Create a folder named Encipher in you google drive.
3. Add the train2.csv file in the folder. (Train2.csv should contain 2 columns 'Agreement' and 'Type')
4. Currently model is trained considering the 5 Types given: 1. Preamble 2. Governing Law 3. Lender Deafulting 4. Indemnification 5. Other
5. To feed data for prediction, create a test.csv file in same 'Encipher' folder with 2 columns 'Id' and 'Agreement'.
6. Predicted output will be generated in json format in predictions.json.
