# Covid-19 Clinical Trials Analysis Project

Welcome to my Covid-19 Clinical Trials Analysis project! This deep dive explores the global response to the Covid-19 pandemic through the lens of clinical research. Using Python and Tableau, we unpack trends, trial phases, intervention types, and more: sourced from clinicaltrials.gov.

## 🧠 Objective

To analyze the global landscape of Covid-19 clinical trials by:
- Cleaning and preprocessing raw trial data
- Performing in-depth data analysis (Univariate and Bivariate Data Analysis)
- Creating meaningful visualizations of key trends
- Laying the groundwork for potential machine learning use cases

## 🔧 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- [Tableau Public (for interactive dashboard)](https://public.tableau.com/app/profile/naila.srivastava/viz/Covid-19ClinicalTrialsDashboard_17484336631320/Covid-19TableauDashboard)
- Jupyter Notebook
- Git & GitHub (for version control)

## 📁 Dataset

- The dataset includes information on Covid-19-related trials: NCT number, country, phase, intervention type, sponsor, enrollment size, starting date, completion date and more.
- Due to privacy and size limits, the full dataset is not included in this repo.

➡️ [Download dataset here](https://www.kaggle.com/datasets/nailasrivastava/covid-19-clinical-trials-data)

## 💻 How to Run
1. Clone the repo  
2. Install dependencies: `pip install -r requirements.txt`  
3. Open the notebook: `Covid-19_Clinical_trials.ipynb`  
4. Run all cells and enjoy the visuals!

## 📊 Key Analysis

* Trial Status Distribution
* Phase-wise Progression
* Duration Trends
* Sponsor Landscape
* Intervention Types & Therapeutic Areas
* Country-wise Contributions

## 📈 Sample Visualizations

* Bar Charts
* Line Charts
* Funnel Chart

## 🌍 Advanced Visuals

* Choropleth World Map
* Interactive Filters 

## 📝 Key Takeaways

* Most COVID-19 clinical trials peaked between 2020–2021, coinciding with the global outbreak timeline.
* A large proportion of trials are in early phases, highlighting the urgency and experimental nature of pandemic-era research.
* The United States led in trial count, but other countries like China, India, and Iran had significant contributions.
* “Completed” and “Recruiting” were the most common statuses, while many trials still remain “Unknown” or “Withdrawn.”
* Top sponsors included major pharma companies and global research institutions—big names stepped up.
* Therapeutic areas focused heavily on antivirals, respiratory interventions, and immune-modulating therapies.

## 🧩 What’s Next?

* Add machine learning to predict trial outcomes or estimate completion times
* Integrate Natural Language Processing (NLP) to analyze trial descriptions and titles
* Create a real-time dashboard using live data sources (e.g., ClinicalTrials.gov API)
* Deploy this as a web app for researchers and policymakers 

## 🙌 Acknowledgments
Huge thanks to the open-source community and dataset contributors. 
This project was done as part of a 12-week upskilling sprint (Data Analyst Internship).

Massive thanks to:
* **ClinicalTrials.gov** – for making the raw data accessible
* And all healthcare professionals, researchers, and volunteers involved in COVID-19 trials

## 📂 Project Structure

```plaintext
Covid19-Clinical-Trials/
│
│── COVID clinical trials.csv                      # Raw dataset from clinicaltrials.gov
│── Covid-19_cleaned_dataset.csv                   # Cleaned and preprocessed dataset
│
├── visuals/                                       # All charts and graphs
├── Covid-19_Clinical_trials.ipynb                 # Main analysis notebook
├── Tableau df script.ipynb                        # Tableau dashboard notebook
├── .gitignore
├── README.md
└── requirements.txt                               # All required packages
