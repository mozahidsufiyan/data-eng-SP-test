# data-eng-SP-test - This dataset is powered by Open Data.
This dataset provides a sample of stagecoach card journeys performed in a week on bus. On journey on bus, card user must touch in at the start, and touch out at the end for journey validation. On buses card users are only required to touch in so to validate their journey.
# Step 1: Data Wrangling
# Completed Journeys
I am interested in exploring journey length and how it interacts with other variables.
# Feature engineering
create a new category called "JourneyTime", which is the total journey time in minutes, as the difference between "ExTime" and "EntTime"
# Step 2: EDA
Now let's explore the data with some visualisations.
Important Observation on 'complete' Dataframe
Comparing Start and End Stations
Most popular stations (Start or End)
Compare days of week
# Step 3: Preprocessing
Prepare data for modelling, creating logical variables and dropping redundant features
# Conclusion
