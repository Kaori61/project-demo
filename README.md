
<img align="right" width="200" height="100" src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png"> 

# Credit Card Attrition Analysis

**Credit Card Attrition Analysis** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.



## Dataset Content
The dataset consist of 10,000 customers' age, salary, marital status, credit card limit, credit card category, etc. The dataset is available from [Credit Card customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data)


## Business Requirements
* Assess which customers are likely to churn (when a customer ceases to be a customer) so that the bank can take proactive measures to retain them. Develop analytical reports to identify customers at risk of churning and provide actionable insights to reduce churn rates. The goal is to assess which customers are likely to churn using customer data and develop strategies to improve retention.


## Hypothesis and how to validate?

1. Customers with lower card categories are more likely to churn.
   * Create a bar chart of churn rate by card category.

2. The lower the total transaction amount, the higher their likelihood of churning.
   * Create a histogram to visualise total transaction amount for attrited and exisiting customers.     


3. Customers with lower total revolving balances are likely to churn.
   * Create a box plot to compare total revolving balance for attited customers and exsisting customers.

 

## Project Plan
* Data collection
* Data Cleaning  
* Data Analysis
* Hypothesis Testing
* Insight generation
* Reporting

I chose these methods to follow a logical step by step approach. Started with data collection to gather relevant information, data cleaning to handle any incinsistency in the data and prepared for analysis. Analysed data to explore patterns then tested hypothesis to validate assumptions. Generated insight based on the results. By following these steps, I could understand the dataset better and generate insights based on the findings.


## The rationale to map the business requirements to the Data Visualisations
* The bank wants to know who are likely to churn and prevent from churning. 
I assumed that generating actionable insights would require more advanced analysis than I could currently perform, so I focused on identifying obvious patterns and filtering out assumptions in preparation for the next step.

## Analysis techniques used
* Created ETL → pipeline pairwise analysis → visualisation → hypothesis testing
    
    I followed these steps to prepare the dataset for analysis and to understand the data more effectively, so I could generate meaningful conclusions.
* I used generative AI tools to help organise methodology, brainstorming, code optimisatoin and refining the wording in my project writing.
* Limitation

  I was unable to create interactive visualisation (see Unfixed Bugs section) so I decided to create it with Seaborn instead of Plotly so that I could still find a useful insight from it.
  
  This analysis was about exploring the data and spotting patterns.


 
## Ethical considerations
* The data was anonymised. Ethical consideration was addressed with this project.

## Unfixed Bugs

I tried to create a plot using Plotly, but something wasn’t working properly on my computer. Neil was very helpful and tried to assist, but we couldn’t figure out the cause of the issue. I uninstalled `nbformat` version 5.10.4 and installed version 4.2.0 instead. Even though the terminal confirmed that version 4.2.0 was installed, I continued to receive the same error message.

 ![Bug1](ScreenshotBug.png)


I uninstalled and reinstalled requirements.txt, and also ran `pip install ipython` as Neil suggested. However, the issue persisted, insted of `ValueError`, it is now showing `alueError` as shown in the image below.
![Bug2](ScreenshotBug2.png)





## Development Roadmap
The chanlleges I faced 
- Creating project plan - I wasn't sure where to start so I just dived in before planning much which was not a great idea. I have a little more understanding of what needs to be done so next project, I will plan better and document more as I go. 
- Error and trial - I had many errors and google, chatGPT was a gret help to understand what I did wrong. I should have documented more of my error. 
- Tried to create a pair plot using entire dataset to find any patterns before addressing hypothesis but it kept giving me errors. To address the issue, I picked few columns of interest and created a dataset then created a pair plot showing multiple variable relationships. 

In the next project, I would like to use more statistics in my analysis for my next project. I am not confident in using statistical methods so I chose not to apply in this project but I am interested in and would like to have deeper understandings.



## Main Data Analysis Libraries
* Pandas to load and clean data
* Numpy to manage plot layout
* Seaborn to create visualisation
* Matplotlib to visualise the created plots
* Plotly to create interactive plot(failed)


## Credits 

* I got visualisation idea from here - [From Data to Viz](https://www.data-to-viz.com/#network).  Helped me decide which plot to make to visualise dataset.
* Checked the code with [seaborn](https://seaborn.pydata.org/index.html#), [LMS](https://learn.codeinstitute.net/dashboard).
* When I encountered errors and needed a guidance, I used [ChatGPT](https://chatgpt.com/), [W3Schools](https://www.w3schools.com/), [GeeksforGeeks](https://www.geeksforgeeks.org/)
* Checked this page to know how to align image to the right in README [DavidWells](https://gist.github.com/DavidWells/7d2e0e1bc78f4ac59a123ddf8b74932d)




## Acknowledgements
Thanks to all my tutors. I’ve really been enjoying the course so far, and your support has helped me complete this project.
* Emma Lamont - Very supportive course facilitator. Thank you for your support and I am greatful to be looked after.
* John  Rearden - Thank you for great sessions to explain complex consepts clearly. 
* Mark Briscoe - Thank you for your humour and relaxed teaching style. It made the learning environment more enjoyable.
* Niel McEwen - Thank you for making course material easy to follow and quick response for my query.