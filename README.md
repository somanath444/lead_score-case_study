# Prblem Statement

An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once the people land on the website, they might browse the courses or fill up a form for the course or watch some video. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls , writing emails, etc. Through this process, some of the leads gets converted while most do not. The typical lead conversion rate at X education is around 30%.

Now although X Educaiton gets a lots of leads, its leads conversion rate is very poor. For example, if, they say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as 'Hot Leads'. If they successfully identify this set of leads, this lead conversion rate should go up as the sales team will now focusing more on communication with the potential leads rather then making calls to everyone.

X Education has appointed you to help them select the most promising leads,i.e. the leads that are most likely to convert into paying customers> 'The company requires you to build a model where in you need to assign a lead score to each of the leads' such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in [articular, has given a ballpark of the target lead coversion rate to be around 80% 

# Data:

YOu have been provided with leads dataset from the past with around 9000 data points. This dataset consists of various attributes such as Lead Source, Total Time Spent on website, Total Visits, Last Activity, etc. Which may or may  not be useful in ultimately deciding wheater a lead will be converted or not. The target variable in this case, is the column 'Converted' which tells wheater a past lead was converted or not wherein 1 means it was converted and 0 means it wasn't converted. You can learn more aabout the dataset from the data dictionary provided in the zip folder at the end of the page.
Another thing that you also need to check out for are the levels present in the categorical variables. Many of the categorical variables have a level called 'Select' which needs to be handled because it is as good as a null value (think why?)

# Goals of the cas study.

There are quite a feq goals for this case study.

* Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

* There are some problems presented by the company whcih your model should be able to adjust if the company's requirment changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.

# Results Expected.

* A well-commented Jupyter note with at least the logistic regression model, the convrsion predictions and evaluation metrics.

* The overall approach of the analysis in a presentation.
    * Mention the probelm statement and the analysis approach briefly
    * Explain the results in business terms.
    * Include visualizations and summarizee the most important results
      in the presentation. 
