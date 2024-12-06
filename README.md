# Running Consumer Clustering Analysis

## Introduction
This project leverages clustering techniques to help a running footwear and apparel company identify key consumer segments based on their running habits. Using survey data, the analysis uncovers distinct groups of runners—such as casual joggers, competitive athletes, or style-conscious individuals—and their unique preferences. These insights inform tailored product designs and marketing strategies.

## Objectives
- Segment customers based on their running habits using unsupervised learning techniques.
- Provide actionable recommendations for product development and marketing strategies.

## Data
The dataset used in this project was obtained through a survey of running consumers. It contains multiple fields that describe running habits, preferences, and demographic details. A data map is provided in the `data/` folder to explain each field in the dataset.

## Analysis Process
1. **Data Preprocessing**:
   - Cleaning and preparing the data for clustering.
   - Standardizing features to ensure uniform scaling.

2. **Clustering Techniques**:
   - Explored different clustering algorithms (e.g., K-Means, Hierarchical Clustering).
   - Used the Elbow Method and Silhouette Scores to determine the optimal number of clusters.

3. **Visualization**:
   - Visualized clusters using PCA (Principal Component Analysis) and t-SNE for dimensionality reduction.
   - Created plots to interpret clusters and identify key consumer segments.

4. **Recommendations**:
   - Based on cluster analysis, provided strategic insights for product development and marketing campaigns.

## Key Findings
- Identified distinct consumer segments such as:
  - **Casual Joggers**: Running primarily for fitness and leisure.
  - **Competitive Athletes**: Focused on performance and advanced running gear.
  - **Style-Conscious Users**: Prioritize aesthetics over functionality.
- Recommendations include targeted marketing strategies and product improvements to cater to each segment.

## Dependencies
The project was implemented using Python. Below is a list of key libraries used:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

To install all dependencies, use:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Running-Consumer-Clustering.git
   cd Running-Consumer-Clustering
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook notebooks/clustering_analysis.ipynb
   ```
4. Follow the annotations in the notebook to understand the analysis and results.

## Results
The clustering analysis revealed actionable insights that can help the company:
- Tailor marketing campaigns to each customer segment.
- Develop products that align with the preferences of different runner groups.
- Improve customer satisfaction and drive sales growth.

## Project Structure
```
Running-Consumer-Clustering/
├── data/
│   ├── survey_data.xlsx           # Raw survey data
│   ├── data_map.txt               # Description of dataset fields
├── notebooks/
│   ├── clustering_analysis.ipynb  # Jupyter notebook with analysis
├── reports/
│   ├── recommendations.md         # Strategic recommendations
├── README.md                      # Project overview
├── requirements.txt               # Python dependencies
└── LICENSE                        # (Optional) License for the project
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
