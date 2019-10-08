# Apparel Recommendation System
Problem Statement:- To recommend similar items/products in e-commerce.

This work is done as a part of the workshop conducted by Applied AI Course on Amazon Apparel Recommendation Engine. The data has been taken from Amazon.com in a policy compliant manner. Please Visit https://docs.aws.amazon.com/AWSECommerceService/latest/DG/Welcome.html for more information.

About 183K datapoints(product details) were provided, but it was reduced after data cleaning and pre-processing to 16K. Originally extracted with 19 features of products, only 7 have been considered as a part of this work in order to reduce complexity as well as duration.
The files included here are as follows: 
16k_apperal_data_preprocessed- this is the pre-processed data file.
AppliedAIWorkshop.ipynb- this is the original code which explains everything.
ApparelRecommendationEngine.ipynb- this is my final code which uses weighted IVF- word2vec with brand, colour and image in recommending the apparel
