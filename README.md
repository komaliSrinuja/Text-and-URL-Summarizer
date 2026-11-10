# Text-and-URL-Summarizer

## Project Overview
Text and URL Summarizer is a Python-based NLP project that generates concise summaries from user-provided text or webpage URLs. It uses the **BART (Bidirectional and Auto-Regressive Transformers)** model to generate meaningful summaries while preserving the important information.

## Features
- Summarizes user-provided text.
- Accepts webpage URLs and extracts article content.
- Generates summaries using a pretrained BART model.
- Converts lengthy content into short, meaningful summaries.
- Provides an easy way to understand long articles quickly.

## Technologies Used
- Python
- Flask
- Natural Language Processing (NLP)
- Hugging Face Transformers
- BART Pretrained Model
- HTML, CSS
- Requests and BeautifulSoup

## How It Works
1. The user enters text or provides a webpage URL.
2. For URL input, the application extracts the webpage content.
3. The extracted text is processed and passed to the BART model.
4. The model generates a concise summary.
5. The generated summary is displayed to the user.

## Project Structure

```text
Text-and-URL-Summarizer/
│
├── Text_and_URL_Summarizer.ipynb
├── README.md
└── requirements.txt
```

## Installation and Setup

**Step 1: Clone the Repository**

```bash
git clone <your-repository-url>
```

**Step 2: Install Required Libraries**

```bash
pip install transformers torch flask requests beautifulsoup4
```

**Step 3: Run the Project**

Open the Jupyter Notebook:

```bash
jupyter notebook Text_and_URL_Summarizer.ipynb
```

Run the notebook cells in sequence.

## Applications
- Summarizing lengthy articles and blog posts.
- Extracting important information from websites.
- Creating short notes from lengthy content.
- Saving time while reading online information.

## Future Enhancements
- Support for multiple languages.
- Adjustable summary length.
- Downloadable summaries.
- Improved webpage content extraction.
- Deployment as a web application.

## Author
**Komali Srinuja**

