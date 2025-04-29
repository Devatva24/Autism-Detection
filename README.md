<h1>Early Autism Detection Using Machine Learning</h1>

<h2>📌 Objective</h2>
<p>To develop a machine learning model that can predict the likelihood of Autism Spectrum Disorder (ASD) in individuals based on questionnaire-based screening data.</p>

<hr>

<h2>🛑 Problem Statement</h2>
<p>Early detection of Autism Spectrum Disorder is crucial for timely intervention and support. Traditional diagnosis often requires specialized clinical assessment, which may not be easily accessible in all regions. This project aims to assist early screening using machine learning models trained on structured questionnaire responses.</p>

<hr>

<h2>📊 Dataset</h2>
<ul>
  <li><b>Source:</b> <a href="https://www.kaggle.com/datasets/fearless007/autism-screening-on-children" target="_blank">Kaggle - Autism Screening Data</a></li>
  <li><b>Features include:</b>
    <ul>
      <li>Age</li>
      <li>Gender</li>
      <li>Ethnicity</li>
      <li>Family history of ASD</li>
      <li>Jaundice at birth</li>
      <li>Screening test responses (Q1 to Q10)</li>
      <li>Result from the Autism Spectrum Quotient test</li>
      <li>Class/target: ASD or Not</li>
    </ul>
  </li>
</ul>

<hr>

<h2>⚙️ Methodology</h2>

<h3>1. Data Preprocessing</h3>
<ul>
  <li>Handle missing values and inconsistent entries</li>
  <li>Convert categorical data to numerical using encoding</li>
  <li>Normalize/standardize features as needed</li>
  <li>Train-test split (e.g., 80-20)</li>
</ul>

<h3>2. Exploratory Data Analysis (EDA)</h3>
<ul>
  <li>Understand class imbalance</li>
  <li>Visualize age distribution and test response trends</li>
  <li>Check correlation between features</li>
</ul>

<h3>3. Model Selection</h3>
<ul>
  <li>Test multiple models:
    <ul>
      <li>Logistic Regression ✅ (Best Performing)</li>
      <li>Random Forest</li>
      <li>Support Vector Machine (SVM)</li>
      <li>Naive Bayes</li>
    </ul>
  </li>
  <li>Use GridSearchCV or cross-validation for tuning</li>
</ul>

<h3>4. Evaluation Metrics</h3>
<ul>
  <li>Accuracy</li>
  <li>Precision, Recall, F1-Score</li>
  <li>Confusion Matrix</li>
  <li>ROC-AUC Score</li>
</ul>

<h3>5. Final Model</h3>
<ul>
  <li>Logistic Regression achieved:
    <ul>
      <li><b>Accuracy:</b> 86.88%</li>
      <li><b>High Recall:</b> Suitable for screening tasks</li>
    </ul>
  </li>
</ul>

<h3>6. Deployment (optional)</h3>
<ul>
  <li>Streamlit app to collect questionnaire responses and display predictions</li>
  <li>User-friendly interface for non-technical audiences</li>
</ul>

<hr>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>Pandas, NumPy</li>
  <li>Matplotlib, Seaborn</li>
  <li>Scikit-learn</li>
  <li>(Optional) Streamlit for frontend</li>
</ul>

<hr>

<h2>✅ Results</h2>
<ul>
  <li>Best model (Logistic Regression) achieved 86.88% accuracy</li>
  <li>Balanced performance with good recall for detecting potential ASD cases</li>
</ul>

<hr>

<h2>📝 Conclusion</h2>
<p>The project showcases the potential of machine learning in supporting early autism screening using easily available data from questionnaires. With further development and validation, such tools can complement clinical assessments, especially in resource-constrained settings.</p>

<hr>

<h2>🔮 Future Work</h2>
<ul>
  <li>Train on larger and more diverse datasets</li>
  <li>Implement ensemble learning methods</li>
  <li>Enhance the user interface for deployment</li>
  <li>Collaborate with healthcare professionals for clinical validation</li>
</ul>
