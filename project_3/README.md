# NLP CLASSIFICATION FOR AD TARGETING

---
## BACKGROUND

---
There is increased competition in the space for coding bootcamps. Bootcamps such as Hack Reactor, Vertical Institute, Rocket Academy and Le Wagon. If no action is taken, there will be a decline in market share, poor marketing return of investment (ROI), poorer lead generation which means we will not be able to meet the enrollment KPI's.

GA marketing is therefore trying to figure out how to better identify the online persona of a bootcamp seeker as opposed to that of a computer science major to aid in targeted advertising.


Considering the two topics have quite a bit in common, efforts to further segregate the two targets could yield better advertising ROI.


## PROBLEM STATEMENT

---
Due to increased competition in the market for bootcamps. General Assembly has been facing poorer enrollments and they intend to maintain their position as one of the better bootcamps out there. We are team of data scientists that are being tasked by General Assembly to build a model with >90% accuracy that helps to identify between those who are looking for bootcamp style learning vs computer science majors/prospective students based on the words they use online.

## WORKFLOW

---
1. Gather Data
2. Clean Data
3. Exploratory Data Analysis
4. Modelling
5. Evaluation

## KEY FINDINGS

---
On reddit, from the features, there were other bootcamps that were physical, online and websites that were mentioned more. General Assembly's(GA) name did not feature in the top 50 bi-gram words for each subreddit. If you look at this positively, GA has the potential to reach to a larger audience and be more talked about and potentially get more enrollments. 


## CONCLUSION

---
In conclusion, GA needs to stand out from our competitors and speed is also essential in being able to act before our competitors. For the marketing team, you have to maximise our marketing ROI and increase our conversion rate.

## DATA DICTIONARY

---
| Feature | Type | Dataset | Description|
| :--- | :--- | :--- | :--- |
| subreddit | Object | cs_major / coding_bootcamp | Subreddit contains the topic of the subreddit in the dataframe. Either cs Major or coding bootcamp|
| selftext | Object | cs_major / coding_bootcamp | selftext contains the text or the message of the post written by the end user. |
| title | Object | cs_major / coding_bootcamp | title contains the title of the post. |
| csMajors | Object | cs_major | csMajors is the topic or also known as the subreddit. csMajors refers to Computer Science Major that universities offers to students. |
| coding_bootcamp | Object | coding_bootcamp| coding_bootcamp is the topic or also known as the subreddit. coding_bootamp refers to coding bootcamps that are taken by mid-career switches, companies and students who are interested in upskilling. | 
| combined_text | Object | cs_major / coding_bootcamp | combined_text is the combined columns of selftext and title. |