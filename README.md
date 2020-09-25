
### **Savings Decission Automation** 
The project aims to explore the capabilities of a pipeline to use a persons dataset, a product dataset and specific business rules to produce a match between a person and an investment portfolio.

### **Status**
Design: gather information to define the scope of the project.

### **Work plan**
0. Design
1. Define business rules:
    - how are we going to segment the persons dataset
    - what kind of portfolios are we going to group
    - what are the rules that are going to link persons segments and product portfolios 
2. Define the processes
    - data cleaning
        - selecting the relevant variables (columns)
        - deciding about null values (in principle, eliminate)
    - user input data
        - chose between a general demonstration or a ones specific customer demostration
    - pipeline procedures
        - assigning every person to a segment
        - assign a portfolio to each segment
        - for each customer, depending on speficic data (e.g. ammount+ selecting criteria), select the specific assets that will conform the portfolio
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

### **Technology stack**
Python, Pandas, Scipy, Scikit-learn, etc. Indicate the technological nature of the software, including primary programming language(s), main libraries and whether the software is intended as standalone or as a module in a framework or other ecosystem.

### **Core technical concepts and inspiration**
Why does it exist? Frame your project for the potential user. Compare/contrast your project with other, similar projects so the user knows how it is different from those projects. Highlight the technical concepts that your project demonstrates or supports. Keep it very brief.

### **Configuration**
Requeriments, prerequisites, dependencies, installation instructions.

### **Usage**
Parameters, return values, known issues, thrown errors.

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
Next steps, features planned, known bugs (shortlist).

### **Further info**
Credits, alternatives, references, license.

### **Contact info**
Getting help, getting involved, hire me please.


