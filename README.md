<h1 align="center">
 <img src="https://media.giphy.com/media/U3aSGuq0paWSro3Vnx/giphy.gif" width="30"> Portfolio Projects <img src="https://media.giphy.com/media/U3aSGuq0paWSro3Vnx/giphy.gif" width="30">
</h1>

## QWANT Programming School, Data Science Track (May, 2021 - October, 2021).

1. **Convex Optimization**

In this project, I learned performance measure through Gradient Descent Methods, answering questions such as how a learning rate influences the efficiency of the algorithm, and used Simplex Algorithm to find optimal values.

2. **DS Babel**

Using cursor and iteratively reading an sql file, then writing it into a csv; converting a csv to sql through queries and Python's sqlite3 module.

3. **FAFA** 

>1.	Scraped the data from the https://fa-fa.kz/search_load/gruzy-almaty/ with Beautiful Soup in fafa_Almaty.py and wrote it in fafa_Almaty.csv
>2.	Cleaned Data in fafa_Almaty.csv
>3.	In fafa_Almaty.ipynb: Introduced Data,
>4.	Did an Exploratory Data Analysis, 
>5.	Answered 3 Business Questions through calculations and visualizations with seaborn and matplotlib.pyplot.
>6.	Presented Suggestions on a profitable business model

I summarized Projects steps in the BlogPost: https://fafkz-scraping.blogspot.com/2021/09/scraping-fafakz-for-almaty-delivery.html .

4. **Fine Tune**

Fune tuning for Sentiment Analysis Using PyTorch to create [bert-finetuned-semantic-chinese](https://huggingface.co/Ayazhankad/bert-finetuned-semantic-chinese). Result Model: [here](https://huggingface.co/Ayazhankad/bert-finetuned-semantic-chinese)

5. **Github Scraper**

Using Python's requests and beautifulsoup4 modules, returning a CSV of the TOP 25 trending repositories from Github's page (https://github.com/trending). Following information is included: Developer, Repository Name, Number of Stars.

6. **Open Iris**

Loading the dataset with pandas; Summarizing the dataset; Visualizing the dataset with seaborn; Evaluating algorithms with sklearn's DecisionTreeClassifier, KNeighborsClassifier, LogisticRegression, SVC; Making predictions about which class of iris plant does a plant belongs to based on its characteristics through training the data with sklearn's train_test_data, and showing the accuracy score.

7. **NBA Game Analysis**

Immersing in the NBA game dataset, parsing a csv, which describes both teams' players' game activities to
create a table, separately for home and away team, with statistics (FG, FGA, FG%, 3P, 3PA, FT) of all players by finding keywords with Python's Regex Module. Additional calculations were done for some stats.

## University, Year 1 (2021-2022):

8. **Hospital Admitting System Simulation** 

>1. Reading the Patients dataset - Sheet1.csv, new_Diseases and Symptoms - Sheet1.csv.
>2. Shuffle the 'Patients dataset - Sheet1.csv', Add pateients to the hospital based on the following critera: (used **OOP for Patient and Hospital data structures**) 
- Does the admittied patients number exceed the capacity?
- Can the hospital assign two symptoms of the patient to any of the diseases that it treats (get from new_Diseases and Symptoms - Sheet1.csv).
>3. Create a csv for Admitted/not Admitted patients.
Output: 'Hospital_admitted.csv', 'Hospital_NOTadmitted.csv'.
>4. Recommend Different Lung Diseases treatment hospitals to not admitted patients.
- Scrape https://www21.ha.org.hk/smartpatient/SPW/en-us/Useful-Resource/Patient-Group/List/?guid=ebe3f3f7-cd2b-4573-882e-cfd61eac55ac with **BeautifulSoup** -> make a Dataframe -> create a csv of recommended hospitals.
>5. Visualizing the frequency of diseases of Admitted Patients with **matplotlib.**

**Every time the code is run, the output 'Hospital_admitted.csv', 'Hospital_NOTadmitted.csv' will be different because the 'Patients dataset - Sheet1.csv' will always be shuffled differentely.**

Hence, the bar plot will be different for every run.

9. **RFM Analysis**

>1. Use the public dataset: https://www.kaggle.com/olistbr/brazilian-ecommerce, namely olist_orders_dataset.csv and olist_order_payments_dataset.csv files.
>2. Convert the date of delivery of the order by the original carrier (order_delivered_carrier_date) to datetime64. -> as we are going to base our calculations on it.
>3. Create an index order_id and connect the datasets through it.
>4. Since the dataset is not recent, we will use max + 1 instead of the current date. To create Recency, Frequency and Monetary for every customer, group the records through customer_id. -> RFM Table is ready!
>5. Assigning grades. Split into a range from 1 to 5. The wider the range, the more accurate our groups are, but at the same time, it is more challenging to work with a large number of combinations.
>6. Segmented_rfm Table is ready! RFM score of 413 means: r_quartile = 4, f_quartile = 1, m_quartile = 3.
>7. Separately, the average recency/frequency/monetary_value values for all RFMScore can be seen using matplotlib.

## University, Year 2 (2022-2023):

10. **Games in Java**

Game programes created during the COMP2026/COMP2045 (Programming and Problem-Solving; Programming Using Object-Oriented Approach) courses:

- [6-nimmit](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Games/6-nimmt)
- [Connect Four](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Games/ConnectFour)
- [Tower Defence](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Games/TowerDefense)

Skills: Inheritance/List/Exception Handling/Polymorphism/Arrays/etc.

11. **[R practice](https://github.com/ayazhankadessova/Rpractice)**

Assignments done during the ECON3096: Causal Inference: Capturing Cause-and-Effect Relationships with Data course.

* [Assignment 1](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Rpractice/Assignment1): Counterfactual outcome, independent/dependent variables, bivariate regresion
* [Assignment 2](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Rpractice/Assignment_2): Identificantion, Multivariate Regression, Controls, Causal Diagrams, R^2, Omitting
* [Assignment 3](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Rpractice/Assignment_3): Experiment and Difference-in-Differences, DID in non-experiment setting, Matching Fixed Effects
* [Final](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Rpractice/Final): Referee Report(black and white wage gap that shows discrimination of labor market), Replication Project (Treatment effect, Quadratic relations, Regressions, etc).

