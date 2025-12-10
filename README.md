# Student-Performance-Predictor

## Brief project description:
- An unsupervised learning project that is used to identify distinct student behavioral personas from demographic and activity data, rather than predicting grades.

## The Technical Summary:
**Goal** : Discover hidden patterns in student behavior.<br>
**Method** : Unsupervised Learning.<br>
**Data** : 25,000 records (Study hours, Attendance, Demographics).<br>
**Outcome** : Identified 4 unique student clusters to guide personalized educational support.<br>

## 📂 Project Structure
```bash
Student-Performance-Predictor
│
├── data/
│   ├── raw/                 
│   └── processed/        
│
├── notebooks/
│   └── Student_Clustering.ipynb  # Main analysis and visualizations
│
├── src/
│   ├── preprocessing.py     # Scripts for encoding and scaling
│   └── visualization.py     # Scripts for generating Snake Plots and PCA graphs
│
├── images/                  # Saved plots (Elbow curve, Cluster scatter plots)
│
├── requirements.txt
└── README.md
```
