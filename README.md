# Election Audit

## Overview of Audit:
The Board of Elections requested analysis of the tabulated results from the US Congressional precinct in Colorado. A report was conducted for the total number of votes cast, the total number of votes for each candidate, the percentage votes for each candidate, and the winner of the election. 

The election commission then requested some additional data to complete the audit including the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout.

## Election-Audit Results

<img width="434" alt="Screen Shot 2022-08-01 at 10 32 39 PM" src="https://user-images.githubusercontent.com/106785377/182292275-de72b110-23e0-49b1-9311-b966c1719ad3.png">

* 369,711 total votes were cast in this congressional election.
     * See line 44 in the code: ``` total_votes = total_votes + 1 ```

* A breakdown of the number of votes and the percentage of total votes for each county in the precinct:
      
      | County      | Number Votes | Percentage of total votes |
      | ----------- | -----------  | ------------------------- |
      | Jefferson   | 38,855       | 10.5%                     |
      | Denver      | 306,055      | 82.8%                     |
      | Arapahoe    | 24,801       | 6.7%                      |

* Denver county had the largest number of votes.

* A breakdown of the number of votes and the percentage of the total votes each candidate received:

      | Candidate                  | Number Votes | Percentage of total votes |
      | -------------------------- | ------------ | ------------------------- |
      | Charles Casper Stockham    | 85,213       | 23.0%                     |
      | Diana DeGette              | 272,892      | 73.8%                     |
      | Raymon Anthony Doane       | 11,606       | 3.1%                      |

* A breakdown of the winning candidate and their vote counts:
    * Winner: Diana DeGette
    * Winning Vote Count: 272,892
    * Winning Percentage: 73.8%


## Election-Audit Summary

The script created for this election audit analysis and summary may be used for any election with the following modifications.
1. Save the raw election resuslts file in a location that can be accessed by the script in line 9. Update the file name as necessary. Update the file name and path in line 11 to the preferred output location and file name.
2. Make sure the Ballot ID is in column 1, County is in column 2, and Candidate in column 3. It's also important to not that this script expects clean data.

