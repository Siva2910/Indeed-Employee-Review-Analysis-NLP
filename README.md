# Indeed-Employee-Review-Analysis-NLP

# Introduction

Online company review sites such as Indeed and Glassdoor facilitated the use of employer branding. For example, any employee, whether former or current, can review their experience with a company by giving a star rating and providing feedback. As the result, those looking to apply to positions at that company will know whether it’s worth doing.
The surveys of users of company review sites supported the need for proper brand management, especially negative reviews. For example, a recent compilation of recruiting stats by Glassdoor revealed that 83 percent of job seekers were likely to research company reviews before deciding whether to apply. Clearly, an increasing number of people use online resources to get more information about companies and certain aspects such as salary data of benefits.

# Objective

To analyze the employee reviews on an Online Company review website i.e. Indeed and obtain insights from the data

# Dataset

![image](https://user-images.githubusercontent.com/67836160/176505371-3e20bc63-0403-4ea9-bb28-d0937660bc96.png)

Dataset Contains around 67,530 rows and 3 Columns :
  * Rating
  * Review Text
  * Employee Type
      * Former Employee
      * Current Employee

# Exploratory Data Analysis

![image](https://user-images.githubusercontent.com/67836160/176505507-4c7db502-83b0-48ab-a822-bb3c34b2349c.png)

![image](https://user-images.githubusercontent.com/67836160/176505530-dee8ebfa-c594-421c-a7ee-81fd03db0793.png)

# Text Preprocessing 

![image](https://user-images.githubusercontent.com/67836160/176505805-75a6c248-5f62-470f-b9ac-7bd8a232cced.png)

![image](https://user-images.githubusercontent.com/67836160/176505836-616d076e-95b5-41e9-a0fe-fe63699535e8.png)

![image](https://user-images.githubusercontent.com/67836160/176505891-1e8627f6-f8d5-463a-9cfe-6f7461b18850.png)

![image](https://user-images.githubusercontent.com/67836160/176505991-089e25e7-d2cd-4a7f-b520-552f6b0ed82d.png)

# Topic Modeling 

* Topic Modeling in NLP is a technique which assigns topics to a given corpus based on the words present

* Topics can be thought of as keywords which can describe a document for example  for topic sports the words related to it are cricket , basketball , tennis

* LATENT DIRICHLET ALLOCATION 
* 
  * LDA is a popular modeling technique to extract topics from a given corpus
  * LDA categorizes the text into document and words per topic
  * Implemented using Gensim package

![image](https://user-images.githubusercontent.com/67836160/176506243-f2143d1a-5880-4fb2-80e5-e2fd5ad948af.png)

![image](https://user-images.githubusercontent.com/67836160/176506272-da87c247-e28f-4d6d-b385-e3166dd5f6be.png)

![image](https://user-images.githubusercontent.com/67836160/176506328-1010a6cd-d641-4463-94b5-543093495c34.png)

![image](https://user-images.githubusercontent.com/67836160/176506363-3ea9445f-9458-4982-b69e-1366008c45f7.png)

![image](https://user-images.githubusercontent.com/67836160/176506395-47a2e748-de10-4424-aa2f-823550cbea8d.png)



