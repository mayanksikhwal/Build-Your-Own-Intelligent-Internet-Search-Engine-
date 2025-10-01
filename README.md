# Build-Your-Own-Intelligent-Internet-Search-Engine-

## Project Description

This project explores the capabilities of **Crawl4AI**, an open-source AI web crawler designed for efficient and large-scale data extraction. It demonstrates the basic usage of Crawl4AI, including installation, configuration of browser, crawler, and LLM settings, and examples of both basic web scraping and deep crawling strategies (specifically BFS). The goal is to showcase how Crawl4AI can be used to gather structured, markdown-formatted data for various AI and data pipeline applications.

## Tech Stack

*   **Python:** The primary programming language used for implementing the crawling logic.
*   **Crawl4AI:** The core library used for web crawling, handling browser automation, deep crawling, and data extraction.
*   **asyncio:** Used for managing asynchronous operations within the crawler.
*   **Playwright:** The underlying browser automation library used by Crawl4AI.
*   **LXML:** Used as a scraping strategy for parsing HTML content.
*   **urllib.parse:** Used for URL manipulation.
*   **json:** Used for handling JSON data, particularly in the Jobs Crawler example.
*   **pprint:** Used for pretty-printing data structures.
*   **Google Colab:** The environment where this notebook is developed and can be executed (though deep crawling on large sites is better suited for a local environment).

## How to Run

1.  **Open the notebook in Google Colab:** Upload or open the notebook file (.ipynb) in your Google Colab environment.
2.  **Install dependencies:** Run the cell with `!pip install crawl4ai` to install the necessary library.
3.  **Execute Code Cells:** Run the code cells sequentially to:
    *   See examples of basic scraping (AI News Scraper).
    *   See an example of structured data extraction using CSS selectors (Jobs Crawler).
    *   See an example of deep crawling using the BFS strategy (BFS Crawl on Wikipedia). Note that for deep crawls on large sites, running the code in a local Python environment is recommended due to potential resource limitations in Colab.
4.  **Generate `requirements.txt`:** Run the cell to generate a `requirements.txt` file listing the project's dependencies.
