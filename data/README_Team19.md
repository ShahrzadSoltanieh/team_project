# Team 19 - Project 

# Dataset Exploration:
## How will you select your dataset?
We explored different open-source datasets from different platforms. We chose one related to finance which focuses on vehicular insurance data. We evaluated the dataset's content for usability and reviewed the dataset ranking on Kaggle to ensure it is robust and suitable for our analysis needs.
## How will you make sure all team members can contribute to the project?
Tasks will be assigned based on each member’s strengths and interests. We will use GitHub for version control and collaboration. We will use Slack for communication and  Google Drive for sharing and organizing documentation to ensure everyone is actively contributing and informed about the project’s progress.
## How will you make decisions?
We will have daily meetings to discuss progress and make decisions, and use Slack for day-to-day communications. We will ensure that everyone agrees on a decision before moving forward. In case of any disagreements, we resolve them through voting to ensure agreement.
## What is the question you're trying to answer through your data analysis?
[TO UPDATE]
## What tasks need to be completed to get to your final output?
After selecting the dataset, we will use heat maps of regression variables to identify correlations and and visualize key variables and attributes within the dataset. We will assign numerical values to binary variables and further explore the dataset relationships using visualization methods and modeling (scatter plots, histograms, etc.).


# Rules of Engagement - Team 19
## Team Members
* Balkan Dogu
* Yu (Cecily) Li
* Luiz Oliveira
* Shahrzad Soltanieh

## Communication and Feedback 
### Channels and Purposes:
* Use Slack for quick questions and updates.
* Zoom call for official discussions. Agenda shared beforehand;
* Response Time: Respond to messages within 24 hours. Communicate to the team if you will be late or unavailable. 
* Decision Making: Consensus for major decisions; additional discussions held as a team for tie-breakers.

### Work Allocation
* Tasks: Assign tasks based on strengths and interests, aligning with DSI team project requirements. 
* Deadlines: Set realistic deadlines; update if necessary. Communicate to the team ahead of the deadline if you experience a delay or issue. 
* Accountability: Raise issues promptly in the Slack group chat.

### Collaboration
* Respect diverse opinions; encourage open dialogue.
* Active listening during discussions, be open to others’ ideas and perspectives.
* Conflict Resolution: Address conflicts privately, escalate to the team if unresolved.
* Commitment: Commit to deadlines and quality standards as a team member.
* Proactivity: Initiate communication and problem-solving.

### Feedback and Evaluation
* Feedback: Regular feedback sessions during Zoom calls. Constructive criticism to be delivered respectfully.
* Evaluation: Review milestones; celebrate achievements!!!

## Self-Organization of Work 
* Work Environment Tools and Resources: GitHub repository for code; Google Drive for documents.
* Access: Ensure all members have access to necessary tools and resources.

## Clear Tracking of Progress
### Version Control and Documentation
* Repository: Use Git branching model (feature branches), create pull requests to team-project-1 for code review.
* Documentation: Update Google Sheets project plan for decisions and progress.



# Questions Discussed During Dataset Review
## What are the key variables and attributes in your dataset?
## Raw Dataset: Learning from Imbalanced Insurance Data
* Number of columns: 12
### ID: Unique identifier for each record.
* Type: Numerical
### Gender: Unique identifier for each record.
* Type: Categorical (Male, Female) →  We changed it to 'Male' = 1 and 'Female' = 0
### Age: Age of the customer.
* Type: Numerical
### Driving_License: Indicates whether the customer has a driving license.
* Type: Categorical (0 for No, 1 for Yes) 
### Region_Code: Code representing the region of the customer.
* Type: Numerical
### Previously_Insured: Indicates whether the customer previously had insurance.
* Type: Categorical (0 for No, 1 for Yes)
### Vehicle_Age: Age of the customer’s vehicle
* Type: Categorical (< 1 Year, 1-2 Year, > 2 Years) →  We changed it to 1,2,3 respectively
### Vehicle_Damage: Indicates whether the customer’s vehicle has been damaged in the past.
* Type: Categorical ( No, Yes) →  We changed it to No= 0 and Yes= 1
### Annual_Premium: The amount of premium the customer needs to pay annually.
* Type: Numerical
### Policy_Sales_Channel: Code representing the channel through which the policy was sold.
* Type: Categorical
### Vintage: Number of days the customer has been associated with the insurance company.
* Type: Numerical
### Response: The target variable indicating whether the customer responded positively to the insurance offer
* Type: Categorical (0 for No, 1 for Yes)

## How can we explore the relationships between different variables?
* Method 1 - Using Heatmaps to visualize correlations between numerical variables.
* Method 2 - Scatter Plots. Example: Plot scatter plots to explore relationships between two numerical variables, such as Age vs. Annual_Premium. The scatter plot shows a positive correlation between Age and Annual Premium, with older customers tending to pay higher premiums. This suggests that age is an important factor in determining the cost of insurance for customers. The insurance company could use this information to develop pricing strategies that take into account the age of the customer and offer competitive rates to different age groups.

## Are there any patterns or trends in the data that we can identify?
* Yes, there are trends between various sets of variables such as Vehicle Age and Damage, whereby most vehicles with 1-2 years of age have been damaged, while vehicles with less than 1 year of age have not been damaged. This suggests that the age of the vehicle may be related to the likelihood of damage. [TO UPDATE]

## Who is the intended audience for our data analysis?
The intended audience for this data analysis is the insurance company that provided the data. The company can use the analysis to understand the characteristics of customers who are interested in vehicle insurance and to identify potential customers who are likely to purchase insurance. The analysis can help the company develop targeted marketing strategies and improve customer acquisition and retention.

## What is the question our analysis is trying to answer?
Our analysis provides value to shareholders of the insurance company by answering the question "What are the characteristics of customers who are interested in vehicle insurance, and how can the insurance company identify potential customers who are likely to purchase insurance?". The analysis aims to investigate the relationships between various customer attributes.

## Are there any specific libraries or frameworks that are well-suited to our project requirements?
* Numpy - data manipulation and cleaning.
* Pandas - useful for numerical operations
* Matplotlib - for creating static and visualizations in Python.
* Seaborn -  it provides a high-level interface for drawing attractive and informative statistical graphics
* SciPy - Useful for statistical analysis

