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
│   ├── Program-4-Datasets/        # Relational dataset for Power BI (7 CSV files)
│   │   ├── categories.csv
│   │   ├── cities.csv
│   │   ├── countries.csv
│   │   ├── customers.csv
│   │   ├── employees.csv
│   │   ├── products.csv
│   │   └── sales.csv              # Tracked via Git LFS
│   ├── Mall_Customers.csv         # Customer dataset for clustering analysis
│   └── Sample_Superstore.csv      # Superstore sales dataset for Tableau visual analytics & dashboards
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
├── Program 2/                     # Exp 02: Executive Dashboard Design (Tableau)
│   ├── Program 2.pdf              # Step-by-step process & documentation guide
│   └── Program 2.twb              # Tableau workbook file
├── Program 3/                     # Exp 03: Visual Analytics for Business Tasks (Tableau)
│   ├── Program 3.pdf              # Step-by-step process & documentation guide
│   └── Program 3.twb              # Tableau workbook file
├── Program 4/                     # Exp 04: Customer Experience & Predictive Analytics (Power BI)
│   ├── Program 4.pdf              # Step-by-step process & documentation guide
│   └── program-4.pbix             # Microsoft Power BI report file (Tracked via Git LFS)
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
| **02** | **Executive Dashboard Design** | Executive dashboard design for a given business analytics scenario using **Tableau Public** (KPIs, visual charts, and interactive dashboard). | [`Program 2.twb`](./Program%202/Program%202.twb) <br> ([`Guide`](./Program%202/Program%202.pdf)) |
| **03** | **Visual Analytics for Business Tasks** | Generate visual analytics for business tasks (regional sales, monthly trends, category shares, top customers) using **Tableau Public** and the Superstore dataset. | [`Program 3.twb`](./Program%203/Program%203.twb) <br> ([`Guide`](./Program%203/Program%203.pdf)) |
| **04** | **Customer Experience & Predictive Analytics** | Enhancing customer experience with data modeling, ETL, and predictive analytics in **Microsoft Power BI**. | [`program-4.pbix`](./Program%204/program-4.pbix) <br> ([`Guide`](./Program%204/Program%204.pdf)) |
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

- **Spreadsheet, BI & Visual Analytics:** `Microsoft Excel`, `Tableau Public`, `Microsoft Power BI`
- **Data Mining & Machine Learning:** `scikit-learn`, `mlxtend`, `Weka`, `RapidMiner`, `R`, `Apache Spark`
- **Programming & Scripting:** Python 3.12+, R
- **Data Manipulation:** `pandas`, `numpy`, `openpyxl`
- **Data Visualization:** `matplotlib`, `seaborn`, `wordcloud`
- **NLP & Text Analytics:** `nltk` (VADER, Stopwords, Tokenization)
- **Graph & Network Analysis:** `networkx`
- **Interactive Development:** `jupyter`, `ipykernel`

---

## Getting Started & Installation

### 1. Clone the Repository
```bash
# Ensure Git LFS is installed for large model & dataset files
git lfs install
git clone https://github.com/toxicbishop/BIDA.git
cd BIDA
git lfs pull
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

### 2. Tableau Dashboards & Visual Analytics (Experiments 02 & 03)
- **Experiment 02:** Open [`Program 2/Program 2.twb`](./Program%202/Program%202.twb) in **Tableau Public** or **Tableau Desktop** to explore the Executive Dashboard. Refer to [`Program 2/Program 2.pdf`](./Program%202/Program%202.pdf) for the step-by-step design process, KPI creation, and visual combinations.
- **Experiment 03:** Open [`Program 3/Program 3.twb`](./Program%203/Program%203.twb) in **Tableau Public** or connect [`Datasets/Sample_Superstore.csv`](./Datasets/Sample_Superstore.csv), following [`Program 3/Program 3.pdf`](./Program%203/Program%203.pdf) to generate visual analytics answering key business tasks (regional sales, monthly trends, category shares, and top customer segments).

### 3. Microsoft Power BI Workflow (Experiment 04)
- Open [`Program 4/program-4.pbix`](./Program%204/program-4.pbix) directly in **Microsoft Power BI Desktop** to view the completed multi-page interactive dashboards (`customer analysis`, `product Insights`, `Employee Performance`, and `Time Series Sales Trend`).
- The 7 relational CSV datasets are located in [`Datasets/Program-4-Datasets/`](./Datasets/Program-4-Datasets/) (`sales.csv`, `products.csv`, `customers.csv`, `categories.csv`, `employees.csv`, `cities.csv`, `countries.csv`).
- Refer to [`Program 4/Program 4.pdf`](./Program%204/Program%204.pdf) for the complete lab specifications, Power Query transformations, data modeling relationships, DAX measures, and forecasting settings.

### 4. Python & Jupyter Notebooks (Experiments 05 – 12)
Launch Jupyter Notebook or JupyterLab in your active environment:

```bash
jupyter notebook
```

or open the workspace directly in **VS Code** / **Cursor** and select the `.venv` kernel (`.venv: Python 3.12.x`) when executing the notebook cells.

---

## License

This repository is maintained for educational and academic purposes.
