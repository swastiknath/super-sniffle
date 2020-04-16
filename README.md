# Performing ETL with Cassandra

We perfrom an Extract Transform Load Pipeline on a Log Dataset using Apache Cassandra on the following dataset

## Now the CSV file titled <font color=red>event_datafile_new.csv</font>, located within the Workspace directory.  The event_datafile_new.csv contains the following columns:

- artist 
- firstName of user
- gender of user
- item number in session
- last name of user
- length of the song
- level (paid or free song)
- location of the user
- sessionId
- song title
- userId

The image below is a screenshot of what the denormalized data should appear like in the <font color=red>**event_datafile_new.csv**</font> as the ETL process progresses:<br>

![Dataset](https://github.com/swastiknath/super-sniffle/raw/master/image_of_cassandra_etl.jpeg)

## We Create queries to ask the following three questions of the data

##### 1. Returning the artist, song title and song's length in the music app history that was heard during  sessionId = 338, and itemInSession  = 4


##### 2. Returning only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
    

##### 3. Returning every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'
