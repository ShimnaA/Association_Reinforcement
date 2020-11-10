***Association Rule Learning***

 - Apriori
 
 - Dataset - Market_Basket_Optimisation.csv

 - People who bougth this also bought
 - DataSet contains a list of products bought together by each customer in a week
 - 
 - Question : Determine the most associated product to make deal - Buy this Get that
 
 - minimum Support 
         - consider only product bought atleast 3 times in a day. 
         - Since a weeks data - 3 * 7 times in a week
         - minimum support  = 21/7501 = 0.003
 - minimum Confidence
         - 0.2
         
 - minimum lift 
         - 3  (take values from experience - 3, 4, 5, 6, 7)
  - Train an apriori model with the dataset
         
  - Result - fromage blanc and honey are bought together 
  ------------------------------------------------------------------------
 
 - Eclat
 
 - Trivial and much faster approach
 - Simplified version of Apriori
 - Considers only Support
     - Support(P) = # Customers Basket containing P / total # Customer Baskets
     - P the set of 2 products
     
 - Train apriori model with the dataset.
 - Result is taken as the set of products with highest support value
 - herb & pepper and ground beef (0.015998)
 ---------------------------------------------------------------
      
    
                  
     