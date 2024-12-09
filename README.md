# 🎥 Fandango Movie Ratings Analysis

## **Overview**
This project investigates a potential conflict of interest in Fandango—a website that both sells movie tickets and displays movie review ratings. By analyzing data from 2015, the project aims to determine whether Fandango artificially inflated movie ratings to drive ticket sales.

---

## **Problem Statement**
Fandango displays two types of ratings:
- **Stars**: The ratings visually shown to users (0 to 5 scale).
- **True Ratings**: The backend numerical ratings calculated based on user votes.

The question we address is:
- *Does Fandango display artificially higher ratings compared to its true ratings and other platforms like Rotten Tomatoes, Metacritic, and IMDb?*

---

## **Dataset**
The project uses two main datasets:
1. **`all_sites_scores.csv`**:
   - Contains movie scores from multiple platforms, including Fandango, Rotten Tomatoes, Metacritic, and IMDb.

2. **`fandango_scrape.csv`**:
   - Scraped data from Fandango, including both the displayed `Stars` and backend `True Ratings`.

---

## **Project Workflow**

### **1. Data Collection and Cleaning**
- Preprocessed the datasets to ensure uniformity and compatibility.
- Normalized ratings from different platforms to a common 0-5 scale for fair comparisons.

### **2. Exploratory Data Analysis (EDA)**
- Visualized discrepancies between Fandango’s displayed ratings and true ratings.
- Explored user and critic rating distributions across platforms.
- Analyzed the relationship between movie popularity and ratings.

### **3. Cross-Platform Analysis**
- Compared Fandango ratings with other platforms like Rotten Tomatoes, Metacritic, and IMDb.
- Highlighted cases where Fandango ratings significantly deviated from others.

### **4. Visualization and Findings**
- Created insightful plots using Python libraries like Pandas, Matplotlib, and Seaborn.
- Highlighted the skew in Fandango’s displayed ratings, where most movies were rated higher than their true values.

---

## **Key Findings**
- **Inflated Ratings**: Fandango consistently displayed higher ratings than its backend true scores.
- **Platform Comparison**: Fandango’s ratings were noticeably higher than other platforms. For example, the movie *Taken 3* was displayed with a 4.5-star rating on Fandango, while its average rating across platforms was only 1.86.
- **Distribution Differences**: While Rotten Tomatoes and Metacritic showed a balanced distribution of good and bad movies, Fandango's ratings skewed heavily toward higher values.

---

## **Skills and Tools Demonstrated**
- **Programming Languages**: Python
- **Libraries Used**: Pandas, NumPy, Matplotlib, Seaborn
- **Data Analysis Techniques**: EDA, normalization, cross-platform comparison
- **Visualization**: Histograms, scatter plots, cluster maps
- **Critical Thinking**: Uncovered ethical concerns in online rating systems

---

## **Visualizations**
Some key visualizations include:
- **Rating Discrepancy Plots**: Comparing Fandango’s displayed `Stars` to its backend `True Ratings`.
- **Cross-Platform Histograms**: Normalized score distributions for Fandango, Rotten Tomatoes, Metacritic, and IMDb.
- **Cluster Map**: Grouped movies by their ratings across platforms to identify patterns.

---

## **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fandango-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd fandango-analysis
   ```

3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Load and run the `Capstone_Project.ipynb` notebook.

---

## **Project Outcomes**
This project demonstrates how data-driven insights can uncover ethical concerns in online platforms. It also showcases proficiency in:
- Analyzing real-world datasets
- Visualizing data trends effectively
- Identifying patterns and discrepancies

---

## **References**
- [538 Article: "Be Suspicious of Online Movie Ratings, especially Fandango’s"](https://fivethirtyeight.com/features/fandango-movie-ratings/)
- Wikipedia: *Taken 3*'s Critical Reception

---

## **Acknowledgments**
Special thanks to [538](https://fivethirtyeight.com/) for the inspiration and datasets used in this analysis.

---

## **Contact**
For any questions or feedback, feel free to reach out:
- **Name**: Vedant Pimple
- **Email**: [your_email@example.com](mailto:your_email@example.com)
- **LinkedIn**: [linkedin.com/in/vedant-pimple](https://linkedin.com/in/vedant-pimple)
