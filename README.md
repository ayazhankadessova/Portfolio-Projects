<h1 align="center">
 <img src="https://media.giphy.com/media/U3aSGuq0paWSro3Vnx/giphy.gif" width="30"> Portfolio Projects <img src="https://media.giphy.com/media/U3aSGuq0paWSro3Vnx/giphy.gif" width="30">
</h1>

<h2 align="center">
Independent Projects
</h2>

<h3 align="center">
Database Management
</h3>

### 1. [**University Bookshop**](https://github.com/ayazhankadessova/UniversityBookshop) 

Java app with JDBC driver to access an Oracle DB and PL/SQL triggers, supporting various functions for University Bookshop Management.

<h3 align="center">
Full-stack/Frontend
</h3>

### 2. [**LEarnBU**](https://github.com/ayazhankadessova/FinanceGame) 

LEarnBU: Web-based Financial Literacy Game built to improve students' personal finance skills. Users can choose a story to play, with each character dealing with different aspects of personal finance.

### 3. [**ToDo App**](https://github.com/ayazhankadessova/ToDoApp) 

First MERN Project implementing simple todo web app to keep track of, edit, delete daily tasks.

<h3 align="center">
Data Science/Data Analysis
</h3>

### 1. [**Convex Optimization**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Convex_Optimization)

In this project, I gained hands-on experience in implementing performance measures using Gradient Descent Methods. I explored how to optimize the algorithm's efficiency by studying the influence of different learning rates. Additionally, I utilized the Simplex Algorithm to identify optimal values, further enhancing my skills in mathematical optimization.

### 2. [**DS Babel**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/DS%20Babel)

This project demonstrates the use of Python's cursor and iterative SQL reading to write data into a CSV file. It also showcases the conversion of CSV to SQL through the use of queries and Python's sqlite3 module.

### 3. [**Scraping & Analysing Fafa.kz for Almaty Delivery Market Insights**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/FAFA) 

1.	Scraped the data from the https://fa-fa.kz/search_load/gruzy-almaty/ with Beautiful Soup in fafa_Almaty.py and wrote it in fafa_Almaty.csv
2.	Cleaned Data in fafa_Almaty.csv
3.	In fafa_Almaty.ipynb: Introduced Data,
4.	Did an Exploratory Data Analysis, 
5.	Answered 3 Business Questions through calculations and visualizations with seaborn and matplotlib.pyplot.
6.	Presented Suggestions on a profitable business model

- Summarized Projects steps in the BlogPost: https://fafkz-scraping.blogspot.com/2021/09/scraping-fafakz-for-almaty-delivery.html .

### 4. [**TOP 25 Github repos Scraper**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Github%20scraper)

