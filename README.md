# Election_Analysis

## Overview of Election Audit

The purpose of the election audit analysis was to assist Tom, an employee of the Colorado Board of Elections, in auditing the election results for a U.S. Congressional precinct in Colorado.  Specifically, the election commission requested the following data: 
<ol>
  <li>The voter turnout for each county</li>
  <li>The percentage of votes from each county out of the total count</li>
  <li>The county with the highest turnout</li>
</ol>

## Election Audit Results

![Election Audit Results](https://user-images.githubusercontent.com/94088129/159726114-9fead0c8-989e-45d1-ad3c-65d93e9dc4a3.png)

The election outcomes are as follows:
<ul>
  <li>369,711 total votes cast in the election</li>
  <li>Number of votes and percentage of total votes by county</li>
    <ul>
      <li>Jefferson: 10.5%, 38,855 votes</li>
      <li>Denver: 82.8%, 306,055 votes</li>
      <li>Arapahoe: 6.7%, 24,801 votes</li>
    </ul>
  <li>Largest County Turnout: Denver</li>
  <li>Number of votes and percentage of total votes by candidate</li>
    <ul>
      <li>Charles Casper Stockham: 23.0%, 85,213 votes</li>
      <li>Diana DeGette: 73.8%, 272,892 votes</li>
      <li>Raymon Anthony Doane: 3.1%, 11,606 votes</li>
    </ul>
  <li>Winning Candidate: Diana DeGette</li>
  <li>Winning Vote Count: 272,892 votes</li>
  <li>Winning Percentage: 73.8%</li>
</ul>

## Election Audit Summary

The script utilized was able to accurately audit the election results and write the conclusions of said audit to a text file for easy reading.  With a few modifications, this script could be utilized for any election.  For example, in the script there is a For Loop to populate a dictionary with the names of the counties relevant to the election.  For a national election, any variable beginning with "county" could easily be altered to state (i.e. "county_name" would become "state_name").  Additionally, you could use an IF Statement to add a variable to identify the county (or other region, like state) with the lowest voter turnout.  That would be useful for future elections, to identify areas in which voter turnout may need to be increased.  The script is highly modifiable for whatever election situation necessary.
