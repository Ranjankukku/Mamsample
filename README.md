# Mamsample

## QUESTION 1: [TOTAL MARKS: 25]

### **Q1(a): Using the Generic Data Analytics Pipeline**
**Question:** Using the topic from your CA682 visualisation assignment, apply the Generic Data Analytics Pipeline to describe how the data may have been Gathered, Processed, Analysed, Presented and Preserved. Give a brief description of the activities at each stage (1-2 sentences) and identify any specific tools that you did or would use. If you didn’t specifically perform any stage then you can make assumptions or predictions about the actions and tools.

**Answer:**  
- **Gathering:** Data was collected from online surveys about student feedback on online teaching in 2020 using tools like Google Forms or SurveyMonkey.  
- **Processing:** The raw data was cleaned and formatted using Python libraries such as Pandas to remove duplicates and handle missing values.  
- **Analysis:** Statistical techniques were applied using R or Python to identify trends in feedback, such as satisfaction levels or common complaints.  
- **Presenting:** Visualisations were created using Tableau or Matplotlib to present insights through bar charts and heatmaps.  
- **Preserving:** The processed data and visualisations were stored in cloud storage (e.g., Google Drive) for future reference.

---

### **Q1(b): Data Attributes**
**Question:** For each of the following data attributes (A-D), choose all of the following descriptions that can apply: Qualitative, Quantitative, Discrete, Continuous, Nominal, Ordinal, Interval, Ratio.

**Answer:**  
- **A. Number of bicycles owned per household:** Quantitative, Discrete, Ratio.  
- **B. Average time taken to commute each day:** Quantitative, Continuous, Ratio.  
- **C. Mode of transport used to commute on Monday:** Qualitative, Nominal.  
- **D. Motor vehicle safety rating (Gold, Silver, Bronze):** Qualitative, Ordinal.

---

### **Q1(c): Big Data Classification**
**Question:** Which of the following situations is most likely to be classified as big data? Explain why your choice is most likely to produce big data.

**Answer:**  
- **Choice:** A - Viewing data for Netflix subscribers including the show and the date watched and social media sentiment analysis responding to the show.  
- **Reasoning:** This scenario involves large volumes of structured (viewing history) and unstructured (social media sentiment) data with high velocity and variety—key characteristics of big data.

---

## QUESTION 2: [TOTAL MARKS: 25]

### **Q2(a): 
Given the following brief to design a system for a data collection task: 

