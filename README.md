# Business Intelligence and Data Analytics (BIDA)

A comprehensive collection of laboratory experiments, assignments, and practical implementations developed for the **Business Intelligence and Data Analytics (BCB701)** course.

This repository demonstrates fundamental and advanced concepts in Business Intelligence, Data Analytics, Data Mining, Machine Learning, Data Visualization, Interactive Business Dashboards, Social Network Analysis, and Text / Sentiment Analytics using Python, Jupyter Notebooks, and Microsoft Excel.

---

## Course Overview

Business Intelligence and Data Analytics focuses on extracting actionable insights from data to support decision-making processes. The course covers descriptive, predictive, and prescriptive analytics through practical implementations involving:
- Interactive Business Reporting, Pivot Tables & Excel Dashboards
- Data Preprocessing and Exploration
- Cluster Analysis and Market Basket Mining
- Supervised and Unsupervised Machine Learning
- Text Mining, Natural Language Processing, and Sentiment Analysis
- Topic Modeling and Web Analytics
- Social Network Graph Analytics
- Web Hyperlink Structure & PageRank Algorithm

---

## Repository Structure

```text
BIDA/
│
├── .venv/                         # Python virtual environment (ignored)
├── Datasets/                      # Input datasets
│   └── Mall_Customers.csv         # Customer dataset for clustering analysis
├── Images/                        # Visualizations and output plots
│   ├── program5-image1.png
│   ├── program5-image2.png
│   ├── program-6.png
│   ├── program-8.png
│   ├── program-9.png
│   ├── program-10-image-1.png
│   ├── program-10-image-2.png
│   ├── program-11-image-1.png
│   ├── program-11-image-2.png
│   └── program-12.png
├── output/                        # Generated output data files
│   └── customer_reviews.xlsx      # Generated dataset for sentiment analysis
├── Program 1/                     # Exp 01: Student Retention Excel Dashboard
│   ├── Program 1.pdf              # Step-by-step process & documentation guide
│   └── Program 1.xlsx             # Interactive Excel dashboard with PivotTables & Slicers
├── 05.ipynb                       # Exp 05: K-Means Customer Segmentation
├── 06.ipynb                       # Exp 06: Apriori Association Rule Mining
├── 07.ipynb                       # Exp 07: Sentiment Analysis with Naïve Bayes
├── 08.ipynb                       # Exp 08: Topic Modeling with LDA
├── 09.ipynb                       # Exp 09: Social Network Analysis (SNA)
├── 10.ipynb                       # Exp 10: Web Scraping & Topic Trends (WordCloud/TF-IDF)
├── 11.ipynb                       # Exp 11: Sentiment Analysis on Extracted Web Comments
├── 12.ipynb                       # Exp 12: Web Hyperlink Structure Analysis (PageRank)
├── requirements.txt               # Project dependencies
└── README.md                      # Project documentation
```

---

## Course Modules

### Module 1 – Business Intelligence Fundamentals
- Business Intelligence and Decision Support Systems
- Business Analytics Frameworks
- Artificial Intelligence & Conversational AI

### Module 2 – Descriptive Analytics
- Nature of Data & Preprocessing
- Statistical Modeling & Exploratory Data Analysis
- Regression Analysis & Big Data Overview

### Module 3 – Business Intelligence & Data Warehousing
- Data Warehousing Architecture & ETL Processes
- Business Reporting & Interactive Dashboards (Excel PivotTables & Slicers)
- Data Visualization Tools (Excel, Tableau, Power BI)

### Module 4 – Predictive Analytics
- Data Mining & Supervised Classification
- Unsupervised Clustering & Segmentation
- Association Rule Mining & Optimization

### Module 5 – Text, Web & Social Analytics
- Natural Language Processing (NLP) & Text Mining
- Sentiment Analysis (VADER, Naïve Bayes)
- Topic Modeling (LDA, TF-IDF)
- Social Network Analysis (Centrality Measures & Graph Theory)
- Web Structure Mining & Link Analysis (PageRank)

---

## Implemented Laboratory Experiments

