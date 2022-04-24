# Election_Analysis
## Purpose
The purpose of the assignment was to analyze votes in a election to determine the winner, and all largest voter turnout by county
## Analysis
Below is a high-level summary of that analysis completed

  
  * There were 369,711 votes cast in the election
      * The code used to calculate total votes was as follows after initializing the variable for Total Votes to zero: ![Total Votes](https://github.com/tori-taylor/Election_Analysis1/blob/main/Resources/Total%20Votes.PNG)
  * Below is a breakdown of the vote count and percentage by county, which is also in the text file
       * ![County Votes](https://github.com/tori-taylor/Election_Analysis1/blob/main/Resources/County_Votes.PNG)
       * The code used to create the county list and count the number of votes per county is below
       * ![County Votes_Code](https://github.com/tori-taylor/Election_Analysis1/blob/main/Resources/County_Votes_Code.PNG)
  *  Denver had the most votes with more than 80% of the total votes cast
  * Below is a breakdown of the vote count and percentage by candidate, which is also in the text file
       * ![Candidate Votes](https://github.com/tori-taylor/Election_Analysis1/blob/main/Resources/Candidate_Votes.PNG)
       * The code used to create the county list and count the number of votes per candidate is below
       * ![Candidate Votes_Code](https://github.com/tori-taylor/Election_Analysis1/blob/main/Resources/Candidate_Votes_Code.PNG)
   * Diane Degette won the election with 73.8% of the vote or  272,892 votes

## Recommendations
This code would be simple to re-use for other elections as there are no references to specfic candidates or countys. One item you would have to change is telling the code where names or countys (if countys are used) are in the csv file, for example in the data load for this election the candidates are in column 3 which the code references, you would have to change this if the candidate names were in a different column (similar process for county name). Also you would have to load the file with the correct name assuming the data for another election wouldn't have the same file name as this one. You also could be collecting data that is not listed by county, the votes could be listed by province, therefore you would liekly want to change the variables to something that references province. 
