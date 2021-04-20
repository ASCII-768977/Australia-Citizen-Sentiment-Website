# Australia-Citizen-Sentiment-Analysis
Australia Tweets Data Analysis Project


The platform mainly analyses Australia’s sentiment and attitudes towards China, Covid-19 and Happiness. Ansible is used to archive fully automated deployment, including generating Nectar instances, configuring virtual environments, and building network servers. The project uses the Stream and Search API to collect tweets and store them in the CouchDB server. Furthermore, only English tweets are selected. Other languages are not included in the analysis.

Vader_Lexicon is used to analyse related emotions for the collected tweets. It divided tweets into positive, neutral and negative three types of sentiments. We also obtained crucial information about people in different areas of Australia, such as population age, population number, income information in AURIN (https://aurin.org.au/). 

By comparing the local people’s sentiment on the specified topic with the primary Aurin data, we generated a corresponding sentiment analysis chart to facilitate the exploration of different people’s views and attitudes on the specified topic. Also, a simple linear regression model is draw to explore the emotions of Australians under different basic data. Finally, we analysed the areas where the platform needs improvement and expansion plans.

Video link: https://youtu.be/UeD7XCTFyeg