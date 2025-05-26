# Personal Netflix Viewing Data Analysis

A comprehensive data science project analyzing personal Netflix viewing patterns using real account data, featuring exploratory data analysis, predictive modeling, and advanced visualization techniques to uncover viewing behaviors and preferences.

## Project Overview

This project leverages actual Netflix viewing data to perform an in-depth analysis of personal streaming habits across multiple user profiles. Through statistical analysis and machine learning, the project identifies distinct viewing patterns, device preferences, and content consumption behaviors, culminating in a predictive model that can accurately classify users based on their viewing characteristics.

### Key Achievements
- **Personal Data Analysis** - Real Netflix account data providing authentic insights
- **Profile Classification Model** - 81% AUC score for user prediction accuracy
- **Comprehensive EDA** - Multi-dimensional analysis of viewing patterns
- **Advanced Visualizations** - Professional data storytelling with statistical plots

## Architecture

```
Raw Netflix Data → Data Cleaning → Exploratory Analysis → Feature Engineering → ML Modeling → Performance Evaluation
```

## Technology Stack

**Data Analysis & Processing:**
- Python (pandas for data manipulation and analysis)
- Statistical analysis and aggregation techniques
- Data cleaning and preprocessing pipelines

**Machine Learning:**
- scikit-learn (logistic regression implementation)
- Model evaluation metrics (AUC, confusion matrix)

**Data Visualization:**
- Matplotlib (comprehensive plotting and customization)
- Seaborn (statistical visualizations and heatmaps)
- ROC curve analysis and confusion matrix visualization

## Dataset Overview

**Data Source**: Personal Netflix account viewing history
**File**: `ViewingActivity.csv`

**Key Variables:**
- Profile names (user identification)
- Title information (content consumed)
- Viewing timestamps (temporal patterns)
- Device types (viewing platform preferences)
- Duration data (engagement metrics)

## Analysis Framework

### Exploratory Data Analysis (netflix_analysis.ipynb)

**Viewing Pattern Analysis:**
- **Profile Comparison**: Viewing count distribution across household members
- **Content Preferences**: Most-watched titles and genre analysis
- **Temporal Patterns**: Viewing habits over time periods
- **Engagement Metrics**: Average viewing duration and completion rates

**Device Usage Analysis:**
- **Platform Preferences**: Most commonly used devices by profile
- **Cross-Platform Behavior**: Multi-device usage patterns
- **Device-Content Correlation**: Relationship between device type and content choice

**Statistical Insights:**
- **Viewing Volume**: Total hours consumed per profile
- **Content Diversity**: Range of titles watched by each user
- **Binge-Watching Patterns**: Session length and frequency analysis

### Predictive Modeling (netflix_logreg.ipynb)

**Logistic Regression Implementation:**
- **Target Variable**: User profile classification
- **Features**: Viewing time patterns and device type preferences
- **Performance**: AUC score of 0.81 (strong predictive capability)
- **Model Validation**: Comprehensive evaluation metrics

**Feature Engineering:**
- **Viewing Time Features**: Duration-based user characteristics
- **Device Encoding**: Categorical device type transformation
- **Behavioral Metrics**: Derived features from viewing patterns

## Model Performance & Results

### Classification Results
- **AUC Score**: 0.81 (Excellent discriminative ability)
- **Model Type**: Logistic Regression
- **Feature Importance**: Viewing time and device preferences as key predictors
- **Validation**: ROC curve analysis and confusion matrix evaluation

### Key Insights from Analysis

**Profile Differentiation:**
- Distinct viewing patterns successfully distinguish between users
- Device preferences serve as strong identifying characteristics
- Viewing duration patterns reflect individual consumption habits

**Behavioral Patterns:**
- Clear device-profile associations (mobile vs. TV vs. computer preferences)
- Content consumption volume varies significantly between profiles
- Temporal viewing habits show consistent individual patterns

## Project Structure

```
├── netflix_analysis.ipynb          # Comprehensive exploratory data analysis
├── netflix_logreg.ipynb            # Logistic regression modeling
├── ViewingActivity.csv             # Personal Netflix viewing data
└── README.md                       # Project documentation
```

## Key Findings & Insights

### User Behavior Analysis
- **Profile Uniqueness**: Each user demonstrates distinct viewing signatures
- **Device Loyalty**: Strong preferences for specific viewing platforms
- **Content Patterns**: Individual preferences clearly reflected in data
- **Predictive Accuracy**: 81% success rate in profile identification

### Statistical Discoveries
- **Viewing Volume Variation**: Significant differences in consumption levels
- **Platform Preferences**: Clear device-profile associations
- **Temporal Consistency**: Stable viewing patterns over time
- **Content Diversity**: Varying levels of content exploration by user

### Technical Achievements
- **Real Data Application**: Authentic dataset providing genuine insights
- **Model Performance**: Strong predictive capability with practical applications
- **Visualization Quality**: Professional-grade data presentation
- **Reproducible Analysis**: Well-documented analytical workflow

## Technical Skills Demonstrated

- **Data Science Workflow**: End-to-end analysis project execution
- **Python Programming**: Advanced pandas operations and data manipulation
- **Machine Learning**: Classification model development and evaluation
- **Statistical Analysis**: Comprehensive exploratory data analysis
- **Data Visualization**: Professional chart creation with multiple libraries
- **Model Evaluation**: Performance metrics interpretation and validation
- **Real Data Handling**: Personal data analysis with privacy considerations

---

**Contact**: [https://www.linkedin.com/in/danieldema/] | [danieldema42@gmail.com]

**Repository**: [https://github.com/danieldema/personal-netflix-analysis]

**Note**: This analysis uses personal Netflix data for educational and portfolio purposes, demonstrating data science techniques on real-world streaming data.
