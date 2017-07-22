# Twitter-Sentimental-Analysis
This project is a twitter sentimental analysis project based on the 2016 US election data. The main objective for us was to predict the chances of the electoral candidates HillaryClinton and Donaldtrump on various US states	
# Description 
The data extraction process for this project was critical as we had to crawl data using the Twitter API. The data extraction process involved collecting data that tweeted about the twitter handles @realDonaldTrump and @HillaryClinton. We were able to extract data from different parts of the world for our project. Since our main objective was to concentrate on the sentiments of the people in US we stuck to the tweets tweeted from different parts of the US. We were then able to create visualizations using cartograms and other visualization methods to intuitively understand the sentiments of the people from different states in the US. 

# Files 

submit.html - Home page containing separate options to analyze and understand the stats about Donald trump and Hillary Clinton

WordCloud.html- This page contains the word clouds for Donald Trump and Hillary Clinton.These wordclouds contained the most prominent words spoken when tweeting about @realDonaldTrump and @HillaryClinton.

Nodetmp.html - This page contains the nodes for Donald Trump. These are nodes from the n gram model with which we construct a force directed graph

Nodehil.html - This page contains the nodes for Hillary Clinton. These are nodes from the n gram model with which we construct a force directed graph

Wordgraph.html - This page contains the force Directed graph for Hillary Clinton. With this graph we could intuitively analyze the  top bigram , trigram and 4 gram nodes.

Wordgraph2.html - This page contains the force Directed graph for Donald Trump. With this graph we could intuitively analyze the  top bigram , trigram and 4 gram nodes.

Geoviz.html -  This page contains the cartogram for Donald Trump and Hillary Clinton. With this page we could effectively compare the amount of positive and negative tweets tweeted in each state for Donald trump and Hillary Clinton. The data here was collected at different times of the week and month and then normalized. The normalized data is then mapped to each state in the United States.

Report.pdf - This contains the final report which summarizes the overall analysis performed the intuitions that were got and the cisualizations that were created

# Folders

Data - Contains the sourse data and other json files foe Geovisualization br\
   |__ nst_2011.csv - The csv file that contains the data across each state br\
   |__ The other files are built-in jsons that are required for Geovisualizing the data br\

WordClouds - Contains Wordcloud inputs and outputs that were used for our visualization.

lib - Contains javascript libraries that are required











