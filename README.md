# AutomatedContactInformationExtractionFromWebsites
The project involves web scraping and extracting website information including contact information and social media links.

## Problem Statement

The user faced difficulty in extracting **contact information** and social media links from websites. Previously, two separate codes were written to solve the problem. However, the project was divided into two parts for better organization and readability.


### Solution
The project has two parts:

**Part 1**: Extracting website domains with relevant keywords
The first part of the project involves fetching website domain names with relevant keywords. The following libraries were used:

 * requests
 * Beautiful Soup
 * pandas
 * urllib3
 * are used to extract website domain names containing a relevant keyword. The data is then written to an Excel file.



    
   * The program fetches website domain names with relevant keywords and writes them into an Excel file. The program sends requests to the website URLs and fetches the HTML content. Then, it extracts relevant information such as the IP address, hosting company, web hosting location, and more from the HTML content using BeautifulSoup. Finally, it saves the extracted data into an Excel file.
    
    
    
**Part 2** - Contact and Social Media Information Extraction
In the second part of the project, Python libraries such as
* pandas
* requests
* Beautiful Soup
* re 

are used to extract contact information such as phone numbers and email addresses, and social media links such as Facebook, Twitter, LinkedIn, and Instagram. The data is extracted from the website domains fetched in Part 1 and written to an Excel file.




The program reads the Excel file containing website URLs, fetches website content using requests library, and extracts relevant information using BeautifulSoup and regular expressions. It extracts phone numbers, email addresses, and social media links for each website and adds them to a DataFrame. Finally, it saves the updated DataFrame to a new Excel file.



# Conclusion
This project demonstrates how web scraping techniques can be used to extract website domain names with relevant keywords and extract contact information from the fetched website domains. By automating the process, the program saves time and effort in collecting information from various websites.


# note:
if the web site is not fetch the website name then first you can surf the website manually because there is human verification for the first time on this website:https://myip.ms/browse/sites/1/url/**dentist** is the keyword and this website retrive the keyword relevent website
  
  
  
    
