# UFOs


## Overview 
Utilizing a dataset encompassing various features associated with UFO sightings, a filterable table was created to enable users to search for particular data and display only the corresponding results based on their query across numerous search criteria. The table facilitates seamless exploration and analysis of the UFO sightings data.

## Results 
The revised JavaScript and HTML code now allows users to filter UFO sightings based on date, city, state, country, and/or shape. Upon initially loading the page, all UFO sightings will be displayed. To refine the search, users can input information in one or several categories. 

![image](https://user-images.githubusercontent.com/117605658/235377921-aa502173-e834-497a-a2ec-9f82b65276e8.png)


For instance, if the goal is to explore all UFO sightings in Wisconsin, the focus would solely be on ensuring the sightings occurred in WI. By entering "wi" under the state category, it retrieves all documented sightings within Wisconsin. 

![image](https://user-images.githubusercontent.com/117605658/235377888-3fcbe31e-ec87-4ab4-b6cf-68d7200e59bc.png)


Additionally, it's possible to search using multiple filters. For instance, if the aim is to view all sightings in the United States, specifically in California, with a light shape, inputting these three filters would yield the following results: 

![image](https://user-images.githubusercontent.com/117605658/235377854-0b3f1d15-a272-43f8-9071-51792f6920f0.png)
 

## Summary 
A limitation of the current design is that the filter inputs must exactly match the table data in terms of letter casing, which users might not be aware of. They might input an uppercase letter and receive no results due to this discrepancy.
To address this issue, a function can be implemented to convert all characters to lowercase once they are entered.

Another improvement would be to display a message when no search results are found, informing the user that their search criteria did not yield any results and suggesting they refine their search. Additionally, this message could remind users that entries should be in lowercase. In the current version, the table simply disappears, which might lead users to think that the table is malfunctioning if they assume their search criteria were entered correctly.
