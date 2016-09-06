
Data description for Meetup geographic dataset.

1. user_lon_lat.csv represents the geographic location for each user's home
  location (inferred from user's own home address by meetup.com). The csv file
  contains three columns, which are user_id, longitude and latitude,
  respectively). E.g. a line "1,-75.690002,41.410000" represents user "1"'s
  home location has longitude "-75.690002" and latitude "41.410000". Some 
  user_ids may not appear in the file, since not all users have their location
  specified

2. event_lon_lat.csv records the geographic location for offline social events.
  Similarly, the file has three columns, which are event_id, longitude and
  latitude, respectively. E.g. a line "68561,-84.368683,33.781757" means event
  "68561"'s venue is located at longitude "-84.368683" and latitude
  "33.781757". Also, some event_ids may not appear in this file, since not all
  events have venue location identified.
