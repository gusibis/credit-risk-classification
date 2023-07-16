# credit-risk-classification
<div id="assignment_show" class="assignment content_underline_links">
    <!--Student View-->
    <div class="assignment-title">
      <div class="title-content">
        <h1 class="title">
          Module 20 Challenge
        </h1>
      </div>
  <div class="description user_content enhanced"><div id="bootcamp">
<img style="display: none;" src="https://static.bc-edx.com/data/dl-1-2/m20/lms/img/banner.jpg" alt="lesson banner" tabindex="0" role="button" aria-label="lesson banner. Click to Enlarge." class="external-link-icon">
    <h3>Instructions</h3>
    <p>The instructions for this Challenge are divided into the following subsections:</p>
    <ul>
        <li>
            <p>Split the Data into Training and Testing Sets</p>
        </li>
        <li>
            <p>Create a Logistic Regression Model with the Original Data</p>
        </li>
        <li>
            <p>Write a Credit Risk Analysis Report</p>
        </li>
    </ul>
    <h4>Split the Data into Training and Testing Sets</h4>
    <p>Open the starter code notebook and use it to complete the following steps:</p>
    <ol>
        <li>
            <p>Read the <code>lending_data.csv</code> data from the Resources folder into a Pandas DataFrame.</p>
        </li>
        <li>
            <p>Create the labels set (<code>y</code>) from the “loan_status” column, and then create the features (<code>X</code>) DataFrame from the remaining columns.</p>
            <div class="content-section callout note title-above"><strong class="blockquote-title">note</strong><div>
                <p>A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.</p>
            </div></div>
        </li>
        <li>
            <p>Split the data into training and testing datasets by using <code>train_test_split</code>.</p>
        </li>
    </ol>
    <h4>Create a Logistic Regression Model with the Original Data</h4>
    <p>Use your knowledge of logistic regression to complete the following steps:</p>
    <ol>
        <li>
            <p>Fit a logistic regression model by using the training data (<code>X_train</code> and <code>y_train</code>).</p>
        </li>
        <li>
            <p>Save the predictions for the testing data labels by using the testing feature data (<code>X_test</code>) and the fitted model.</p>
        </li>
        <li>
            <p>Evaluate the model’s performance by doing the following:</p>
            <ul>
                <li>
                    <p>Generate a confusion matrix.</p>
                </li>
                <li>
                    <p>Print the classification report.</p>
                </li>
            </ul>
        </li>
        <li>
            <p>Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?</p>
        </li>
    </ol>
    <h4>Write a Credit Risk Analysis Report</h4>
    <p>Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the <code>README.md</code> file included in your GitHub repository.</p>
    <p>Structure your report by using the report template that <code>Starter_Code.zip</code> includes, ensuring that it contains the following:</p>
    <ol>
        <li>
            <p><strong>An overview of the analysis:</strong> Explain the purpose of this analysis.</p>
        </li>
        <li>
            <p><strong>The results:</strong> Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.</p>
        </li>
        <li>
            <p><strong>A summary:</strong> Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.</p>
        </li>
    </ol>
</div>
<div>
    <h3>Overview of the Analysis:</h3>
        <ul>
            <li><p>Explain the purpose of the analysis.</p></li>
            <li><p>Explain what financial information the data was on, and what you needed to predict.</p></li>
            <li><p>Provide basic information about the variables you were trying to predict (e.g., `value_counts`).</p></li>
            <li><p>Describe the stages of the machine learning process you went through as part of this analysis.</p></li>
            <li><p>Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).</p></li>
        </ul>
    <h3>Results</h3>
    <h4>Machine Learning Model 1 (Healthy loans=0, high-risk loans=1):</h4>
        <li>Model 1 Overall Accuracy 99%</li>
        <li>Model 1 balanced accuracy score 0.95% (0.9520479254722232).</li>
        <li>Model 1 Precision 100% for healthy loans and 85% for high-risk loans.</li>
        <li>Model 1 Recall 99% for healthy loans and 91% for high-risk loans</li>
        <li>Model 1 f1-score 100% for healthy loans and 88% for high-risk loans</li>
        <img src="model1Summary.png">
    <h4>Machine Learning Model 2 (Healthy loans=0, high-risk loans=1):</h4>
        <li>Model 2 Overall Accuracy 99%</li>
        <li>Model 2 balanced accuracy score 0.99% (0.9936781215845847).</li>
        <li>Model 2 Precision 100% for healthy loans and 84% for high-risk loans.</li>
        <li>Model 2 Recall 99% for healthy loans and also 99% for high-risk loans</li>
        <li>Model 1 f1-score 100% for healthy loans and 91% for high-risk loans</li>
        <img src="model2Summary.png">
    <h3>Summary</h3>
        <li>* The First model for the low risk loans has an accuracy of 100%, the recall is 99% which is excellent, however with the 1 label for the high-risk loans, the precision is 85% and the  recall is 91%.  85% precision is low for high-risk loans in my opinion, also the recall tells us about how the model identifies true positives and 91% is not too bad but it all depends of the level of risk the business should keep to be profitable and to have less liabilities given that it is higher-risk loans. Of course we would need to verify the results to have a better perspective. <br>* The second model performed a bit better than model 1 with healthy loans accuracy of 99% and a recall of 99% (true positive score), as well as a f1-score that if our data contains the total number of observations the calculation function of precision and recall (F1 Score = 2* Precision Score * Recall Score/ (Precision Score + Recall Score/)), this calculation returned 100%. I think this is also a good model for our data if we were only working with healthy loans. For the high risk loans this model did a bit better than the previous, even though the precision is one percent down, the recall and f1-score improved quite a bit. If I had to choose between the 2 models I would pick this second model. </li>
        <li>* I have to say that both models could be insufficient for the line of business and risk level since the most importan prediction would be for the high-risk loans, both have a low precision score, but again there could be other variables such as total amount of loans and the level or risk the business can take to be profitable and safe at the same time. If a choice had to be made between the the two, the second model performed better although the precision was 1 percent less, the recall and f1-score had a good improvement. </li>
</div>