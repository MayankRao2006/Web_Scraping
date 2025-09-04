📚 Book Scraper Project

This project demonstrates web scraping and data extraction from Books to Scrape
 using Python.
It is divided into two stages: scraping raw HTML files and creating structured DataFrames.

📂 Project Structure
.
├── Scraping_Data.ipynb        # Notebook to scrape website and save 50 HTML files

├── Creating_DataFrames.ipynb  # Notebook to parse HTML files and build DataFrame

├── Extracted_data.csv         # Final dataset (Book Name, Price, Ratings)

├── htmls/                     # Folder containing 50 scraped HTML files

🚀 Workflow

Scraping_Data.ipynb

Sends HTTP requests to Books to Scrape.

Extracts HTML content for all the 50 pages.

Saves them in the htmls/ folder for offline parsing.

Creating_DataFrames.ipynb

Reads the saved HTML files.

Extracts Book Title, Price, and Ratings.

Stores the results in a Pandas DataFrame.

Exports the dataset to Extracted_data.csv.

Extracted_data.csv

Cleaned and structured dataset with three columns:

Book Name

Price

Ratings

📊 Example Output
Book Name	Price	Ratings
A Light in the Attic	£51.77	Three
Tipping the Velvet	£53.74	One
Soumission	£50.10	One
🛠️ Tech Stack

Python 3

BeautifulSoup4 → HTML parsing

Requests → HTTP requests

Pandas → Data handling & CSV export

Jupyter Notebook → Interactive workflow

📜 Ethical Considerations

This project was created only for educational purposes.

The website Books to Scrape is intentionally designed for practicing web scraping.

I strictly adhere to data privacy principles, follow robots.txt, and keep GDPR/CCPA best practices in mind while scraping.

▶️ How to Run

Clone this repository:

https://github.com/MayankRao2006/Web_Scraping


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebooks:

jupyter notebook
