# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Team 1 Hackathon 2

## Hackathon2 Project: Credit Card Churn Prediction

The Hackathon2 project aims to predict customer churn in the credit card sector using customer data. By analyzing factors such as credit card usage, income, and transaction activity, the goal is to identify potential churn risks, allowing businesses to take proactive measures to retain high-risk customers. This project will enable banks to improve customer retention strategies, increase customer satisfaction, and ultimately reduce the churn rate.

## Dataset Content

The dataset contains detailed customer information, including:
Customer Information: Age, marital status, income, credit card limit, and card category.
Credit Card Usage: Total credit limit, average utilization ratio, transaction volumes, and balances.
Behavioral Data: Customer relationship count, transaction frequencies, and months inactive.
This dataset is ideal for understanding customer spending behavior, predicting churn, and optimizing customer retention efforts. The dataset is available at https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data

## Business Requirements

The project addresses the following business requirements:

1. Predict customers who are likely to churn based on their usage behavior.
2. Identify patterns in transaction activity and credit utilization that influence churn.
3. Recommend strategies to retain high-risk customers.
4. Investigate how demographic factors (e.g., age, marital status) influence churn likelihood.

## Hypotheses and How to Validate

### Hypotheses:

1.Churned customers exhibit different spending behaviors than retained customers.
2. Higher-income customers tend to have higher credit limits, but anomalies may exist.
3. Customers with low transaction activity are more likely to churn.
4. Higher credit utilization and transaction volume are strong indicators of churn risk.
5. Customers with "Blue" card category are less likely to churn due to better utilization.
6. Male customers have a lower open-to-buy ratio, increasing their likelihood of churn.
7. Customers with more relationships are more likely to churn.

## Validation Steps:

Analyze transaction activity and churn rates to identify behavioral patterns.
Use correlation analysis to explore relationships between customer attributes and churn.
Test different retention strategies based on spending behavior and customer segments.

## Project Plan

Steps:

1. Data Collection: Load the dataset from the provided source.
2. Data Cleaning: Handle missing values, check duplicates, and standardize formats.
3. Data Transformation: Nothing to clean as the dataset had no duplicates or missing values.
4. Analysis: Perform exploratory data analysis, trend analysis, and correlation analysis
5. Modeling: Predict churn.
6. Visualization: Build dashboards to present insights and predictions.
7. Churn Prediction: Create a model to predict churn risk using customer demographics and behaviors. Visualizations like heatmaps and bar charts will help show the most significant factors influencing churn.
8. Credit Utilization Analysis: A scatter plot or box plot will help compare the utilization rate of customers who churn vs. those who stay.
9. Customer Segmentation: Use bars and pie-charts to group customers by similar characteristics, and visualize these groups to understand churn patterns better.
10. Imbalanced Dataset: Only 16.07% of customers have churned

## Dashboard

### Power BI https://app.powerbi.com/groups/me/reports/c4eb83c2-591d-49c3-b9fe-39572734e34c/02489e3782d86b16c45c?ctid=c233c072-135b-431d-af59-35e05babf941&experience=power-bi


Use of AI Tools:
ChatGPT was utilized for brainstorming hypotheses, improving code, and optimizing the model.


## Cloud IDE Reminders

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to _Account Settings_ in the menu under your avatar.
2. Scroll down to the _API Key_ and click _Reveal_
3. Copy the key
4. In the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

* Set the runtime.txt Python version to a [Heroku-22](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. At the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.
