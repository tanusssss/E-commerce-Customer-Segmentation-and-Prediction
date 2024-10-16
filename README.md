# E-commerce-Customer-Segmentation-and-Prediction 
Drive Link for original Dataset : https://drive.google.com/file/d/19VGX8gQw3sun0YOTj_g4IGwNs0jbsK-I/view?usp=sharing
This project aims to enhance marketing strategies and customer retention for an e-commerce company by gaining a deeper understanding of their customer base based on their purchasing patter. By leveraging machine learning, the project seeks to segment customers and predict future purchasing behavior. 

Project Outline : How I approached the problem 
        
I Found 2 Parts to work on : 1)Customer segmentation 2)Products segmentation
           
    1)  Feature Engineering : I Realised, with Recency, Monetary and Frequency, 'Cancellation Percentage of Each Customer also matter in Churning.' I wanted to Highlight that. So, though I have Visualised data on Recency, Monetary and Frequency I have trained the model with CancellationFreq Feature. To segment Customers More Deeply.

        I have Also considered Monetary and Frequency outliers, seperate as well as common property and trained model for Non Outliers dataset to generalise the model. But In the end I have called Outliers dataset, plotted and visualised, Then clustered them with labeling each segment with -ve sign (-1,-2,-3) because it was manual and not by model. Gave Business recommandations for each segment and added them back to Main dataset.

         So, this is how, I did not Ignored outliers since there were Upper bracket Outliers as well as Lower Bracket Outliers., and recommandated the Solutions for each segment manually
        
     2)Model Building and Evaluation
               
         ] Segment Visualising For Interpretation step: Before Interpretation step, I have created a ccount plot for 'Customers Count in each cluster' on the scatterplot for Recency, Monetary, Frequency and CancellationFreq respectively, to visualise On the same output. So, the Viewer can See Visualisation and can relate to each cluster Interpretation
        
      3)Product Popularity finding for targeted  product Promotions

          Intituively, CancellationFreq and Quality/Popularity of the product have relation.So, I ranked the columns with rank() function., used qcut() to seperate and Identify most popular products to least Popular product., And have added these ratings to final Dataset/excel file. So, viewer can relate and visualise and the same time the Customer Segment and their Purchase product, and same time find out rating of the product., to generalise and Predict the behaivior.
        
      4)visualising final findings of the Project. : In the last we have visualised Cluster Distribution with Average Feature Values., with the help of overlapping Lineplot and Barplot. 
        
      5)Dataset Overview : while working on the iven dataset :

      Original_Dataset : rows : 5,41,909
      
      prediction_dataset Final : rows : 4,06,789
        
      Overall Data Retained and Used : 75%

#best E-commerce-Customer-Segmentation-and-Prediction 
#E-commerce-Customer-Segmentation-and-Prediction Proeject
