# Election Analysis


## Overview of Election Audit

Throughout this analysis we will be breaking down some additional data points in the outoverview of the tabulated results for a U.S. congressional precinct in Colorado. Using Python to create an automated and valuable tool that can be applied to multiple proejcts as a scrit template and make adjustments accordingly. 
Some examples of the main extentions used to loop over the voter data are as follows: 

* ```for``` loops
* ```PyPoll_Challenge.py```
* ```election_results.txt```
* candidate_options```.append```(candidate_name)

In this analysis our results will target the following specifications:

1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout


## Election Audit Results

### Looking at the data
* 369,711 rows of raw data
* Counties considered:
```Jefferson```
``` Denver```
``` Arapahoe ```
* Candidates: 
```Charles Casper Stockham```
``` Diana DeGette```
``` Raymon Anthony Doane ```

![Picture3](https://user-images.githubusercontent.com/115853964/201012797-27adb685-1bae-4029-bf95-b3830d3dcfd7.png)

![Election_Results ](https://user-images.githubusercontent.com/115853964/201004437-e881ca8a-dd9d-47e6-a28c-aa544c9fda60.png)

### Winning Canidate:
``` 
Diana DeGette
```

## Election Audit Summary

Election Audit Commission,

The script used in the analysis above provides a versatile and valuable tool for future election and aduited data sets, allowing the user to easily and accurately process larger data sets where numerous or very specific data points can be targeted and analyzed. In this spesific scipt we looped over 369,711 rows of data over three different congressional canidates. In the script we were able to assign a dictionary of values to a specific canidate and then loop over and pull the data. With these base integers from our initial pull is still telling a lot of information so we further break down the script, calculating our data and adjusting our established lists in order to produce a clear and readable automated report. 


The tools versatility comes from the ability to translate data over multiple platform types including ```.txt``` and ``` .csv``` files, storing in some cases thousands of lines of data and manages the all the analysis and calculations from a script that can be adjusted is new data is presented. In the case of elections this can be a very useful tool in larger or smaller elections in creating a template for the specific data points we are looking for. This is particularly helpful when there is more variables that are being considered rather than just 3 like this example. A second part of our loop focuses on the data from the columns and this can hold a lot of variables all depending on the data set being analyzed. 


When changing the script new information can be added or taken away from the lists created in our dictionaries. If the election missed a county those votes can easily be added into the original scipt and avoid an extensive repolling process. This process can also be applied on the opposite end and the same tool can be useful before  or after the election to calculate percentage based trends in a variety of categories which will allow a more accurate system based on real data tendencies. 

Thank you


