# Kids YouTube Midterm Project – MAT 301

## Author
**Nawel Messaoudi**  
Undergraduate Biology major (Bioinformatics Concentration) at Hunter College  
Summer 2025 | MAT 301: Applied Statistics and Data Analysis (Lehman College)

## About the Project
This project examines statistical patterns in YouTube videos specifically designed for children's content. As both a student and a parent of young children, I was personally motivated to analyze the types of media kids are exposed to online. My focus was on understanding how engagement metrics, such as views, likes, and comments, behave across different video categories and creators.

## Dataset
- **Filename**: `Filtered_Kids_Youtube_Videos.csv`
- **Stored in**: [Google Drive](https://drive.google.com/file/d/1JOI9cBck2VYqkgoYpyu4cnWcOyLZcphL/view?usp=sharing)
- **Description**: Contains metadata on YouTube videos for children, including views, likes, dislikes, comments, category ID, publish time, and more.
- Note: The dataset was too large to upload directly to GitHub and is therefore shared via Google Drive.

## Project Components
### 1. Data Cleaning & Wrangling
- Dropped irrelevant columns and duplicates.
- Removed rows with invalid values (e.g., 0 views or negative comments).
- Converted publish time to datetime format and checked for nulls and outliers.

### 2. Statistical Analysis
- Calculated measures of **central tendency**: mean, median, and mode.
- Evaluated **spread** using standard deviation and interquartile range (IQR).
- Answered four probability questions using sample data.

### 3. Visualizations
- **Pairplot**: explored relationships among key metrics (views, likes, comments).
- Three additional visualizations:
  - **Histogram**: distribution of views (right-skewed).
  - **Boxplot**: likes by category ID.
  - **Line graph**: trends in views over publish dates.

### 4. Regression Analysis
- Focused on the relationship between **likes** and **views**.
- Fitted a least squares regression line and calculated the correlation coefficient.
- Predicted number of views for a video with 100,000 likes.

### 5. Freestyle Exploration
- Investigated which YouTube channels received the highest average number of likes.
- Found that music and entertainment creators dominated top rankings.

## Final Deliverables
- 📓 **Notebook**: [Google Colab Link](https://drive.google.com/file/d/1lcy0Kzq0AFAdelu4zQV6m4L0RAGHWNKR/view?usp=sharing)
- 🎥 **Video Presentation**: [Watch Video](<insert-Video-link-here>)
- 📂 **Dataset**: [Download CSV from Google Drive](https://drive.google.com/file/d/1JOI9cBck2VYqkgoYpyu4cnWcOyLZcphL/view?usp=sharing)

## Tools Used
- Python: `pandas`, `seaborn`, `matplotlib`, `scipy`
- Google Colab for coding and markdown annotations
- GitHub for sharing the project
- Google Drive for dataset storage

## Acknowledgments
This project was submitted as part of the midterm requirement in **MAT 301: Applied Statistics and Data Analysis** at Lehman College, under the guidance of Professor Eric Aragundi.
