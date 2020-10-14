![Image](https://content.api.news/v3/images/bin/0909e514b5fc28ed3baf1b70fa7bb773)

### **Savings Decission Automation** 
The project aims to explore the capabilities of a pipeline to use a persons dataset, a product dataset and specific business rules to produce a match between a person and an investment portfolio.

### **Status**
- Design: gather information to define the scope of the project
- Define business rules:
    - segments of people
    - portfolios
    - rules that link segments and portfolios
    - rules that personalize a portfolio for a person
- Operation:
    - assign a segment to a specific portfolio
    - optimize a portfolio for a specific person


### **Work plan**
0. Design :heavy_check_mark:
1. Define business rules
    - how are we going to segment the persons dataset
    - what kind of portfolios are we going to group
    - what are the rules that are going to link persons segments and product portfolios 
2. Define the basic processes

   a. Preparation
    - data cleaning
        - exploratory data analysis
        - selecting the relevant variables (columns)
        - deciding about null values (in principle, eliminate)
        
   b. Operation
    - user input data
        - chose between a general demonstration or a one specific customer demostration
    - pipeline procedures
        - assigning every person to a segment
        - define portfolio classes
        - assign a portfolio class to each segment
        - for each customer, depending on speficic data (e.g. amount+ selecting criteria), select the specific assets that will conform the portfolio
    - delivery
        - output: a summary of segments and portfolios or a one customer recommendation
3. Define complementary processes
    - new data recommendation
        - extract the basic person variables necesary
        - create a user input data for these variables
        - create a pipeline to deliver a particular recommendation for this specific data
     - unsupervised classification
        - generate a clustering for persons
        - generate a clustering for products
        - try to invoke business rules to link persons and products
     - whitebox business rules
        - transpanrency in business rules used
        - possibility of using business rules as input (fine tuning)

### **Technology stack**
Python, Pandas, Numpy, Pipelines, Scikit-learn.
Jupyter, Pycharm

### **Core technical concepts and inspiration**
Algorithms have transformed many industries, and the finacial sector is not an exception. Among many other human processes that have been automated, the investment decission advisory based on robots has developed consistently since 2008. 
Although they will find structural and status quo resistances, we believe there is a future for these tools (the pandemic will accelerate the change in the way in which we deal with our finances in a "remote" environment).
The aim of this project is to replicate in an academical environment the processes that take place in these robo-advisers, in order to challenge them with a naïve view, and to try to bring new concepts such as "white box" focus or the use of deep learning in the advisory process. 

### **Links*
 (https://www.forbes.com/advisor/investing/what-is-robo-advisor/)
 
 
 (https://en.wikipedia.org/wiki/Robo-advisor)
 
 
 (https://www.kaggle.com/stefanoleone992/mutual-funds-and-etfs?select=Mutual+Funds.csv)
 
 
 (https://data.world/cfpb/financial-well-being-survey-data)

### **Usage**
 

### **Folder structure**
```
└── project
    ├── __trash__
    ├── .gitignore
    ├── .env
    ├── requeriments.txt
    ├── README.md
    ├── main_script.py
    ├── notebooks
    │   ├── notebook1.ipynb
    │   └── notebook2.ipynb
    ├── package1
    │   ├── module1.py
    │   └── module2.py
    └── data
        ├── raw
        ├── processed
        └── results
```

> Do not forget to include `__trash__` and `.env` in `.gitignore` 

### **ToDo**
- Documentation on business rules
- Data cleaning: NaN for people and products data
- Data cleaning: exclude institutional funds
- Define questionary to identify customer profile
- Define an aggregated report on the proposed selection of funds
- Define comments on the report
- Define variables to use in the unsupervised classification (for people and products)
- Application to manage basic rules of each portfolio in the dictionary

### **Further info**
 

### **Contact info**
 


