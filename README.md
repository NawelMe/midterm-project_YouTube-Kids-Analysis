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
- **Hosted on Google Drive**: [Download CSV File](https://drive.google.com/file/d/1JOI9cBck2VYqkgoYpyu4cnWcOyLZcphL/view?usp=sharing)  
- **Description**: A cleaned and filtered subset of trending YouTube videos tailored for children. Includes metrics such as views, likes, dislikes, comments, channel titles, category ID, and publish time.

---

## Project Structure (Notebook)  
The notebook follows a structured, step-by-step approach for clarity and evaluation:

1. **Data Cleaning & Wrangling**  
   - Loaded the dataset  
   - Converted `publish_time` to datetime  
   - Removed unused columns and handled missing values

2. **Measures of Central Tendency**  
   - Q1: What is the average number of views?  
   - Q2: What is the median number of likes?  
   - Q3: What is the most common category ID?

3. **Measures of Spread**  
   - Q4: What is the standard deviation of views?  
   - Q5: What is the IQR of comment counts?

4. **Visualizations**  
   - Q6: Pairplot of views, likes, dislikes, and comments  
   - Q7: Histogram of view distribution  
   - Q8: Boxplot of likes across category IDs  
   - Q9: Time series of total views per day

5. **Scatterplot with Linear Regression**  
   - Q10: Is there a linear relationship between likes and views?  
   - Predicted views for a video with 100,000 likes

6. **Probability Analysis**  
   - Q11: P(video has >1M views)  
   - Q12: P(likes >100k AND comments >10k)  
   - Q13: P(views >1M | category 24)  
   - Q14: P(dislikes >10k OR comments >20k)

7. **Freestyle Exploration**  
   - Q15: Which 10 channels receive the highest average number of likes?

---

## Final Deliverables  
- **Notebook (Google Colab)**: [Open in Colab](https://colab.research.google.com/drive/1lcy0Kzq0AFAdelu4zQV6m4L0RAGHWNKR?usp=sharing)  
- **Dataset (Google Drive CSV)**: [Filtered_Kids_Youtube_Videos.csv](https://drive.google.com/file/d/1JOI9cBck2VYqkgoYpyu4cnWcOyLZcphL/view?usp=sharing)  
- **Video Presentation**: *[Coming Soon]*

---

## Tools Used  
- Python (`pandas`, `seaborn`, `matplotlib`, `scipy`)  
- Google Colab for coding and markdown formatting  
- Google Drive for CSV and notebook hosting  
- GitHub for version control and documentation

---

## Acknowledgments  
Submitted as the midterm project for **MAT 301: Applied Statistics and Data Analysis** at Lehman College under Professor Eric Aragundi.
