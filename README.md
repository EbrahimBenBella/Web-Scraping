# Web-Scraping


```markdown
# Web Scraping Task: HTML Page Data Extraction

This project involves performing web scraping on an HTML page to extract specific elements and organize the data into structured formats like CSV and JSON. Below are the task details and steps followed to achieve the goals.

---

## Task Objectives

1. **Extract Text Data**  
   Extract headings, paragraphs, and list items into a structured CSV file.  
   - **Output**: `Extract_Text_Data.CSV`

2. **Extract Table Data**  
   Extract data from the table (Product Name, Price, Stock Status) into a CSV file.  
   - **Output**: `Extract_Table_Data.CSV`

3. **Extract Product Information**  
   Extract details of book cards at the bottom of the page (Title, Price, Availability, Button Text) into a JSON file.  
   - **Output**: `Product_Information.JSON`

4. **Extract Form Details**  
   Extract details from the form, such as field name, input type, and default values, into a JSON file.  
   - **Output**: `Form_Details.JSON`

5. **Extract Links and Multimedia**  
   Extract hyperlinks, video links, and related metadata into a JSON file.  
   - **Output**: `Links_and_Multimedia.JSON`

6. **Scraping Challenge**  
   Extract details from the Featured Products section, including:
   - Product Name
   - Hidden Price
   - Available Colors
   - Product ID  
   - **Output**: `Featured_Products.JSON`

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `BeautifulSoup` for HTML parsing.
  - `requests` for retrieving the web page.
  - `csv` for saving data into CSV format.
  - `json` for saving data into JSON format.

---

## Steps to Execute the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### 2. Install Dependencies
Install the required Python libraries using the following command:
```bash
pip install -r requirements.txt
```

### 3. Run the Script
Execute the Python script to perform all tasks:
```bash
python scrape_data.py
```

### 4. Outputs
- `Extract_Text_Data.CSV`: Contains headings, paragraphs, and list item texts.
- `Extract_Table_Data.CSV`: Contains table data (Product Name, Price, Stock Status).
- `Product_Information.JSON`: Contains book card details.
- `Form_Details.JSON`: Contains form input details.
- `Links_and_Multimedia.JSON`: Contains hyperlinks and video links.
- `Featured_Products.JSON`: Contains details of featured products.

---

## References

- [Python CSV Writing Tutorial](https://www.pythontutorial.net/python-basics/python-write-csv-file/)
- [Converting Python Dictionary to JSON](https://www.geeksforgeeks.org/how-to-convert-python-dictionary-to-json/)
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

---

## Notes

- The script assumes that the provided HTML file (`https://www.baraasallout.com/test.html`) is accessible locally or online.
- For any issues, feel free to create an issue in this repository 





