# polly_movie
Amazon Polly will use different voices to act out movie scripts you provide

Found a simple movie script parser on this post:
http://ask.metafilter.com/274007/Parsing-movie-TV-scripts

Connected it to Julien Simon's PollyApi module:
https://github.com/juliensimon/aws/tree/master/rekognition

Added a simple Dictionary to set voices, and added Polly capabilities. 

This is nothing fancy but i thought it would be funny to listen to.

python parse_movie.pl < startrek.txt

#TODO 
- Set a list of voices and auto assign the Polly voices to actors
