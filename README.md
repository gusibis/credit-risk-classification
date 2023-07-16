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
        <li>
            <p>Fit a logistic regression model by using the training data (<code>X_train</code> and <code>y_train</code>). (10 points)</p>
        </li>
        <li>
            <p>Save the predictions on the testing data labels by using the testing feature data (<code>X_test</code>) and the fitted model. (5 points)</p>
        </li>
        <li>
            <p>Evaluate the model’s performance by doing the following:</p>
            <ul>
                <li>
                    <p>Generate a confusion matrix. (5 points)</p>
                </li>
                <li>
                    <p>Generate a classification report. (5 points)</p>
                </li>
                <li>
                    <p>Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels? (5 points)</p>
                </li>
            </ul>
        </li>
    </ul>
    <h4>Write a Credit Risk Analysis Report (20 points)</h4>
    <p>To receive all points, you must:</p>
    <ul>
        <li>
            <p>Provide an overview that explains the purpose of this analysis. (5 points)</p>
        </li>
        <li>
            <p>Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model. (5 points)</p>
        </li>
        <li>
            <p>Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. (10 points)</p>
        </li>
    </ul>
    <h4>Coding Conventions and Formatting (10 points)</h4>
    <p>To receive all points, you must:</p>
    <ul>
        <li>
            <p>Place imports at the top of the file, just after any module comments and docstrings and before module globals and constants. (3 points)</p>
        </li>
        <li>
            <p>Name functions and variables with lowercase characters, with words separated by underscores. (2 points)</p>
        </li>
        <li>
            <p>Follow DRY (Don’t Repeat Yourself) principles, creating maintainable and reusable code. (3 points)</p>
        </li>
        <li>
            <p>Use concise logic and creative engineering where possible. (2 points)</p>
        </li>
    </ul>
    <h4>Code Comments (10 points)</h4>
    <p>To receive all points, your code must:</p>
    
</div>