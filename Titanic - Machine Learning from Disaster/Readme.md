<h1>Titanic - Machine Learning from Disaster</h1>
<div class="row">
    <div class="col-12">
        <p>In this project, I worked on predicting passenger survival from the Titanic disaster using data provided in a Kaggle challenge. The aim was to build a model that could predict which types of passengers were more likely to survive based on features like age, gender, and socio-economic class.</p>
        <p>Below is an outline of the steps I followed to complete the project:</p>
    </div>
    <div class="col-12">
        <h3>1. Exploratory Data Analysis (EDA)</h3>
        <p>The first step involved performing EDA to understand the dataset and identify key trends. I performed the following operations:</p>
        <ul>
            <li><strong>Data Cleaning</strong>: Handled missing values, particularly in the <em>Age</em> and <em>Cabin</em> columns, by either imputing median values or dropping uninformative features.</li>
            <li><strong>Feature Exploration</strong>: Analyzed the distribution of key variables like <em>Sex</em>, <em>Age</em>, <em>Fare</em>, and <em>Pclass</em> to see how they correlated with survival rates.</li>
            <li><strong>Outlier Detection</strong>: Used visual techniques like boxplots to identify and remove any outliers in continuous variables like <em>Fare</em>.</li>
            <li><strong>Visualization</strong>: Created visualizations using libraries like <em>matplotlib</em> and <em>seaborn</em> to better understand the relationships between variables. For example, I plotted survival rates against gender, passenger class, and embarked location to reveal insights.</li>
        </ul>
    </div>
    <div class="col-12">
        <h3>2. Feature Engineering</h3>
        <p>After EDA, I engineered new features to improve model performance:</p>
        <ul>
            <li><strong>Title Extraction</strong>: Extracted titles (e.g., Mr., Mrs., Miss) from passenger names to capture information about social status and gender.</li>
            <li><strong>Family Size</strong>: Created a new feature to represent the family size of each passenger by combining <em>SibSp</em> and <em>Parch</em> (siblings/spouse and parents/children).</li>
            <li><strong>Fare Binning</strong>: Grouped fare into categories to handle variability and make it easier for the model to interpret.</li>
        </ul>
    </div>
    <div class="col-12">
        <h3>3. Data Preprocessing</h3>
        <p>To prepare the data for machine learning, I performed several preprocessing steps:</p>
        <ul>
            <li><strong>Label Encoding</strong>: Converted categorical variables such as <em>Sex</em> and <em>Embarked</em> into numerical labels.</li>
            <li><strong>Standardization</strong>: Scaled continuous features like <em>Age</em> and <em>Fare</em> to ensure they were on a similar scale using <em>StandardScaler</em>.</li>
            <li><strong>Splitting the Data</strong>: Split the data into training and testing sets to evaluate the model's performance effectively.</li>
        </ul>
    </div>
    <div class="col-12">
        <h3>4. Model Building</h3>
        <p>I tried different machine learning models to find the best one:</p>
        <ul>
            <li><strong>Logistic Regression</strong>: As a starting point, I implemented logistic regression to classify passengers as survivors or non-survivors. This simple model provided a baseline accuracy.</li>
            <li><strong>Random Forest</strong>: Next, I used a Random Forest classifier to improve performance by capturing non-linear relationships and handling missing data more effectively.</li>
            <li><strong>Support Vector Machines (SVM)</strong>: I also experimented with SVM to see if it could capture more complex decision boundaries.</li>
        </ul>
    </div>
    <div class="col-12">
        <h3>5. Hyperparameter Tuning</h3>
        <p>To optimize the model performance, I performed hyperparameter tuning:</p>
        <ul>
            <li><strong>GridSearchCV</strong>: I used <em>GridSearchCV</em> to fine-tune hyperparameters for the Random Forest model, such as the number of trees, maximum depth, and minimum samples per leaf. This step improved the model's accuracy.</li>
        </ul>
    </div>
    <div class="col-12">
        <h3>6. Statistical Testing and Validation</h3>
        <p>I validated the performance of my models using:</p>
        <ul>
            <li><strong>Cross-validation</strong>: Employed K-fold cross-validation to ensure that the model generalized well across different subsets of data.</li>
            <li><strong>Confusion Matrix & ROC Curve</strong>: Evaluated the model using confusion matrices and ROC curves to measure precision, recall, and overall classification performance.</li>
        </ul>
    </div>
    <div class="col-12">
        <h3>7. Data Visualization</h3>
        <p>I used visualizations to present my findings and model results:</p>
        <ul>
            <li><strong>Feature Importance Plot</strong>: Displayed which features were most influential in predicting survival using the Random Forest model.</li>
            <li><strong>Survival Distribution Plots</strong>: Plotted survival distributions across different classes and genders to visually convey the insights derived from the data.</li>
        </ul>
    </div>
    <div class="col-12">
        <h3>8. Model Submission</h3>
        <p>Finally, I generated predictions on the test dataset and submitted them to the Kaggle leaderboard. The final model achieved an accuracy of <strong>0.77033</strong>, which placed me in a respectable position on the leaderboard.</p>
    </div>
    <div class="col-12">
        <h3>Key Takeaways</h3>
        <p>This project helped me gain a solid foundation in data analysis, machine learning, and working with real-world datasets. I learned how to systematically approach a problem, starting with data exploration and progressing through model building, tuning, and evaluation. Additionally, I improved my skills in using libraries like <em>pandas</em>, <em>numpy</em>, <em>scikit-learn</em>, and <em>seaborn</em> to solve data science problems.</p>
    </div>
</div>
