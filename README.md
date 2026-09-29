# 🎬 OTT Streaming Analytics

It is a data analytics project that uses Python and Power BI in order to analyze OTT streaming content, viewer preferences, content trends, and platform performance.

---

## 📌 Overview

The rapid growth of OTT platforms has led to a huge volume of digital content and streaming data. It is essential to understand this data if viewer preferences are to be identified, content performance is to be analyzed, and data-driven decisions are to be supported.

The OTT Streaming Analytics examines datasets from Netflix, Amazon Prime Video, and Disney+ in order to detect significant patterns relating to movies and TV shows.

The project converts data from OTT services into valuable insights regarding genres, ratings, popularity, release trends, regional preferences, and content performance by using Python-based data analysis and visualization together with Power BI interactive dashboards.

---

## 🎯 Problem Statement

The expansion of OTT platforms has created several challenges:

📌 Rapid growth—The quantity of digital content and user engagement is still increasing.
* **Data Management**. Handling and studying large amounts of streaming data is hard.
🔹 Viewer Behavior—It is difficult to understand complex viewer preferences and the way the audience's habits have changed.
🔹 **Accuracy of recommendations—If there is inadequate data analysis, this will have an effect on the precision of the content recommendations.
— The business impact could be that inadequate insights lead to content production strategies that are ineffective and investment decisions that are suboptimal.

The project deals with these challenges by analyzing OTT data and showing the results using visual analytics and interactive dashboards.

---

## 🎯 Project Objectives

### 1. Study What Viewers Like

Analyze OTT streaming data to understand:

* Viewer preferences
* Watching behavior
* Popular genres
* Popular movies
* Popular TV shows

### 2. Look at Content Trends

Analyze content trends across:

* Different countries
* Release years
* Ratings
* Popularity
* Engagement

### 3. Provide support for decisions based on data

Create interactive visualizations and dashboards that make OTT data easier to understand and support:

* Content analysis
* Viewer preference analysis
* Recommendation-related insights
* Data-driven decision-making

---

## 📊 Dataset

The project analyzes cleaned datasets collected from:

* **Netflix**
* **Amazon Prime Video**
* **Disney+**

The dataset combined includes more than 34,000 OTT movies and TV shows.

### Platform Distribution

| Platform     |  Records |
| ------------ | ----------: |
| Netflix      |      31,991 |
| Disney+      |       1,447 |
| Amazon Prime |       1,000 |
| **Total**    | **34,000+** |

### Content Types

The dataset contains:

* 🎬 Movies
* 📺 TV Shows

### Key Attributes

The datasets contain attributes such as:

| Attribute    | Description                         |
| ------------ | ----------------------------------- |
| Title        | Name of the movie or TV show        |
| Type         | Movie or TV Show                    |
| Genre        | Content genre                       |
| Release Year | Year the content was released       |
| Country      | Country associated with the content |
| Language     | Content language                    |
| Rating       | Content rating                      |
| Popularity   | Popularity measure                  |
| Vote Count   | Number of votes                     |
| Budget       | Content budget                      |
| Revenue      | Content revenue                     |
| Duration     | Content duration                    |

---

## 🧹 Data Preparation

To carry out the analysis, the datasets were first put in order in order to enhance the quality of the data.

The preprocessing stage included:

* Handling missing values
* Removing duplicate records
* Standardizing columns
* Preparing datasets for analysis
* Organizing data for interactive dashboard creation

---

## 🔬 Analysis

The project involves the analysis of OTT content from a number of different angles.

### Content Analysis

Analysis of:

* Movies vs TV Shows
* Popular genres
* Popular titles
* Top-rated content
* Content distribution

### Time-Based Analysis

Analysis of:

* Release-year trends
* Content growth over different years
* Changes in content popularity

### Regional Analysis

Analysis across:

* Countries
* Languages
* Regional content preferences

### Performance Analysis

Analysis using:

* Ratings
* Popularity
* Vote counts
* Budget
* Revenue
* Duration

---

## 📈 Visualization & Dashboard

