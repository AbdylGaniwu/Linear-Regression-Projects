# **Linear Regression Analysis on Learners' Dataset**

## **Project Overview**
This project applies a **linear regression analysis** to explore the relationship between quiz scores and the number of completed content items by learners. Additionally, it investigates whether there is a significant difference in performance based on the lesson taken (Lesson A or Lesson B). The findings provide insights into learner behaviors and the effectiveness of lesson content.

---

## **Dataset Description**
The dataset contains 100 observations with the following columns:
- **score**: The quiz score of each learner (continuous, float).
- **completed**: Number of completed content items (integer).
- **lesson**: Type of lesson taken by the learner, either "Lesson A" or "Lesson B" (categorical).

**Initial Data Assessment:**
- **Missing Values**: No missing values in the dataset.
- **Duplicate Rows**: No duplicate rows were found.

---

## **Linear Regression Analysis**

### **1. Relationship Between Quiz Scores and Completed Content**
A scatter plot was used to visualize the relationship between the number of completed content items and quiz scores.

#### **Result:**
A **positive correlation** was identified: as the number of completed items increases, the quiz score tends to rise.

### **2. Linear Regression Model**
A simple linear regression model was fitted to predict the **quiz score** based on the number of completed content items.

- **Intercept**: Learners who completed 0 content items are predicted to score **13.21** points on the quiz.
- **Slope**: For every additional completed content item, the score is expected to increase by **1.31** points.

#### **Example Prediction:**
A learner who has completed 20 content items is predicted to score **39.35** points.

---

## **Residual Analysis**

### **Normality of Residuals**
The residuals were checked for normality using a histogram, which showed that they follow an approximately normal distribution.

### **Homoscedasticity**
A scatter plot of fitted values vs. residuals showed no visible patterns, confirming that the assumption of homoscedasticity is satisfied.

---

## **Lesson-Based Performance Comparison**
### **1. Boxplot of Scores by Lesson**
A boxplot was used to compare the distribution of quiz scores between **Lesson A** and **Lesson B**.

#### **Conclusion**: 
Learners who took **Lesson A** performed better on average than those who took **Lesson B**.

### **2. Linear Regression for Lesson Impact**
A linear regression model was used to assess whether the lesson taken impacted quiz scores. The results indicated that learners who took **Lesson B** scored, on average, **11.64 points lower** than those who took **Lesson A**.

---

## **Visualization**
An **lmplot** was used to visualize the relationship between completed content items and quiz scores, with different lines for **Lesson A** and **Lesson B**.

#### **Conclusion**:
The plot shows that learners who completed more content items generally achieved higher scores, and **Lesson A** appears to be more effective in producing higher quiz scores.

---

## **Key Insights**
- Learners who complete more content items tend to achieve higher quiz scores.
- **Lesson A** appears to be more effective than **Lesson B** in improving learner performance.

