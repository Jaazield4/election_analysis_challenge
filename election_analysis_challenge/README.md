# Election Analysis

## Overview of Election Audit
Determine the total votes in a congressional election. Find the number of votes and percentage of total votes received by each of 
three candidates. As well as find the voter turnout for three counties, Arapahoe, Denver, and Jefferson, to determine the county
with the highest voter turnout, and print all the results on a text file using VS Code.

### Purpose
The purpose of this project is to practive using the python language in VS Code to get data from a large spreadsheet without the
need of going through thousands of rows of data. By completeing the election_analysis_challenge it helped gain experience in creating
lists, dictionaries, adding to a list or dictionary, performing calculations, use repition statements, conditional statements, and print
statements using f-strings. Putting all these skills together allowed us to get the information needed from the data.

## Election-Audit Results
  -Total Votes in Election = 369,711
    Obtained by initializing a total vote counter using "total_votes = 0" then adding one for every vote using "total_votes = total_votes + 1" 
  
  -Breakdown of each county
  
  ![image](https://user-images.githubusercontent.com/85451089/125231106-c3590280-e29f-11eb-9442-d3f0bafae004.png)
    
    As you can see in the picture above taken from the election_analysis text file, Jefferson received 10.5% of the total votes meaning there
    were a total of 38,855 votes counted in Jefferson county. Denver had the majority of the total votes with 306,055 votes counted in the Denver
    county being 82.8% of the total vote. Arapahoe had the lowest voter turnout with only 6.7% of the total votes translating to 24,801 votes.
    
  -Largest county votes
    Denver had the largest voter turnout with 82.8% of the total votes coming from the Denver county. This was found by using a conditional 
    statement that determined which county had the most votes counted.

  -Breakdown of candidate votes
    There were a total of three different candidates which could be chosen from. These were Charles Casper Stockham who 
    received 23% of the total votes (85,213 votes), Diana Degette receiving 73.8% of the votes (272,892 votes), and 
    Raymon Anthony Doane receiving 3.1% of the votes (11,606 votes)
    
  -Winning Candidate
    The winning candidate was Dianna Degette who received a total of 272,892 votes which was 73.8% of the total votes counted for the three counties.
    
![image](https://user-images.githubusercontent.com/85451089/125232664-b689de00-e2a2-11eb-821a-80a5b5cc7bce.png)

    
    The picture above is taken from the text file and was added using the code "txt_file.write(winning_candidate_summary" on the PyPoll_Challenge.py.
    Using the conditional statement and f strings below we were able to attain the information for the winning candidate and print it to election_analysis.txt.
![image](https://user-images.githubusercontent.com/85451089/125232300-eedcec80-e2a1-11eb-88de-da17a2f9308e.png)
    
## Election-Audit Summary
Using the code in the Pypoll_Challenge as a blueprint it is possible to make minor modifications to run the same analysis for any
other election. The first step would be to replace the excel file located in the resources folder with the data from the new election
that is to be analyzed. Once doing so it would just require changing "'election_results.csv'" to the new csv file. This would heppen 
in the very top of the code in the area depicted below. Once the resource file is changed then all the data will be pulled from there. 


![image](https://user-images.githubusercontent.com/85451089/125226046-ee3e5900-e295-11eb-9635-1d51bc76fdfa.png)


The second most important thing to change is adjust the variables to the row they are in the csv. The following code would be ammended 
to fit the criteria in the new imported csv. Depending on what row the candidate name's and county name's are is where the number inside
the brackets would be changed to.


![image](https://user-images.githubusercontent.com/85451089/125230582-aa038680-e29e-11eb-8ed0-a101e78da5be.png)


After changing the file the next step would be to adjust the variables to what is needed. If you're looking at cities as opposed to 
counties, then it would require changing the variables to cities in order to make the code easier to read and understand. 
