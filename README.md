# AI Web Scraper

## Overview

The **AI Web Scraper** is a powerful and flexible tool designed to extract structured data from any website and present it in a tabular format. Leveraging the power of AI with **LangChain's OllamaLLM** and **BrightData services**, the scraper can handle dynamic and complex web pages, including those protected by CAPTCHAs.

---

## Features

- **AI-Powered Extraction**: Utilizes LangChain's OllamaLLM to intelligently parse web content and extract relevant details.
- **CAPTCHA Handling**: Automatically detects and solves CAPTCHAs using BrightData services.
- **Flexible Input**: Accepts any website URL and user-defined requirements for data extraction.
- **Tabular Output**: Presents the scraped data in a clean and easy-to-use tabular format.
- **Customizable**: Easily extendable to handle specific scraping requirements and custom data formats.

---

## Technology Stack

- **Programming Language**: Python
- **AI Framework**: LangChain
- **LLM**: OllamaLLM
- **CAPTCHA Solver**: BrightData services
- **Web Framework**: Streamlit (for user interface)
- **Web Scraping Libraries**: BeautifulSoup, Selenium (optional for dynamic content)

---

## Installation

### Prerequisites

1. Python 3.7 or higher
2. A virtual environment (recommended)
3. BrightData API credentials

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-web-scraper.git
   cd ai-web-scraper
   ```

2. Set up a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Add your BrightData API credentials to a `.env` file:
   ```
   BRIGHTDATA_API_KEY=your_brightdata_api_key
   ```

5. Start the application:
   ```bash
   streamlit run main.py
   ```

---

## Usage

1. Open the application in your browser (usually at `http://localhost:8501`).
2. Enter the website URL you want to scrape.
3. Specify the required data fields.
4. If the website uses CAPTCHAs, the scraper will handle them automatically.
5. View the extracted data in a tabular format.
6. Export the data as a CSV file if needed.

---

## Project Structure

```
AI-Web-Scraper/
├── main.py               # Entry point of the application
├── scraper/
│   ├── ai_scraper.py     # Core scraping logic using OllamaLLM
│   ├── captcha_solver.py # CAPTCHA handling with BrightData
│   └── utils.py          # Utility functions
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── .env                  # API credentials (not included in repo)
```

---

## Dependencies

- `streamlit`
- `langchain`
- `ollama`
- `beautifulsoup4`
- `selenium`
- `brightdata`
- `dotenv`

---

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or support, feel free to reach out:

- **Email**: akshayhanchate@example.com
- **GitHub**: [yourusername](https://github.com/yourusername)
