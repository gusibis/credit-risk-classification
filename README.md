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
    <h3>Requirements</h3>
    <h4>Split the Data into Training and Testing Sets (30 points)</h4>
    <p>To receive all points, you must:</p>
    <ul>
        <li>
            <p>Read the <code>lending_data.csv</code> data from the Resources folder into a Pandas DataFrame. (5 points)</p>
        </li>
        <li>
            <p>Create the labels set (<code>y</code>) from the “loan_status” column, and then create the features (<code>X</code>) DataFrame from the remaining columns. (10 points)</p>
        </li>
        <li>
            <p>Split the data into training and testing datasets by using <code>train_test_split</code>. (15 points)</p>
        </li>
    </ul>
    <h4>Create a Logistic Regression Model (30 points)</h4>
    <p>To receive all points, you must:</p>
    <ul>
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
    <ul>
        <li>Be well commented with concise, relevant notes that other developers can understand. (10 points)</li>
    </ul>
    <h3>Grading</h3>
    <p>This project will be evaluated against the requirements and assigned a grade according to the following table:</p>
    <div class="table-div"><table border="0">
        <thead>
            <tr class="acting-th">
                <th>Grade</th>
                <th>Points</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>A (+/-)</td>
                <td>90+</td>
            </tr>
            <tr>
                <td>B (+/-)</td>
                <td>80–89</td>
            </tr>
            <tr>
                <td>C (+/-)</td>
                <td>70–79</td>
            </tr>
            <tr>
                <td>D (+/-)</td>
                <td>60–69</td>
            </tr>
            <tr>
                <td>F (+/-)</td>
                <td>&lt; 60</td>
            </tr>
        </tbody>
    </table></div>
    <h3>Submission</h3>
    <p>You are required to submit the URL of your GitHub repository for grading.</p>
    <div class="content-section callout note title-above"><strong class="blockquote-title">note</strong><div>

        <p>Projects are requirements for graduation. While you are allowed to miss up to two Challenge assignments and still earn your certificate, projects cannot be skipped.</p>
    </div></div>
    <div class="content-section callout important title-above"><strong class="blockquote-title">important</strong><div>

        <p><strong>It is your responsibility to include a note in the README section of your repo specifying code source and its location within your repo</strong>. This applies if you have worked with a peer on an assignment, used code in which you did not author or create sourced from a forum such as Stack Overflow, or you received code outside curriculum content from support staff such as an Instructor, TA, Tutor, or Learning Assistant. This will provide visibility to grading staff of your circumstance in order to avoid flagging your work as plagiarized.</p>
        <p>If you are struggling with a Challenge or any aspect of the curriculum, please remember that there are student support services available for you:</p>
        <ol>
            <li>
                <p>Office hours facilitated by your TA(s)</p>
            </li>
            <li>
                <p>Tutor sessions (<a href="https://tinyurl.com/BootCampTutorTeam" class="external" target="_blank" rel="noreferrer noopener" aria-label="sign up (Links to an external site)."><span>sign up</span><span class="external_link_icon" style="margin-inline-start: 5px; display: inline-block; text-indent: initial; " role="presentation"><svg viewBox="0 0 1920 1920" version="1.1" xmlns="http://www.w3.org/2000/svg" style="width:1em; height:1em; vertical-align:middle; fill:currentColor">
    <path d="M1226.66667,267 C1314.88,267 1386.66667,338.786667 1386.66667,427 L1386.66667,427 L1386.66667,853.666667 L1280,853.666667 L1280,693.666667 L106.666667,693.666667 L106.666667,1493.66667 C106.666667,1523 130.56,1547 160,1547 L160,1547 L1226.66667,1547 C1256.10667,1547 1280,1523 1280,1493.66667 L1280,1493.66667 L1280,1280.33333 L1386.66667,1280.33333 L1386.66667,1493.66667 C1386.66667,1581.88 1314.88,1653.66667 1226.66667,1653.66667 L1226.66667,1653.66667 L160,1653.66667 C71.7866667,1653.66667 0,1581.88 0,1493.66667 L0,1493.66667 L0,427 C0,338.786667 71.7866667,267 160,267 L160,267 Z M1584.37333,709.293333 L1904.37333,1029.29333 C1925.17333,1050.09333 1925.17333,1083.90667 1904.37333,1104.70667 L1904.37333,1104.70667 L1584.37333,1424.70667 L1508.96,1349.29333 L1737.86667,1120.38667 L906.613333,1120.38667 L906.613333,1013.72 L1737.86667,1013.72 L1508.96,784.706667 L1584.37333,709.293333 Z M1226.66667,373.666667 L160,373.666667 C130.56,373.666667 106.666667,397.666667 106.666667,427 L106.666667,427 L106.666667,587 L1280,587 L1280,427 C1280,397.666667 1256.10667,373.666667 1226.66667,373.666667 L1226.66667,373.666667 Z" stroke="none" stroke-width="1" fill-rule="evenodd"></path>
</svg>
<span class="screenreader-only">Links to an external site.</span></span></a>)</p>
            </li>
            <li>
                <p>Ask the class Slack channel/get peer support</p>
            </li>
            <li>
                <p>AskBCS Learning Assistants</p>
            </li>
        </ol>
    </div></div>
    <h3>References</h3>
    <p>Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.</p>
</div></div>


  <div style="display: none;">
    <span class="timestamp">1689659999</span>
    <span class="due_date_string">07/17/2023</span>
    <span class="due_time_string">11:59pm</span>
  </div>
</div>