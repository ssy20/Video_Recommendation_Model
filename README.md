# Video_Recommendation_Model
Given information about videos uploaded on an online video streaming company, build a model decide which videos should be promoted on the home-page. 

# Data

- video_id : unique for each video
- count : total count of views for each video
- date : on which day that video was watched that many times
- video_length : length of the video in seconds
- video_language : language of the video
- video_upload_date : when the video was uploaded
- video_quality : quality of the video. 

# Porject description 
Classify videos based on two dimensions: the daily percentage change of view counts and the average view counts. Using these two dimensions, the videos can be separated into 3 groups: the trending videos, the stable but popular videos, and everything else. The trending and popular videos are the candidate to be shown on the home page. 

Once all the videos are labeled, identify the main characteristics of the trending videos using decision tree.

# Model result
Approximately 18% of all the videos are labeled as trending videos, 10% of them are labeled as popular videos. On average, the percentage change of daily view counts of trending videos is 2%.

Videos that are uploaded recently are more likely to be trending videos. Besides time recency, shorter videos are more likely gain popularity. Videos in English have a slightly better chance of being popular than videos in other languages.
