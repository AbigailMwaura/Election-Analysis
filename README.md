# Election-Analysis
## Election Audit Overview
Colorado Board of Elections has requested an audit of a recent local election and the analsis should include:
  1. votes casted
  2. candidates who received votes
  3. percentage of voters for the winning candidate
  4. winner of the election based on popular vote
  5. county with the highest turnout
  6. percentage of votes from winning county based on total count
  ## Resources used
  - election_results.csv
  -Python and VS Code
  ## Results
  Candidates and votes:
 
   -Diana DeGette-> lead with 73.8% or 272,892 votes
   
   -Charles Casper Stockham-> second place with 23.0% or 85,213
   
   -Raymon Anthony Doane-> last place with 3.1% or 11,606
   
      Total Count: 272,892 votes
###### vote count by county
  -Denver: 82.8% or 306,055
  -Jefferson: 10.5% or 38,855
  -Arapahoe: 6.7% or 24,801
   County withh the highest turnout
              Denver county with 306, 055 votes
 ## Command line results 
 <img width="1155" alt="Screen Shot 2020-12-30 at 11 15 54 PM" src="https://user-images.githubusercontent.com/74630767/103396083-bab89000-4af6-11eb-9dd5-8a0be606a851.png">
## Election Audit Summary
The Colorado election commission now has a script that could be updated as needed to allow access to the most recent data. This can be done using file_to_load= os.path,join(Resources", "election_results.csv"). To add congressional districts loops and if statments can be used for candidates and counties.