The project makes use of Python visualization libraries and **Power BI** in order to present the data that has been analyzed.

### Python Visualization

The following libraries are used for creating static visualizations:

* Matplotlib
* Seaborn

They allow us to investigate the relationships and patterns in the dataset.

### Power BI Dashboard

Power BI is used to create interactive dashboards for:

* Exploring OTT content
* Comparing platforms
* Understanding content trends
* Analyzing viewer preferences
* Exploring regional patterns
* Presenting key insights

The screenshots for the dashboard can be included in this README when the final images of the dashboard are available.

---

## 🛠️ Tech Stack

| Technology           | Purpose                                       |
| -------------------- | --------------------------------------------- |
| **Python**           | Data cleaning, preprocessing, and analysis    |
| **Pandas**           | Data manipulation and dataset handling        |
| **NumPy**            | Numerical calculations and data processing    |
| **Matplotlib**       | Data visualization                            |
| **Seaborn**          | Statistical visualization                     |
| **Power BI**         | Interactive dashboards and visual exploration |
| **Excel / CSV**      | Dataset storage and initial preparation       |
| **Jupyter Notebook** | Python analysis environment                   |
| **Git**              | Version control                               |
| **GitHub**           | Source-code and project management            |

---

## 🚀 Getting Started

### 1. Copy the repository

```bash
git clone https://github.com/<your-username>/ott-streaming-analytics.git
cd ott-streaming-analytics
```

### 2. Create a Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Look through the notebooks in the `notebooks/` directory and carry out the analysis workflow.

---

## 📁 Project Structure

```text
ott-streaming-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   └── 03_visualization.ipynb
│
├── src/
│   ├── data_cleaning.py
│   ├── analysis.py
│   └── visualization.py
│
├── dashboards/
│   └── OTT_Streaming_Analytics.pbix
│
├── images/
│   └── dashboard.png
│
├── reports/
│   └── OTT_Streaming_Analytics.pdf
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

The repository structure can be modified so that it matches the final project files.

---

## 💡 Key Outcomes

The project is designed to identify:

* Popular OTT genres
* Popular movies and TV shows
* Top-rated content
* Content trends over time
* Regional content patterns
* Viewer preference patterns
* Cross-platform content characteristics

Interactive dashboards make it easier to explore and interpret complex OTT data.

---

## 🔮 Future Enhancements

The project can be extended with the following capabilities:

### ⚡ Real-Time Analytics

Analyze viewer activity and streaming trends as they happen.

### 🤖 AI-Based Recommendations

Use machine learning methods to give personalized content suggestions.

### 📊 Predictive Analytics

Predict:

* Future viewer preferences
* Popular genres
* Content demand

### 💬 Sentiment Analysis

Study the user reviews and feedback in order to gain an understanding of audience satisfaction.

### 👥 Advanced User Segmentation

Group viewers based on:

* Interests
* Location
* Viewing habits
* Preferences

### 🌐 Cross-Platform Analysis

Allow the content's performance to be compared dynamically across multiple OTT platforms.

---

## 📌 Project Conclusion

OTT Streaming Analytics shows how data-driven analysis can be applied to large-scale OTT content datasets in order to identify viewing trends, popular genres, the top-rated content, and audience preferences.

The project makes complex streaming data easier to understand and interpret by using Python-based analysis together with interactive Power BI dashboards.

The insights obtained can be used to gain a better understanding of viewer behavior, to make recommendations about content, to decide on content creation and to carry out investment-related analysis.

---

## 👥 Contributors

* **Ch. Kusumitha Keerthi**
* **Praveen Goswami**
* **A. Aparajitha**
* **K. Harsha Vardhan**

**Department of Computer Science & Engineering**
**Aditya University**

---

## 📜 License

It is being carried out for educational and academic purposes.

If the project is intended to be distributed publicly, include the appropriate open-source license in this section.

---

## ⭐ Acknowledgement

This was part of an academic project in the field of data analytics, the aim of which was to gain an understanding of OTT streaming data by means of data preprocessing, exploratory analysis, visualization, and the creation of business intelligence dashboards.
