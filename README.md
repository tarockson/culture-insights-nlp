# Culture Insights: NLP & Sentiment Analysis
## Mining Employee Feedback for Organizational Health

### Overview
Analyzed 3,100+ employee comments and 50+ exit interviews using natural language 
processing to identify cultural themes, sentiment trends, and psychological safety 
issues driving retention.

### Business Problem
Organizations often don't know *why* employees leave. Exit reasons are scattered 
across documents and conversations. Systematically analyzing this text data reveals 
actionable patterns that drive retention decisions.

### Key Results
- **Comments Analyzed**: 3,100+
- **Sentiment Accuracy**: 87% (vs manual coding validation)
- **Topics Identified**: 10 distinct cultural themes
- **Primary Exit Reasons**: Leadership (59%), Workload (50%), Growth (35%)

### Key Finding
**Pay ranks 5th** (15% mention). **Leadership quality** (59%) and **workload 
management** (50%) are the dominant retention drivers. This is a culture problem, 
not a compensation problem.

### What's Included
- `01_text_ingestion_cleaning.ipynb` - Text extraction and preprocessing
- `02_sentiment_analysis.ipynb` - VADER + TextBlob consensus approach
- `03_topic_modeling.ipynb` - TF-IDF vectorization and K-Means clustering
- `04_psychological_safety.ipynb` - Custom psychological safety index
- `index.html` - Interactive sentiment and topic visualization
- `sample_comments_anonymized.csv` - Example comment dataset
- `CASE_STUDY.md` - Detailed methodology and findings

### How to Run This Project

**Option 1: View the Notebooks Online**
Simply click on any `.ipynb` file to view the analysis.

**Option 2: Run Locally**
1. Clone this repository:
```bash
   git clone https://github.com/YOUR-USERNAME/culture-insights-nlp.git
   cd culture-insights-nlp
```

2. Install dependencies:
```bash
   pip install -r requirements.txt
```

3. Start Jupyter:
```bash
   jupyter notebook
```

4. Open notebooks in order: 01 → 02 → 03 → 04

5. View dashboard: [Retention Analytics project](https://tarockson.github.io/employee-retention-analytics/)

### Data
- **Survey Comments**: 3,100+ employee comments (2024-2025)
- **Exit Interviews**: 50+ structured departures
- **Sentiment Labels**: Pre-labeled as Positive, Neutral, Negative
- Sample data provided in `data/` folder (anonymized)

### NLP Methods
- **Sentiment Analysis**: VADER (handles negation/punctuation) + TextBlob (context)
- **Consensus Approach**: Combined both methods for reliability (87% accuracy)
- **Topic Modeling**: TF-IDF vectorization + K-Means clustering
- **Custom Metrics**: Psychological safety keyword index
- **Validation**: Manual coding validation on sample of 100 comments

### Key Themes Discovered
1. **Leadership/Supervision** (59%): Feedback, development, visibility
2. **Workload/Burnout** (50%): Caseload, hours, sustainability
3. **Growth/Career** (35%): Development, advancement, opportunity
4. **Culture/Inclusion** (24%): Belonging, team dynamics, values
5. **Compensation** (15%): Pay, benefits (ranked 5th)

### Key Recommendations
1. **Immediate**: Address supervision quality in high-turnover departments
2. **Short-term**: Implement supervisor training and workload review
3. **Long-term**: Create career development pathways

### Technologies Used
- Python 3.9+
- NLTK, TextBlob (sentiment analysis)
- scikit-learn (TF-IDF, K-Means)
- pandas, matplotlib, seaborn
- Jupyter notebooks
- HTML/JavaScript dashboard

### Notes
- Data has been anonymized to protect the organization
- Analysis demonstrates end-to-end NLP workflow
- For detailed methodology, findings, and recommendations, see [CASE_STUDY.md](https://github.com/tarockson/culture-insights-nlp/blob/main/case_study/CASE_STUDY.md)

## 📊 Interactive Dashboard

View the combined interactive dashboard in the 
[Retention Analytics project](https://tarockson.github.io/employee-retention-analytics/)

### Questions?
Feel free to open an issue or contact me.

### License
MIT License - See LICENSE file for details



