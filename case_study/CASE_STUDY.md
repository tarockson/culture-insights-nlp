# Case Study: Culture Insights through NLP & Sentiment Analysis

## Executive Summary
Analyzed 3,100+ employee comments using natural language processing to identify 
cultural drivers of retention. Key finding: pay ranks 5th; leadership quality and 
workload management are primary drivers.

## The Challenge
- Don't know why employees really leave
- Exit reasons scattered across documents
- No systematic way to identify cultural patterns
- Leadership making retention decisions without complete data

## Solution Approach

### Phase 1: Text Collection & Cleaning
- Extracted 3,100+ employee survey comments (2024-2025)
- Extracted 50+ exit interview documents
- Removed PII and proprietary information
- Standardized text format and cleaned special characters
- Removed stopwords, lemmatized tokens

### Phase 2: Sentiment Analysis
- **VADER Analysis**: Handles negation and punctuation
- **TextBlob Analysis**: Captures context and nuance
- **Consensus Approach**: Combined both methods for reliability
- **Validation**: Manually coded sample of 100 comments
- **Accuracy**: 87% agreement with manual coding

### Phase 3: Topic Modeling
- **Vectorization**: TF-IDF (term frequency-inverse document frequency)
- **Clustering**: K-Means with k=10
- **Interpretation**: Extracted top terms per topic
- **Manual Review**: Verified 89% of clusters were interpretable

### Phase 4: Custom Metrics
- **Psychological Safety Index**: Created keyword-based metric
- Tracked frequency of safety language vs. silencing language
- Validated against manual review
- Trended over time (2024-2025)

## Key Findings

### Finding 1: Sentiment is Neutral (Not Negative)
- Average sentiment: -0.008 (right at neutral)
- Positive comments: 28%
- Neutral comments: 35%
- Negative comments: 37%
- **Implication**: Not catastrophic, but room for improvement

### Finding 2: Psychological Safety is Concerning
- Current index: 0.32 (below healthy)
- Healthy range: 0.50-1.0
- 2024: 0.30, 2025: 0.41 (slight improvement)
- **Implication**: Employees don't feel fully safe speaking up

### Finding 3: Leadership is the #1 Exit Reason (59%)
Common themes:
- "My supervisor doesn't develop me"
- "I don't get regular feedback"
- "I feel invisible to leadership"
- "No clear expectations"

### Finding 4: Workload/Burnout is #2 (50%)
Common themes:
- "Caseload is unsustainable"
- "No work-life balance"
- "Constant firefighting"
- "Exhausted by end of week"

### Finding 5: Growth/Career is #3 (35%)
Common themes:
- "No clear path forward"
- "Stuck after 2 years"
- "Limited development opportunities"
- "Same role for years"

### Finding 6: Pay Ranks 5th (15%)
- Barely mentioned in exit interviews
- When mentioned, usually not primary reason
- Only 8 out of 50+ exits cited compensation
- **Implication**: Not a compensation problem

## Topic Distribution
| Topic | Theme | Avg Sentiment | Mentions |
|-------|-------|---------------|----------|
| 1 | Leadership | -0.42 | 587 |
| 2 | Workload | -0.55 | 432 |
| 3 | Supervision | -0.38 | 502 |
| 4 | Growth | -0.41 | 298 |
| 5 | Culture | -0.12 | 215 |
| 6 | Benefits | 0.15 | 89 |
| 7 | Team | 0.62 | 324 |
| 8 | Mission | 0.71 | 191 |
| 9 | Flexibility | 0.35 | 147 |
| 10 | Communication | -0.28 | 178 |

## Recommended Actions

### Immediate (30 days)
- Address top 3 leadership complaints
- Communicate change initiatives
- Show psychological safety improvement

### Short-Term (60-90 days)
- Supervisor training program ($50K)
- Workload assessment and rebalancing
- Career pathway development

### Long-Term (6-12 months)
- Quarterly culture monitoring
- Leadership accountability metrics
- Ongoing psychological safety improvement

## Business Impact
- **Problem Identification**: Pinpointed exact cultural issues
- **Action Clarity**: Clear priorities (leadership → workload → growth)
- **Resource Allocation**: Justifies supervisor training investment
- **Measurement**: Baseline for future improvement tracking

## Limitations & Future Work
- Comments limited to recent period (2024-2025)
- Cannot identify individual-level patterns
- Topic modeling relies on keyword frequency (not deep semantics)
- Future: Use more advanced NLP models (BERT, transformer-based)

## Conclusion
Analysis reveals that employee departures are driven by management quality and 
workload, not compensation. This is fixable through targeted interventions with 
clear ROI. The cultural issues are addressable and measurable.