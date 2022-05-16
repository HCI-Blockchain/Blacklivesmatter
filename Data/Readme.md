# DATASET 1 : BLACK LIVES MATTER TWEETS
## Due to data size, DATASET 1 is not directly uploaded on Github. Users can access the dataset by Visiting: https://drive.google.com/file/d/1Z6SfxFA_iHYdDLCaa-2IvaDFHqEUtUkg/view?usp=sharing
| ID     | Frequency | Type                      | Description                                                                     | 
|--------|-----------|---------------------------|---------------------------------------------------------------------------------|
| Date   | 1 day     | datetime64[ns] YYYY-MM-DD | #Blacklivesmatter: from May 24, 2020, to Dec 31, 2020                           |  
| Tweets | message   | String                    | Tweets that contain the hashtag #blacklivesmatter  and has at least three likes |   

# DATASET 2 : STOP ASIAN HATE TWEETS
| ID     | Frequency | Type                      | Description                                                                 | 
|--------|-----------|---------------------------|-----------------------------------------------------------------------------|
| Date   | 1 day     | datetime64[ns] YYYY-MM-DD | #Stopasianhate: from March 15, 2020, to Dec 31, 2020                        |  
| Tweets | message   | String                    | Tweets that contain the hashtag #Stopasianhate and has at least three likes |   

# DATASET 3: TREND BLM
| ID            | Frequency | Type                          | Description                                  
|--------|-----------|---------------------------|-----------------------------------------------------------------------------|
| Date          | 1 day     | datetime64[ns] YYYY-MM-DD     | #Blacklivesmatter: from May 24, 2020, to Dec 31, 2020            |  
| Google Trend  | 1 day     | integer ranging from 0 to 100 | The Google Trends Data is crawled from Google Trends (“Black Lives Matter”, n.d.a) through Pytrends API (General Mills, 2020). The data contains (1) the relative popularity of this topic on Google and (2) the time range for the collected data. |
| Tweet Volume  | 1 day     | integer                       | The total number of tweets by date      
| Tweet Length  | 1 day     | float                         | The average tweet lengths of #blacklivesmatter by date  

# DATASET 4: TREND SAH

| ID            | Frequency | Type                          | Description                                                  |
|--------|-----------|---------------------------|-----------------------------------------------------------------------------|
| Date          | 1 day     | datetime64[ns] YYYY-MM-DD     | #Stopasianhate: from March 15, 2020, to Dec 31, 2020               |
| Google Trend  | 1 day     | integer ranging from 0 to 100 | The Google Trends Data is crawled from Google Trends (“Stopa Asian Hate”, n.d.a) through Pytrends API (General Mills, 2020). The data contains (1) the relative popularity of this topic on Google and (2) the time range for the collected data. |
| Tweet Volume  | 1 day     | integer                       | The total number of tweets by date                                       |
| Tweet Length  | 1 day     | float                         | The average tweet lengths of #Stopasianhate by date                                                                                                                                                                                      |
