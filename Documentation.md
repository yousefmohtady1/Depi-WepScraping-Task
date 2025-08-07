Documentation



1\. Approach

The project was developed to scrape different types of data from a test HTML page.  

The work was divided into six main tasks:

1\. **Extract text data** – Scraping paragraphs, headings, and other textual content.

2\. **Extract table data** – Scraping table information.

3\. **Extract product card data** – Scraping product names, prices, and Availability.

4\. **Extract form details** – Scraping form input names, types, and values.

5\. **Extract links and multimedia** – Scraping hyperlinks and videos.

6\. **Featured products challenge** – Scraping product name, hidden price, colors and id from a specific section.



In each step, I examined the HTML structure, identified the required tags and attributes, and used targeted BeautifulSoup methods to extract relevant data. The results of each step were stored in Python data structures and then saved to CSV or JSON files as required.



---



2\. Tools Used

\- **Python** → Main programming language.

\- **BeautifulSoup (bs4)** → For HTML parsing and element selection.

\- **Requests** → To fetch HTML content from the local test page.

\- **CSV \& JSON Modules** → For saving extracted data.



---



3\. Challenges Faced

\- **HTML Structure Variations:**  

&nbsp; The HTML page had different structures for each section, so each scraping step required a slightly different approach.

&nbsp; 

