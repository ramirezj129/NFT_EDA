# NFT_EDA
### Purpose:
Created a jupyter notebook where I used the pandas library, and matplotlib for EDA of an NFT dataset.

#### Process:
  First I used pandas to read in the .csv file data set I was working with, next I needed to determine the size of this data set and it's Data types. Next I determined there were columns that were unnecessary in my EDA so I deleted/dropped the corresponding columns that did were not required
  
  Once I had a clean data set to work with I asked myself which NFT had the highest sales in order to implement this with my current data set I needed to sort the values according to the sales column and display the top 10 rows in order to visualize them using matplotlib. I was able to create a variable called top_nft which I used to display the top 10 NFTs by name and number of sales as reference using a line graph, but I also created a scatterplot of floor price in USD and the amount of sales for visualization.
  
  Lastly using the seaborn library I created a heat map to check the correlation matrix between a few columns I picked. Overall I asked one final question about what is the highest average volume of an NFT by it's name, creating one final barh plot.
  
