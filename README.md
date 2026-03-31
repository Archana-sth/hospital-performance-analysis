# Hospital Performance & Efficiency Analysis
![Hospital Banner](https://raw.githubusercontent.com/Archana-sth/hospital-performance-analysis/main/Images/banner.png)

[![Hospital Performance Analysis](images/banner.png)](https://github.com/Archana-sth/hospital-performance-analysis)

The project analyzes hospital performance using hospital ratings, Medicare spending and unplanned visits data. The goal is to evaluate how efficiently hospitals deliver care and to identify patterns between healthcare spending and patients outcomes.
  
By combining multiple datasets and using Python and SQL for analysis, the project explores wheather higher Medicare spending leads to better outcomes, high performing and underperforming hospitals and uncovers oppertunities for improving healthcare efficiency. 

## Objectives of the Project
* Analyze hospital performance based on **Medicare spending** and **patient return rates**  
* Identify **high performing** and **underperforming** hospitals  
* Categorize hospitals based on **efficiency** (spending vs patient outcomes) 
* Provide insights for hospital management and stakeholders 
* Visualize trend and patterns to support **data driven decision making**  

## Data Source
The dataset used in this project are sourced from publicly available healthcare data provided by the **Centers for Medicaid and Medicare Services (CMS)** 

**1. Hospital Information dataset**  
https://data.cms.gov/provider-data/dataset/xubh-q36u
* Contains hospital details such as facility name, states and overall rating  

**2. Medicare Spending dataset**  
https://data.cms.gov/provider-data/dataset/rrqw-56er#data-table  
* Provides average Medicare spending for each hospital  

**3. Unplanned visits Dataset**  
https://data.cms.gov/provider-data/dataset/632h-zaca
* Includes visit score, number of patients and Unplanned return visits  

## Data Analysis Steps
* Collected hospital data (hospital characteristics, medicare spending, unplanned visits)  
* Cleaned the datasets handling missing/ 'Not Available" values, dropping unnecessary columns, checking duplicates, renaming columns and updating datatypes  
* Created SQL tables and joined them using facility_id 
* Calculated patient return rate and average spending per hospital
* Analyzed patterns in spending vs return rate   
* Categorized hospitals by performance (Efficient, Average, Poor) 
* Identified top and bottom hospitals by efficiency  
* Visualized findings using charts  

## Key Findings
* Highest rated hospitals tend to operate more efficiently and spend less on average  
* Higher spending alone does not guarantee better patient outcomes  
* Most hospitals fall within average efficiency range only small percentage of hospitals are high spending and poor performing  
* Certain hospitals achieve low spending and low patient return rate (models of efficiency)  
* Certain states have more efficient hospitals than others  

## Tools & Libraries Used
* **Python** - Programming language used for data processing, analysis and visulization 
* **SQL** - Language used for data aggredation, joining tables and calculating hospital analysis
* **Pandas** - Library used for data cleaning, manipulation and analysis  
* **Matplotlib/Seaborn** - Library used for visulization  
* **Jupyter Notebook** - Environment used to writing code, running analysis and documenting results  
* **Bash** - Used for running scripts, managing files and project setup  

## Instructions
Follow the steps below to run this project locally:

* Clone the repository to your machine:  
git clone https://github.com/Archana-sth/hospital-performance-analysis.git 

* Create and Activate virtual Environment:   
   + **Mac/Linux:**  
        python3 -m venv hospital_performance_env  
        source hospital_performance_env/bin/activate
    + **windows:**  
        python -m venv hospital_performance_env  
        hospital_performance_env\Scripts\activate
* Install required package:   
        pip install -r requirements.txt  
* Run the Project  
    + Open the jupyter Noetbook  
    + Then open the project notebook file and run all cells
* Deactivate Virtual Environment  
    + deactivate  

## Conclusion  

## Acknowledgements

* This project was developed with guidance and resources from **Online tutorials and Google searches**  
* AI assistant **ChatGpt** was used for suggestions on project workflow, clarifying concepts, improving analysis steps 