# Weather_AI

Hi Spencer
Hi Benny

Find a weather API.
Figure out how to get hourly data into Python as vectors (Temp, Humidity, Vectors for wind direction, etc.) 
Pick a model to train and predict hourly data on, ideally with confidence scores.
Then either predict a week of hourly data based on the past month or so.
Or iteratively predict 1 hour at a time, and multiply the confidence scores to get the decreasing confidence for each hour.
Write function that just requests the next week of predictions from the current time.
Have some sort of main 24/7 runner that does this every hour
Store all actual data vs predicted data in SQL or MongoDB database.

Then start website, which should be able to show current weather, as well as forecasted predictions against ai predictions, as well as past results (graphs, etc.)
