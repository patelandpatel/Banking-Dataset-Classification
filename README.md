# Banking-Dataset-Classification
There has been a revenue decline in the Portuguese Bank and they would like to know what actions to take. After investigation, they found that the root cause was that their customers are not investing enough for long term deposits. 

Data Set Information
The data is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be subscribed ('yes') or not ('no') subscribed.
 
There are two datasets: train.csv with all examples (32950) and 21 inputs including the target feature, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]

test.csv which is the test data that consists of 8238 observations and 20 features without the target feature

Goal:- The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

The dataset contains train and test data. Features of train data are listed below. And the test data have already been preprocessed.

Here’s a well-formatted table for your **README** file detailing the features:

| **Feature**    | **Feature Type**               | **Description**                                                                                                      |
|----------------|-------------------------------|----------------------------------------------------------------------------------------------------------------------|
| age            | Numeric                        | Age of a person                                                                                                      |
| job            | Categorical, nominal           | Type of job ('admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown') |
| marital        | Categorical, nominal           | Marital status ('divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)                 |
| education      | Categorical, nominal           | Level of education ('basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown') |
| default        | Categorical, nominal           | Has credit in default? ('no','yes','unknown')                                                                        |
| housing        | Categorical, nominal           | Has housing loan? ('no','yes','unknown')                                                                             |
| loan           | Categorical, nominal           | Has personal loan? ('no','yes','unknown')                                                                            |
| contact        | Categorical, nominal           | Contact communication type ('cellular','telephone')                                                                  |
| month          | Categorical, ordinal           | Last contact month of the year ('jan', 'feb', 'mar', …, 'nov', 'dec')                                                |
| day_of_week    | Categorical, ordinal           | Last contact day of the week ('mon','tue','wed','thu','fri')                                                         |
| duration       | Numeric                        | Last contact duration, in seconds. Note: this attribute highly affects the target variable ('y')                     |
| campaign       | Numeric                        | Number of contacts performed during this campaign and for this client (includes last contact)                        |
| pdays          | Numeric                        | Number of days since the client was last contacted from a previous campaign (999 means client was not previously contacted) |
| previous       | Numeric                        | Number of contacts performed before this campaign and for this client                                                |
| poutcome       | Categorical, nominal           | Outcome of the previous marketing campaign ('failure','nonexistent','success')                                        |
| **y**          | Binary                         | Has the client subscribed to a term deposit? ('yes','no')                                                            |
