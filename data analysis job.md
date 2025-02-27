# **Report on Data Analysis of Job Postings**

## **Objective**
The notebook analyzes job postings to extract insights such as:
- The number of job postings per website.
- Text cleaning and processing of job descriptions.
- Identification of top hard skills required in data-related job listings.

## **Data Processing Steps**
### **1. Loading Data**  
- The dataset `gsearch_jobs.csv` is loaded using pandas.
- The first few rows are displayed to understand its structure.

### **2. Cleaning Job Descriptions**  
- Removing missing job descriptions.
- Converting text to lowercase and removing special characters.

### **3. Analyzing Job Postings by Website**  
- Counting the number of job postings from each source.

### **4. Extracting Required Hard Skills**  
- Identifies common hard skills like Python, SQL, Excel, Tableau, etc.
- Uses regex patterns to extract skills from job descriptions.

## **Preliminary Insights**
- The number of job postings per website is computed.
- The most frequently mentioned hard skills in job descriptions are identified.

## **Next Steps**
- Implement data visualization for better insights.
- Perform sentiment analysis on job descriptions.
- Explore trends in job postings over time.

Data source: https://www.kaggle.com/datasets/lukebarousse/data-analyst-job-postings-google-search
