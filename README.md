![Image](https://content.api.news/v3/images/bin/0909e514b5fc28ed3baf1b70fa7bb773)

### **Savings Decission Automation**
The project aims to explore the capabilities of a pipeline to use a persons dataset, a product dataset and specific business rules to produce a match between a person and an investment portfolio.

### **Status**
- Phase one delivered

### **Work plan**
0. Design

1. Define business rules
    - how are we going to segment the persons dataset
    - what kind of portfolios are we going to group
    - what are the rules that are going to link persons segments and product portfolios


2. Define the basic processes

a.  Preparation and data cleaning
  - exploratory data analysis
  - selecting the relevant variables (columns)
  - eliminiate null values

b. Operation
  - input clean data for persons and products
  - process the files with reference data on business rules
  - input specific person data from a questionnaire

  - pipeline procedures
        - assigning every person to a segment
        - define portfolio classes
        - assign a portfolio class to each segment
        - for each person, depending on speficic data (e.g. amount+ selecting criteria), select the specific assets that will conform the portfolio
  - delivery
        - output:
          - a summary of segments and portfolios
          - a random choice of an existing person and his recomended portfolio
          - a recommendedation to a new person based on the input from a questionnaire


### **Technology stack**
Python, Pandas, Numpy, Matplotlib.
Jupyter, Pycharm, Atom

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

### **Next steps**
- Provide a report advisory via web, email
- Whitebox business rules
   - transpanrency in business rules used
   - possibility of using business rules as input (customization)
- Define an unsupervised classification
    - generate a clustering for persons
    - generate a clustering for products
    - try to invoke business rules to link persons and products


### **Further info**


### **Contact info**
