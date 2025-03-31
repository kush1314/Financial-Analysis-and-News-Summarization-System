**
#  Financial Analysis & News Summarization System

## Summary
The **Financial Analysis & News Summarization System** is an all-in-one Python-based tool designed to help students and beginner investors make smarter stock investment decisions by combining **fundamental analysis (news)** and **technical analysis (price trends)**. Created by two undergraduate students passionate about finance and coding, the tool leverages real-time data, web scraping, and machine learning to deliver news summaries, price insights, and Monte Carlo-based stock simulations — all in a clean, interactive experience

---

##  Features
-  **Fundamental Analysis:** Input any stock ticker and receive 50 recent news articles with short previews.
-  **News Summarization:** Choose specific articles to summarize using a neural network model (Hugging Face's BART).
-  **Technical Analysis:** View historical prices and descriptive statistics (mean, median, standard deviation)
-  **Price Forecasting:** Run Monte Carlo simulations to generate 30,000+ possible future price paths
-  **User-Friendly Workflow:** Designed for accessibility, even for those with minimal investing experience

---

##  Technologies Used
- **Programming Language:** Python
- **Data Analysis:** pandas, NumPy, matplotlib, yfinance, pandas_datareader
- **APIs:** NewsAPI, Yahoo Finance, Hugging Face Transformers
- **Web Scraping:** BeautifulSoup, `requests`
- **NLP & Summarization:** Hugging Face BART, Transformers, `sumy`
- **Simulation:** Monte Carlo method, `scipy.stats`

---

##  Team Members & Contributions
- **Kush Patel** – Co-developed core Python logic, handled API integration, and led the technical analysis and Monte Carlo simulation work
- **Yash Dave** – Co-developed the summarization engine, built the article scraping pipeline, and contributed to design and testing
>  *Both members contributed equally across all aspects of the project*

---

##  Setup Instructions
>  Prerequisite: Python 3.8+ and pip installed

1. **Clone the repository** (if not already cloned):
   ```bash
   git clone https://github.com/yourusername/financial-analysis-project.git
   cd financial-analysis-project
2. **Install Dependencies** (if not already cloned):
  pip install -r requirements.txt
3. **API Keys** (if not already cloned):
  Add your NewsAPI key and Hugging Face token in a .env file or directly into the script variables (as used in Colab)
4. **Run Script** (if not already cloned):
  Add your NewsAPI key and Hugging Face token in a .env file or directly into the script variables (as used in Colab)

##  Demo 
>  Video: [https://youtu.be/Rylh41YR0Uk](https://drive.google.com/file/d/1LE1-mFYPCSFVon2gFHn4QLHFZCMvm5VF/view?usp=sharing)
>
> 
>  Images: https://docs.google.com/presentation/d/1_0Z-VjxM9AucvIBG8hV6ONm4XnhSelMdumdtTGJEiyc/edit?usp=sharing 

Contact
For questions or collaboration opportunities, feel free to reach out via GitHub or email!


**