“At the request of the Irish Government, you are preparing a report on the impact of COVID-19 restrictions on working and commuting behaviour in Ireland during 2020 comparing it to surveys and records from 2019 and 2009. You have data available from data.gov.ie showing pedestrian footfall in the central shopping area, records from the traffic monitoring cameras on the main arterial routes (vehicle count), survey data on working from home practises as well as weather and standard economic (business growth, median wage, import/export figures, etc.) information. You have permission to conduct further consumer surveys as required. The data from the report will need to be accessed and queried on an ongoing basis by many government departments to monitor the impact of policy decisions.”
![image](https://github.com/user-attachments/assets/f55585bf-d72b-46af-9f97-491485dd2fba)

Designing a Data Collection System**
**Question:** List three important questions you would ask your client. Describe the data and/or specific file formats that you are likely to use in collecting and storing the data. Suggest a type of database storage approach for this project.

**Answer:**  
- **Questions:**
  1. What are the key metrics or insights you aim to derive from this report?  
  2. How frequently will the data need to be updated or accessed?  
  3. Are there any privacy concerns or regulations we need to adhere to?  

- **Data/File Formats:** CSV for survey results; JSON for API-collected traffic data; SQL databases for structured economic information.  

- **Database Storage Approach:** A relational database (e.g., PostgreSQL) for structured data due to its ability to handle complex queries efficiently.

---

### **Q2(b): Metadata Description**

(i)	Give simple example metadata (at least 5 elements) describing your mobile phone (or your computer if you don’t have a mobile phone).  

(ii)	For each metadata element, identify if it is Descriptive, Administrative or Structural.

(iii)	If I was to collect and integrate data about the electronic devices used by all CA682 students then, in your own words, how would using a standard change the quality of metadata data? Identify one potential difficulty with enforcing a metadata standard. 
![image](https://github.com/user-attachments/assets/51c27c62-ccfb-4fb3-a1b1-673a9c907cea)

**Question:** Provide example metadata elements for your mobile phone/computer and classify them as Descriptive, Administrative or Structural.

**Answer:**  
- Example Metadata:  
  - Device Name (Descriptive)  
  - Operating System Version (Administrative)  
  - File Directory Structure (Structural)  
  - Storage Capacity (Administrative)  
  - Screen Resolution (Descriptive).  

Using a standard improves metadata quality by ensuring consistency across datasets but enforcing it can be challenging due to varying interpretations of standards.

---

### **Q2(c): Web Scraping Process**
In your own words, describe the process of scraping data from a website. Give two (2) rules that you should remember when using this as data source.![image](https://github.com/user-attachments/assets/0cca3780-ba36-4564-a59e-011d873573f3)


**Answer:**  
- **Process:** Web scraping involves sending HTTP requests to a website's server, extracting HTML content using libraries like BeautifulSoup in Python, and parsing it into structured formats like CSV or JSON.
- **Rules:**
  1. Always check and adhere to the website's terms of service.
  2. Avoid overloading servers by implementing rate limits on requests.

---

## QUESTION 3: [TOTAL MARKS: 25]

Please download and use it to answer the question. The dataset contains statistics for the Road Safety Authority Ireland on injuries and deaths for road users (cyclists, pedestrians, passengers and drivers) grouped by age.![image](https://github.com/user-attachments/assets/01f75008-caf0-4c9d-8835-e25452e36009)


### **Q3(a): Errors in Dataset**
**Question:** Identify 3 different possible errors or artefacts in the dataset linked above. Give the tool or tools you used. You may use any tool that you like.![image](https://github.com/user-attachments/assets/032e7a97-9675-4481-8f87-46624e1c08c2)


**Answer Example Errors:**
1. Missing values in age groups.
2. Inconsistent formatting for dates.
3. Duplicate entries for certain road user categories.

Tools like Excel or Python's Pandas library can be used for error detection.

---

### **Q3(b-d): Addressing Errors & Sensitive Data**
Q 3(b)	[6 Marks]

Identify how each error or artefact is most likely to have been introduced, specifying the phase from the generic data analytics pipeline. State any assumptions.

Answer:

Q 3(c)	[6 Marks]

What data quality methods would you suggest using to either avoid or mitigate the error? Why would your suggestion improve data quality?

Answer:

Q 3(d)	[6 Marks]
(i)	Can you identify any potential personal or sensitive data in the provided sample dataset? Why or why not? 
(ii)	What process should you follow if you want to legally work with personal or sensitive data?
![image](https://github.com/user-attachments/assets/34bbd5c6-657e-46a2-9be9-9e4892ef3c17)


For brevity:
- Errors are often introduced during *data gathering* or *processing*. Mitigation methods include validation checks during entry.
- Sensitive data should be anonymized before analysis; legal compliance involves adhering to GDPR guidelines if applicable.

---

## QUESTION 4: [TOTAL MARKS: 25]

### **Q4(a): Visualisation Creation**
**Question:** Create a visualisation showing expenditure distribution by staff level across quarters in 2019.

**Answer Example Graph Type:** A stacked bar chart created using Tableau/Excel with clear labels for staff levels and quarters.

---

### **Q4(b-d): Graph Identification & Justification**
For specific graph types:
- Use scatter plots for comparing energy efficiency ratings vs price.
- Preattentive features include color contrast or size variations for immediate attention capture.

---

## QUESTION 5: [TOTAL MARKS: 25]
<img width="348" alt="image" src="https://github.com/user-attachments/assets/08b97ebc-b2b9-4353-b0dd-f0f8945ff20e">

### **Q5(a-d): Communication Purpose & Visual Attributes**
Focus on identifying design flaws in graphs:
- Problems might include misleading scales or poor color choices.
- Improvements involve aligning with Gestalt principles like proximity or similarity for better clarity.

---
