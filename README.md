# Ciela

Hacking your academic left.


## 1. XML to Scholarly Article CSV Converter
### Description: 
This script parses an XML file containing scholarly articles and exports the data into a CSV file with predefined headings. The script also utilizes OpenAI's GPT-3.5 Turbo to generate content for specific columns based on the abstract of the articles.

### Usage:
Ensure you have the required libraries installed using pip: 

```pip install xml.etree.ElementTree csv openai python-dotenv```

Set up your OpenAI API key in a .env file.

```OPENAI_API_KEY = '<your-key>'```

Run the script by executing python ScholarlyXMLtoCSV.py.

### Inputs:
xml_file: The path to the XML file to be parsed.
csv_file: The path where the CSV file will be saved.

### Outputs: 
A CSV file containing the extracted and generated data from the XML file.