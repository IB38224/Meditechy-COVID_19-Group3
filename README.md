# Meditechy-COVID_19-Group3
This is our first group project as part of the Meditechy Python (AI) course. Members of group 3 are:
### Etieneobong Oko, 
### Ezenwalie Somto, 
### Fisha Mehabaw, 
### Gabriel Ntwari, 
### Grace Ogundaini, 
### Hamse Mohamed, 
### Ibrahim Kamara,  
### Ibtissam Chouja, 
### IDOWU Dolapo

We are to administer the following task on a COVID-19 dataset 


## Import the necessary libraries 

### Load the COVID-19 dataset
### Replace with the path to the file
file_path = None 

covid_data = pd.read_csv(file_path)

### List of countries for your group - replace with the list for your group
group_countries = None

### Filter the COVID-19 data for the countries assigned to your group
group_data = covid_data[covid_data['Country/Region'].isin(group_six)]

### Display the filtered data for Group One
group_data


# Questions to address with/in the data


### Data Cleaning:
Are there any missing values in the dataset? If so, how are they handled?
Are there any inconsistencies or anomalies in the data that need to be addressed?


### Grouping:
What is the total number of confirmed cases, deaths, and recoveries for each country in the dataset?
How does the distribution of COVID-19 cases vary across different countries?

### Pivot Tables:
Can you create a pivot table to show the total number of confirmed cases, deaths, and recoveries for each date and country?
### Time Series Analysis:
How has the number of confirmed cases changed over time for each country?
Are there any noticeable trends or patterns in the data?
### Plotting with Matplotlib/Seaborn:
Can you create a line plot showing the trend of confirmed cases over time for a specific country?
How does the number of confirmed cases compare between different countries? Can you visualize this comparison using a bar plot or a heatmap?
### Bonus:
Are there any outliers in the dataset that might indicate errors or anomalies?
Can you perform any additional analyses or visualizations that provide insights into the COVID-19 data for your assigned countries?

