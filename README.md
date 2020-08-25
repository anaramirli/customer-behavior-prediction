# customers-behaviour-analysis

For companies, it is important to use customer data to increase both customer satisfaction and the revenue of the company. Information related to shopping behaviours of the customers is very crucial to understand and to respond to customers on time in a proper way. In this project, we do parametric and non-parametric statistical analysis on shopping duration and shopping amount. Doing so, the aim is to understand these features and their relation with other features to build a more robust dataset for models.

#### Tests impelemneted:
* ANOVA 
* Tukey HSD
* Kruskal-Wallis
* Conover post hoc

#### Description of our project folder
   ```dataset```: contains dataset file<br/>
   ```modules```: contains some utility functions/classes we're using<br/>
   ```shop_duration_stat_tests.ipynb```: statistical tests on shopping duration<br/>
   ```shop_amount_stat_tests.ipynb```: statistical tests on shopping amount<br/>
   ```models_shopping_amount.ipynb```: classificaton modles for shopping amoount<br/>
    
#### Check requirements (to run the codes you need python version 3.6+):
    ```
    conda create -n my_env python=3.6
    conda activate my_env
    (my_env)$ pip install -r requirements.txt 
    ```
