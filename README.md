# Using Airline Tweets to create a perceptual map of the US Airline Market. 

**Project Description** - **This is a marketing analytics project that helps answer the following questions: how do US travelers perceive different domestic airlines? Do certain airlines have better brand perception than others?** In this project, a dataset with tweets about domestic US airlines from February 2015 is used to create a perceptual map of the US Airline Market, which can be used to understand how US domestic travelers perceived different airlines in 2015. 

**Steps Taken for this Analysis**: 

1. Cleaning all the tweets in the dataset
2. Using Topic Modeling (Latent Dirichlet Allocation) to figure out what are some of the overarching topics (product attributes) discussed in the tweets
3. Once the overarching topics (customer service, on-time performance/cancellations, etc.) are identified, keywords are used to assign tweets to a specific topic 
4. Performing sentiment analysis on all the tweets
5. Calculating the percent of positive, negative, and neutral tweets for each topic identified to get product attribute scores for each airline
6. Applying multidimensional scaling to generate the perceptual map from the product attribute scores

**Domestic US Airline Market - Perceptual Map**: 

![]('images/US Airline Perceptual Map.png')
