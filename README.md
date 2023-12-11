
# **Home Credit Default Project**

## **Introduction:**

Home Credit is an international consumer finance provider that focuses on those with little or no credit history, recognizing this demographic's vulnerability to untrustworthy lenders. Home Credit is dedicated to promoting financial inclusion by providing a positive and secure borrowing experience for the underserved population. Using various statistical and machine-learning methodologies, the business predicts clients' repayment abilities using alternative data such as telecom and transactional information. This data-driven approach seeks to ensure that worthy persons are not denied loans, while also constructing loan conditions that provide clients with a reasonable principal and repayment schedule that is favorable to their financial success.

Home Credit aims to bridge the gap in financial services and provide assistance to those who are typically overlooked by traditional lending institutions by maximizing the utility of their data. The primary goal is to foster a lending climate in which persons with the ability to repay are not just awarded loans, but also individualized financial solutions that contribute to their entire financial well-being. Home Credit hopes to provide a real path to financial success for a broader and more varied part of the population by committing to inclusivity and predictive analytics.

## **Business Problem:**

The primary Business problem in the Home Loan Credit Risk Analysis project is extending loans to individuals without a credit history, with the overarching goal of promoting financial inclusion. To address this, the company proposes an analytics-driven approach, leveraging alternative data sources like telco and transactional information. By analyzing historical client data, including call patterns and socioeconomic factors, predictive models are constructed using statistical and machine learning methods. The goal is to accurately predict repayment capabilities and tailor loan terms. Success metrics include lowering default rates, expanding approved loans, enhancing customer satisfaction, and growing the unbanked customer base. Home Credit envisions revolutionizing lending through alternative data and advanced analytics, ensuring secure credit access for underserved individuals while reducing default risks. The core of the project is a predictive model using supervised learning methods, promising expanded customer reach, improved customer satisfaction, responsible lending practices, and business growth, positioning Home Credit uniquely in the market.

## **Project Objective:**

The objective of the project is to build a machine learning model that can reliably estimate their creditworthiness of people applying for house loans. The model will be trained using a dataset of historical loan data, which will include factors such as by gender, Family Status, income, car own, loan amount, and other relevant features. The algorithm will identify patterns and correlations associated with high or low credit risk by analyzing this historical data.

Simply described, the project's goal is to:

- Creating a Classification Predictive model to predict the customers risk to default.
- Expanding loan approvals to a broad customer base with strong repayment capabilities.

## **Your group's solution to the business problem.**

Our team's approach to Home Credit Risk Analysis involved constructing a predictive model through machine learning techniques. Among the various models tested, the Light Gradient Boosting (LGB) model, followed closely by the XG Boost model, demonstrated superior performance in evaluating the creditworthiness of potential borrowers, particularly those with limited credit histories. These models yielded Kaggle scores of .695 and .623, respectively. To tackle class imbalance within the dataset, we implemented SMOTE sampling techniques.The top three features crucial for the LGB model's success were **EMPLOYMENT\_DAYS, REGISTRATION\_DAYS, and LAST\_PHONE\_CHANGE \_DAYS.**

We recommend Home Credit Group to consider lending to individuals based on factors such as **Gender, Family Status, Type of Income, Ownership of a Car, and Level of Education.** Applicants meeting all these criteria are deemed less likely to default. Ultimately, our solution aims to align with Home Credit's mission of enhancing financial inclusion and providing a positive borrowing experience for the unbanked population.

## **Your contribution to the project**

In the Home Credit Loan Risk project, my initial involvement centered around data preprocessing and feature engineering. We focused on collaboration and held regular discussions about ideas to improve our understanding of the dataset. I set up and conducted these meetings, assigning tasks to team members to keep everyone on track throughout the project. I played a crucial role in mitigating class imbalance through Smote sampling, actively contributing to enhancing the model's ability to predict credit risk accurately for the unbanked population. My optimization of data representation and management of class imbalance markedly improved the overall performance,

Within the Modeling phase of the Home Credit Kaggle project, I took a lead role in creating and implementing diverse models, with a focus on refining the Light Gradient Boosting model. I conducted thorough evaluations using metrics like Accuracy and ROC AUC, guiding the team in selecting the most effective models for deployment. Additionally, I performed detailed data analysis and feature engineering to provide valuable insights into borrowers' repayment capabilities. Ultimately, my contributions contributed to Home Credit's mission of expanding financial inclusion and empowering clients with a positive and safe borrowing experience.

## **The business value of the solution.**

We conducted a comparison between the basic logistic regression model and our selected best model, the LGB model, using precision values. The precision for logistic regression is 0.69, while the LGB model achieves a higher precision of 0.92.

To illustrate the impact, we consider a sample of 10,000 customers identified as less likely to default. Utilizing precision values, we estimated the risk of default for both models. **Surprisingly, the logistic regression model predicted 3,193 customers at risk, whereas the LGB model predicted only 16.**

This highlights a significant advantage of the LGB model, potentially allowing Home Credit to identify over 3,000 additional customers with lower default risk. Such an outcome aligns seamlessly with Home Credit's mission of reducing the financial services gap in society, demonstrating a compelling business solution.

## **Difficulties that your group encountered along the way.**

Our team faced some tough challenges while working on the Home Credit Risk Analysis project. One big problem was that there were way more people who didn't default on their loans than those who did, making it tricky to create a model that could accurately predict both groups. To fix this, we tried out different SMOTE techniques to balance things without messing up the results.

Another challenge was explaining how our model made its predictions. Figuring out and telling people why the machine learning algorithms decided what they did turned out to be pretty hard. So, we spent a lot of time using special techniques to make our model more understandable and analyzed which factors were really important in predicting credit risk. On top of all that, we had to stick to tight schedules and work with limited resources. Everyone on the team had other jobs or internships, so finding the right balance and making sure we stayed on track meant lots of communication and teamwork.

To sum up, the challenges we faced, such as addressing class imbalance, navigating complex alternative data, interpreting model predictions, and managing project constraints, served as valuable learning experiences. By working collaboratively, seeking innovative solutions, and adapting our approaches, we successfully navigated these challenges and delivered a robust credit risk prediction model for Home Credit.

## **What you learned in the project.**

The Home Credit Risk Analysis project has been a pivotal learning experience in my journey through data science and machine learning. It marked my initial hands-on encounter with deploying various machine learning models into a dataset, significantly enhancing my comprehension of their functioning. Notably, the study delves into the complexities of dealing with imbalanced datasets, emphasizing the critical need of efficiently controlling class imbalances in order to address real-world difficulties. This newfound expertise has been extremely useful in navigating the complexities of data science, providing practical insights into reducing imbalanced data difficulties, integrating varied data sources, and comprehending sophisticated machine learning models.

Furthermore, the project highlighted the crucial importance of effective teamwork and communication. By holding regular meetings, clearly assigning tasks, and tapping into the expertise of each team member, we successfully tackled the project's challenges, especially considering tight deadlines and limited resources. In addition to improving my skills in data science methods, the Home Credit Risk Analysis project gave me practical know-how in dealing with imbalanced data issues, integrating diverse data sources, and interpreting complex machine learning models. The challenges and lessons learned have increased my motivation to continually enhance my data science expertise, driving me to contribute to impactful solutions in the field and stay updated on the latest developments in data science and machine learning.
