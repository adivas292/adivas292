# Hi there, I'm Advik Vasanth 👋
I'm a first-year undergraduate at UC Irvine focusing on Quant Finance, Software Engineering, and Data Science. I love taking core math, statistics, and calculus concepts and turning them into practical Python data pipelines to uncover patterns in economic, real estate, and financial markets.

---

### 📊 Core Technical Toolkit
* **Languages**: Python (Clean Scripting, Basic OOP), JavaScript
* **Data Science Stack**: Pandas, NumPy, Scikit-Learn (Linear & Logistic Regression)
* **Data Visualization**: Matplotlib, Seaborn, Power BI *(Learning)*
* **Mathematical Foundations**: AP Calculus BC (Optimization & Gradients), AP Statistics (Hypothesis Testing, Distributions, Regression Analytics)

---

### 🚀 Highlighted Data Science Portfolios

#### 🏠 [Washington State Real Estate Predictive Analytics Engine](https://github.com/adivas292/Washington-Real-Estate-Predictive-Engine)
A baseline linear regression pipeline built to test how well standard physical house features can forecast residential valuations.
* **The Process**: I started this project as an exploratory analysis in Google Colab, manually calculating statistical bounds using the Interquartile Range (IQR) method and applying a natural log transformation (`np.log1p`) to fix heavily right-skewed pricing outliers. 
* **Data Corrections**: I noticed a logging glitch where unrenovated homes defaulted to a year value of 0, so I engineered a clean `house_age` factor using vectorized NumPy logic to remove the structural noise.
* **Refactoring Journey**: Once the statistical model held up under residual diagnostics (\(R^2\): 0.3544), I used Gemini to help me learn how to refactor my messy notebook cells into clean, decoupled Python modules (`preprocessing.py`, `train.py`).

#### 📊 [Demographic Consumer Behavioral Classifier](https://github.com/adivas292/Demographic-Consumer-Behavioral-Classifier)
A binary logistic regression classifier built to predict consumer demographic profiles based on 26,000+ real-world retail transactions.
* **The Pivot**: My initial data diagnostics showed that the raw transaction amounts possessed zero linear correlation (\(R^2\): -0.0001) with the consumer profiles. Recognizing a dead-end, I refactored the entire pipeline from a regression system into a logistic classification model instead.
* **Feature Engineering**: I parsed raw calendar text strings to pull day-of-the-week indexes, building a custom `is_weekend` tracking variable to see how spending habits changed over Saturdays and Sundays.
* **Evaluation & Flaws**: I evaluated my classification thresholds using automated `ConfusionMatrixDisplay` plots. While the overall accuracy hit 53.60%, the matrix visually diagnosed a heavy class bias in the dataset, providing me a clear avenue to learn about data balancing (SMOTE) next.

---

### 📈 Current Learning Goals & Market Interests
* 📈 **Quantitative Modeling**: Advancing from basic regression workflows to time-series analysis for financial asset price forecasting.
* 🗄️ **Data Ingestion**: Learning SQL (Structured Query Language) to pull and clean data directly from relational databases instead of just loading CSVs.
* 🤖 **Machine Learning Foundations**: Advancing from basic regression into parametric classification models and feature scaling (prepping for Statistical Methods for Data Analysis) to better handle real-world dataset imbalances and bias.

---

### 🤝 Let's Connect!
* 💼 **LinkedIn**: [https://www.linkedin.com/in/advikvasanth/](https://www.linkedin.com/in/advikvasanth/)
* 📬 **Email**: [advikv0292@gmail.com](mailto:advikv0292@gmail.com)
* 🏹 *Active Applicant: Currently seeking Data Science, Software Engineering, and Quantitative Internships for the Summer 2027 cycle.*