| No. | Experiment Title | Description | Resource / Notebook |
|:---:|:---|:---|:---:|
| **01** | **Student Retention Analysis Dashboard** | Interactive business intelligence dashboard created in **Microsoft Excel** using **PivotTables**, **PivotCharts**, and connected **Slicers** to analyze student retention, dropout rates, academic performance, and demographic factors. | [`Program 1.xlsx`](./Program%201/Program%201.xlsx) <br> ([`Guide`](./Program%201/Program%201.pdf)) |
| **05** | **Customer Segmentation** | Segment customers based on annual income and spending score using **K-Means Clustering** and the Elbow Method. | [`05.ipynb`](./05.ipynb) |
| **06** | **Association Rule Mining** | Identify frequent itemsets and generate association rules from transaction data using the **Apriori Algorithm** (`mlxtend`). | [`06.ipynb`](./06.ipynb) |
| **07** | **Sentiment Classification** | Classify customer product reviews into positive, negative, or neutral sentiment using a **Multinomial Naïve Bayes** classifier. | [`07.ipynb`](./07.ipynb) |
| **08** | **Topic Modeling with LDA** | Extract key terms and uncover latent topics across articles using **Latent Dirichlet Allocation (LDA)** and CountVectorizer. | [`08.ipynb`](./08.ipynb) |
| **09** | **Social Network Analysis** | Construct a social network graph and identify influential nodes using **Degree, Closeness, and Betweenness Centrality** (`networkx`). | [`09.ipynb`](./09.ipynb) |
| **10** | **Web Scraping & Topic Identification** | Extract text content, clean and preprocess data with NLTK, identify trending keywords using **TF-IDF & CountVectorizer**, and visualize topics via **WordCloud**. | [`10.ipynb`](./10.ipynb) |
| **11** | **Sentiment Analysis on Web Data** | Extract user discussion comments, compute sentiment compound scores using NLTK's **VADER `SentimentIntensityAnalyzer`**, and visualize distribution via Pie & Bar charts. | [`11.ipynb`](./11.ipynb) |
| **12** | **Web Hyperlink Analysis & PageRank** | Model a website's internal and external link architecture as a directed graph using `networkx`, evaluate key pages using the **PageRank Algorithm**, and visualize the hyperlink network. | [`12.ipynb`](./12.ipynb) |

---

## Technologies Used

- **Spreadsheet & BI Tools:** `Microsoft Excel` (PivotTables, PivotCharts, Interactive Slicers, Data Tables)
- **Language:** Python 3.12+
- **Data Manipulation:** `pandas`, `numpy`, `openpyxl`
- **Data Visualization:** `matplotlib`, `seaborn`, `wordcloud`
- **Machine Learning & Mining:** `scikit-learn`, `mlxtend`
- **NLP & Text Analytics:** `nltk` (VADER, Stopwords, Tokenization)
- **Graph & Network Analysis:** `networkx`
- **Interactive Development:** `jupyter`, `ipykernel`

---

## Getting Started & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/toxicbishop/BIDA.git
cd BIDA
```

### 2. Set Up Virtual Environment

#### Windows (PowerShell)
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

#### Windows (Command Prompt / Git Bash)
```bash
python -m venv .venv
source .venv/Scripts/activate
```

#### macOS / Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## Running the Experiments

### 1. Interactive Excel Dashboard (Experiment 01)
- Open [`Program 1/Program 1.xlsx`](./Program%201/Program%201.xlsx) in **Microsoft Excel** (or any compatible spreadsheet application).
- Navigate to the `Dashboard` sheet to interact with dynamic visualizations and cross-filtering slicers (by Gender, Age, Support, etc.).
- Refer to [`Program 1/Program 1.pdf`](./Program%201/Program%201.pdf) for the complete step-by-step methodology, PivotTable specifications, and chart configurations.

### 2. Python & Jupyter Notebooks (Experiments 05 – 12)
Launch Jupyter Notebook or JupyterLab in your active environment:

```bash
jupyter notebook
```

or open the workspace directly in **VS Code** / **Cursor** and select the `.venv` kernel (`.venv: Python 3.12.x`) when executing the notebook cells.

---

## License

This repository is maintained for educational and academic purposes.
