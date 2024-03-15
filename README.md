This Python toolkit enables seamless extraction and analysis of textual data from URLs, offering a range of linguistic insights. It's a handy tool for researchers, data scientists, and anyone interested in exploring textual content programmatically.
Features
Web Scraping: Extract text content from URLs specified in an Excel file.
Text Analysis: Compute various linguistic metrics including word count, sentence count, sentiment analysis, and more.
Customization: Easily customize stop words, sentiment dictionaries, and derived variables to suit your specific needs.
Readability Assessment: Evaluate text complexity using the Flesch-Kincaid Readability Index (Fog Index).
User-Friendly Output: Results are saved in an Excel file for easy access and analysis.
Why Use This Toolkit?
Efficiency: Automate the tedious task of extracting and analyzing text data from multiple URLs.
Versatility: Customize the toolkit to perform specific text processing tasks based on your requirements.
Insightful Analysis: Gain valuable insights into the linguistic characteristics and sentiment of the text content.
Usage
Data Input: Prepare an input Excel file (input.xlsx) containing URL IDs and corresponding URLs.
Execute Script: Run the provided Python script to perform data extraction and analysis.
Review Results: Access the output Excel file (text_analysis_output.xlsx) to view computed variables and derived features for each URL.
Dependencies
requests
BeautifulSoup
pandas
spacy
TextBlob
nltk
textstat
