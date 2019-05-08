# Final
## Unstructured Final Project

### Data Flinging
#### group_and_fling.py
The group_and_fling.py file simply loads in the data, groups product purchases by invoice number into baskets, deletes and creates an elasitcsearch index called baskets, and flings each basket to this elasticsearch index.  Note that the Online_Retail.csv file must be in the same folder as the group_and_fling.py file when run to succesfully fling to elasticsearch.


### Item-Item Recommenders
The following two python files contain functions that allow a user to see the top 5 recommended product codes and product descriptions for a given product code.

#### top5_codes_function.py
The top5_codes_function.py file contains a defined function that takes in a product code as the argument and returns a data frame of the top 5 recommended product codes for a basket with the initial product code in it. When run, the file is set to spit out an example data frame generated by a user putting in the product code 22045.

#### top5_desc_function.py
The top5_desc_function.py file contains a defined function that takes in a product code as the argument and returns a data frame of the top 5 recommended product descriptions for a basket with the initial product code in it. When run, the file is set to spit out an example data frame generated by a user putting in the product code 22045.
