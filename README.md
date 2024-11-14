# Cold Email Generator for Job Listings with Groq, LangChain, and Streamlit

This tool enables service companies to generate personalized cold emails for job opportunities by extracting job listings from a company's careers page. By using Groq, LangChain, and Streamlit, the tool can pull job descriptions, analyze their content, and customize email templates. The emails also feature relevant portfolio links sourced from a vector database based on the specific job descriptions.

## Features

- **Job Listings Extraction**: Enter the URL of a company's careers page, and the tool scrapes and extracts available job listings.
- **Email Personalization**: The extracted job descriptions inform a tailored cold email template, personalized for each job role.
- **Portfolio Matching**: Relevant portfolio links from a vector database are included based on the job description to showcase relevant experience.
- **User-Friendly Interface**: Built with Streamlit for an intuitive, web-based UI.

## Technology Stack

- **Groq**: Used for efficient data extraction from job listings on careers pages.
- **LangChain**: Powers natural language processing for job description analysis and email generation.
- **Streamlit**: Provides an interactive and accessible front-end interface for users.
- **Vector Database**: Stores portfolio data, enabling quick retrieval of relevant links based on job descriptions.

## Prerequisites

- **Python** >= 3.8
- Streamlit, Groq, LangChain, Vector Database SDK (e.g., Pinecone or Weaviate), and other dependencies (see requirements.txt)

## License

This project is licensed under the MIT License.

---

Let me know if you need further customization or help with the code implementation.
