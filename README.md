# Meditechy-COVID_19-Group3
This is our first group project as part of the Meditechy Python (AI) course. Members of the group are:
Etieneobong Oko, 
Ezenwalie Somto, 
Fisha Mehabaw, 
Gabriel Ntwari, 
Grace Ogundaini, 
Hamse Mohamed, 
Ibrahim Kamara,  
Ibtissam Chouja, 
IDOWU Dolapo

We are to administer the following task on a COVID-19 dataset 

Tasks 

### Import the necessary libraries 

# Load the COVID-19 dataset
# Replace with the path to the file
file_path = None 

covid_data = pd.read_csv(file_path)

# List of countries for your group - replace with the list for your group
group_countries = None

# Filter the COVID-19 data for the countries assigned to your group
group_data = covid_data[covid_data['Country/Region'].isin(group_six)]

# Display the filtered data for Group One
group_data
