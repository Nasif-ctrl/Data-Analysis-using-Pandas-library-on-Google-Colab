# Data Analysis using Pandas library on Google Colab  

## 📝 __Overview__  
This project's objective was to demonstrate the use of various functions in Python, specifically from the Pandas library, by analyzing a dataset based on the questions in the PDF file `Questions and Answers`.  
Pandas is a powerful Python library used for data manipulation and analysis. It provides data structures like DataFrames and Series, making it easier to handle structured data.  
The programming for this project was conducted on Google Colab, a free, cloud-based platform for writing and executing Python code, which is particularly useful for data science and machine learning. It offers built-in support for GPUs and seamless integration with Google Drive. An alternative to Google Colab is Jupyter Notebook, which is not dependent on having an internet connection, unlike Google Colab.  
The computer used for this project was running on Windows 10 operating system.  
    
## 📂 __Contents__  
| File Name | File Type | Description |
|-----------|-----------|-------------|
| README | MD | Read this before anything else |
| Cust_Purch_FakeData | CSV | Dataset used for Data Analysis |
| Customer_Purchase_Data_Exercise (Solved) | IPYNB | Python Notebook with code included |
| Customer_Purchase_Data_Exercise (Unsolved) | IPYNB | Python Notebook without code included |
| Questions and Answers | PDF | File containing questions and answers derived using Python code in the IPYNB file |  
  
## ▶️ __How to Execute the Program__  
Before executing the program, download the CSV file `Cust_Purch_FakeData` and the IPYNB file from this repository. If you want to try answering the questions by yourself, you can download the IPYNB file  `Customer_Purchase_Data_Exercise (Unsolved)`. If you want to see the code already used for answering the questions, you can download the IPYNB file `Customer_Purchase_Data_Exercise (Solved)` instead. Afterwards, follow these steps:  
### If you are using Google Colab:  
•	Upload the dataset ‘Cust_Purch_FakeData’ to a folder in your Google Drive.  
•	Open a browser and go to https://colab.research.google.com.  
•	Click on File > Upload Notebook.  
•	Select and open the downloaded IPYNB file.  
•	Click on the run button adjacent to each code snippet to run the code.  
### If you are using Jupyter Notebook:  
•	If you don’t have Anaconda or Jupyter Notebook installed, visit: https://www.anaconda.com and download the installer appropriate for your OS.  
•	After downloading, double-click on the downloaded file and follow the on-screen instructions to complete the installation process.  
•	Locate and run the program ‘Anaconda Prompt’.  
•	Run Jupyter Notebook after navigating to the folder containing the downloaded IPYNB file and the CSV file. For instance, if the files are located in a folder called PythonCode in Local Disk (D:), then you have to run _D:\PythonCode>jupyter notebook_.  
•	After opening the IPYNB file, select the code snippets and click on Run to run the code.  
  
## 🔍 __Observation__  

### Dataset Overview:  
The dataset contains 30,000 entries across 20 columns, covering customer details such as age, profession, spending behaviour and credit card usage.  

### Customer Demographics:  
*	Customers' ages range from 18 to 65 years, with an average age of 41.5 years.  
*	The most common customer names, considering full names, are Henrietta Luna, Leona Ruiz, and Katie McKinney, while the most frequent first names are Willie, Francis, and Eula.  

### Spending Behavior:  
*	The maximum spending recorded is 100 CAD, while the minimum is 0 CAD, with an average spending of 49.99 CAD.  
*	Dr. Bruce Bryan and Mrs. Flora Clark did not spend anything and could be targeted with promotional deals.  
*	Mrs. Gregory Brown, Mrs. Cody Christensen, and Miss Lizzie Dixon spent 100 CAD or more, making them eligible for a loyalty reward.  

### Profession & Regional Analysis:  
*	87 customers are Structural Engineers, of which 43 are male.  
*	Dr. Roy Stanley, Mr. Lora Kennedy, Mrs. Nell Richards, and Mrs. Don McDaniel are female Structural Engineers from Alberta (AB).  
*	The two most common professions in the dataset are Preschool Teacher and Distribution Manager.  

### Credit Card and Email Analysis:  
*	1721 people use Visa, while 3536 people use either Visa or Visa Electron.  
*	Mrs. Gregory Brown spent 100 CAD using Visa.  
*	2684 credit cards are set to expire in 2019, requiring timely replacement.  
*	The top 5 most common email providers among customers are _gmail.com_, _me.com_, _outlook.com_, _live.com_, and _hotmail.com_.  
*	Miss Loretta Fletcher uses an email from "am.edu".  
*	A single credit card number ('5020000000000230') is linked to two emails: sebvajom@kol.km and acu@jatsot.ug.  

### Customer Visit Patterns:  
*	The store experiences the highest customer traffic on Saturdays.  

### Duplicate and Anomalous Entries:  
*	Two customers, Mrs. Lilly Tyler and Mrs. Peter Cain, share the same phone number: (263) 382-8004.  
  
## 📌 __Things to Keep in Mind__  
* In Google Colab, while reading the CSV file, the path in `data_root` should be customized based on the file location in your own Drive, not the one given here.  
![image](https://github.com/user-attachments/assets/a577a0e0-1ce2-46df-b517-9ab3a7225b4d)  

* In order for Google Colab to access the CSV file, you need to give it permission to do so.
