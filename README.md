# YouTubeInfluencers

This work aims to analyse online YouTube markets (specifically, that of natural hair users) to determine which users are influential in the market. The underlying assumption is that the influential user is not necessarily the one with the most followers, comments, subscribers etc. 

Read 2017-08-17-online-communities for more information on the methodology.

There are 2 jupyter notebooks:

*2017-08-02-network-scrapes: this notebook goes through scraping YouTube for data related to the search 'natural hair type 4c' and outputs as final product a dictionary of channel, video, comment data which serves as input for the next notebook. Searched + 'type 4c' since this is a smaller subset (500 or so) of a much larger market with size 1.3mill.

*2017-08-05-network-from-scrape: this notebook collects the YouTube data and creates interaction network. Methodology described in accompanying documents. 
  
The interaction network has channels (subsetted: see notebook 1) as nodes and the edges between nodes represents the interaction activity between users, measured by comment activity on user videos. 