Used Python's requests and beautifulsoup4 modules, returning a CSV of the TOP 25 trending repositories from Github's page (https://github.com/trending). Following information is included: Developer, Repository Name, Number of Stars.

### 5. [**Open Iris**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Open%20Iris)

1. Loaded the dataset with pandas
2. Summarized the dataset
3. Visualized the dataset with seaborn
4. Evaluated algorithms with sklearn's DecisionTreeClassifier, KNeighborsClassifier, LogisticRegression, SVC
5. Made predictions about which class of iris plant a plant belonged to based on its characteristics through training the data with sklearn's train_test_data, and showed the accuracy score.

### 6. [**NBA Game Analysis**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/NBA%20Game%20Analysis)

I immersed myself in the NBA game dataset and parsed a CSV file that described both teams' players' game activities. Using Python's Regex Module, I found keywords to extract relevant information and create separate tables for home and away teams with statistics such as FG, FGA, FG%, 3P, 3PA, and FT for all players. I also performed additional calculations for some stats.

<h3 align="center">
NLP
</h3>

### 7. [**RFM Analysis**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/RFM%20Analysis)

1. Use the public dataset: https://www.kaggle.com/olistbr/brazilian-ecommerce, namely olist_orders_dataset.csv and olist_order_payments_dataset.csv files.
2. Convert the date of delivery of the order by the original carrier (order_delivered_carrier_date) to datetime64. -> as we are going to base our calculations on it.
3. Create an index order_id and connect the datasets through it.
4. Since the dataset is not recent, we will use max + 1 instead of the current date. To create Recency, Frequency and Monetary for every customer, group the records through customer_id. -> RFM Table is ready!
5. Assigning grades. Split into a range from 1 to 5. The wider the range, the more accurate our groups are, but at the same time, it is more challenging to work with a large number of combinations.
6. Segmented_rfm Table is ready! RFM score of 413 means: r_quartile = 4, f_quartile = 1, m_quartile = 3.
7. Separately, the average recency/frequency/monetary_value values for all RFMScore can be seen using matplotlib.

### 1. [**Fine Tune Language Model**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Fine_Tune_Sentiment_Analysis)

Fune tuning for Sentiment Analysis Using PyTorch to create [bert-finetuned-semantic-chinese](https://huggingface.co/Ayazhankad/bert-finetuned-semantic-chinese). Result Model: [here](https://huggingface.co/Ayazhankad/bert-finetuned-semantic-chinese)

<h2 align="center">

University, Year 1 (2021-2022)
</h2>

### 1. [**Hospital Admitting System Simulation**](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Hospital%20Admitting)

1. Read the Patients dataset - Sheet1.csv and new_Diseases and Symptoms - Sheet1.csv.
2. Shuffled the 'Patients dataset - Sheet1.csv' and added patients to the hospital based on the following criteria using OOP for Patient and Hospital data structures:
> Checked if the admitted patients number exceeds the capacity.
> Checked if the hospital can assign two symptoms of the patient to any of the diseases it treats (get from new_Diseases and Symptoms - Sheet1.csv).
3. Recorded Admitted/not Admitted patients in 'Hospital_admitted.csv' and 'Hospital_NOTadmitted.csv'.
4. Recommended Different Lung Diseases treatment hospitals to not admitted patients by scraping https://www21.ha.org.hk/smartpatient/SPW/en-us/Useful-Resource/Patient-Group/List/?guid=ebe3f3f7-cd2b-4573-882e-cfd61eac55ac with BeautifulSoup, made a Dataframe, and created a csv of recommended hospitals.
5. Visualized the frequency of diseases of Admitted Patients with matplotlib.

**Every time the code is run, the output 'Hospital_admitted.csv', 'Hospital_NOTadmitted.csv' will be different because the 'Patients dataset - Sheet1.csv' will always be shuffled differentely.**

Hence, the bar plot will be different for every run.

<h2 align="center">
University, Year 2 (2022-2023)
</h2>

### 1. **Games in Java**

Game programes created during the COMP2026/COMP2045 (Programming and Problem-Solving; Programming Using Object-Oriented Approach) courses:

- [6-nimmit](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Games/6-nimmt)
- [Connect Four](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Games/ConnectFour)
- [Tower Defence](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Games/TowerDefense)

Skills: Inheritance/List/Exception Handling/Polymorphism/Arrays/etc.

### 2. **[Causal Inference with R practice](https://github.com/ayazhankadessova/Rpractice)**

Assignments done during the ECON3096: Causal Inference: Capturing Cause-and-Effect Relationships with Data course.

* [Assignment 1](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Rpractice/Assignment1): Counterfactual outcome, independent/dependent variables, bivariate regresion
* [Assignment 2](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Rpractice/Assignment_2): Identificantion, Multivariate Regression, Controls, Causal Diagrams, R^2, Omitting
* [Assignment 3](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Rpractice/Assignment_3): Experiment and Difference-in-Differences, DID in non-experiment setting, Matching Fixed Effects
* [Final](https://github.com/ayazhankadessova/Portfolio-Projects/tree/main/Rpractice/Final): Referee Report(black and white wage gap that shows discrimination of labor market), Replication Project (Treatment effect, Quadratic relations, Regressions, etc).

<h2 align="center">
Independent Projects
</h2>

