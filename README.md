# Kids YouTube Midterm Project – MAT 301

## Author  
**Nawel Messaoudi**  
Undergraduate Biology major (Bioinformatics Concentration) at Hunter College  
Summer 2025 | MAT 301: Applied Statistics and Data Analysis (Lehman College)

---

## About the Project  
This project examines engagement trends in YouTube videos specifically made for children. As a parent and student, I was personally interested in understanding how media exposure impacts children. I analyzed the distribution of views, likes, and comments, as well as patterns among categories and popular channels.

---

## Dataset  
- **Filename**: `Filtered_Kids_Youtube_Videos.csv`  
- **Hosted on GitHub**: [Download Raw CSV](https://raw.githubusercontent.com/NawelMe/midterm-project_YouTube-Kids-Analysis/main/Filtered_Kids_Youtube_Videos.csv)  
- **Description**: Filtered subset of trending YouTube videos tailored for children. Includes metrics like views, likes, dislikes, comments, channel title, category ID, and publish time.

---

## Project Structure (Notebook)  
The analysis follows this structure:

1. **Data Cleaning & Wrangling**
   - Removed duplicates and irrelevant columns
   - Converted `publish_time` to datetime
   - Filtered out rows with missing or invalid data

2. **Measures of Central Tendency**
   - Asked 3 questions about average behavior
   - Computed mean, median, and mode
   - Provided interpretations in context

3. **Measures of Spread**
   - Asked 2 questions about data variability
   - Calculated standard deviation and IQR
   - Interpreted variability in comment activity and views

4. **Visualizations**
   - Pairplot exploring views, likes, dislikes, and comments
   - Histogram of view counts
   - Boxplot of likes across categories
   - Line plot showing total views over time

5. **Scatterplot with Linear Regression**
   - Analyzed relationship between likes and views
   - Fitted regression line and calculated correlation coefficient
   - Predicted expected views for a video with 100,000 likes

6. **Probability Questions**
   - Computed 4 probabilities using dataset
   - Included AND/OR logic and conditional probabilities
   - Clarified interpretation of each probability in sample context

7. **Freestyle Exploration**
   - Identified top 10 channels with the highest average likes
   - Included the exact code used to support this insight

---

## Final Deliverables  
- **Notebook**: [Kids_Youtube_Midterm_Project.ipynb](https://github.com/NawelMe/midterm-project_YouTube-Kids-Analysis/blob/main/Kids_Youtube_Midterm_Project.ipynb)  
- **Video Presentation**: [Watch Video](<insert-your-video-link-here>)  
- **Dataset**: [Raw CSV File on GitHub](https://raw.githubusercontent.com/NawelMe/midterm-project_YouTube-Kids-Analysis/main/Filtered_Kids_Youtube_Videos.csv)

---

## Tools Used  
- Python (`pandas`, `seaborn`, `matplotlib`, `scipy`)  
- Google Colab for code and markdown  
- GitHub for version control  
- YouTube/Google Drive for video submission

---

## Acknowledgments  
Submitted as the midterm project for **MAT 301: Applied Statistics and Data Analysis** at Lehman College under Professor Eric Aragundi.
