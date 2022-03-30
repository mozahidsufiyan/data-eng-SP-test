# data-eng-SP-test - This **data.csv** dataset is powered by Government(Transport) Open Data.
This dataset provides a sample of stagecoach card journeys performed in a week on bus. On journey on bus, card user must touch in at the start, and touch out at the end for journey validation. On buses card users are only required to touch in so to validate their journey. Feel free to use any programming language but prefered lanuage or framework would be Pyspark, Scala or python framwork(Django).
We’d like to see you in action using some of the tools and techniques that you’re likely to encounter on the job.  

With that in mind, please prepare a worked example for us – a 10 -15 minute demo to be followed by Q&A – demonstrating the points below and including any additional insights you may wish to share on best practice / recommendations.  

# Problem Statement  
How can we use data to work out the optimal routes to help more people make the frequent journeys to promote Electric Bus on these routes?  
Deploying ETL application to Kubernetes engine and understanding . Please provide live demo for deploying application to Kubernetes. 

## Step 1: Data Wrangling
### Completed Journeys
I am interested in exploring journey length and how it interacts with other variables.
### Feature engineering
create a new category called "JourneyTime", which is the total journey time in minutes, as the difference between "ExTime" and "EntTime"
## Step 2: EDA
Now let's explore the data with some visualisations.
Important Observation on 'complete' Dataframe
Comparing Start and End Stations
Most popular stations (Start or End)
Compare days of week
## Step 3: Preprocessing
Prepare data for modelling, creating logical variables and dropping redundant features

## Conclusion

## Step 4: The Challenge for DataOps
1. Please deploy above ETL application to the Kubernetes engine.  
2. You may want to touch on how these tools can be used to support scaled Data Engineering solutions within large enterprises. 

# FAQ 
Any software that you need to complete the challenge should be readily available online. 
Should you have any questions please reach out to Moz Sufiyan @ msufiyan@scottishpower.com  
