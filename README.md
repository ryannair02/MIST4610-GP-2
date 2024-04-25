# MIST4610-GP-2

Team Name: Group 4

Team Members:

Marko, Matthew, [@Matthew-Marko](https://github.com/Matthew-Marko)

Muddala, Aniketh, [@anm36176](https://github.com/anm36176)

Nair, Ryan, [@ryannair02](https://github.com/ryannair02)

Pasupuleti, Chaitanya, [@cp12312112](https://github.com/cp12312112)

Valladares, Matthew, [@MatthewValladares](https://github.com/MatthewValladares)

Description: Our data was obtained from DATA.GOV and the database was called Recalls Data created by the Department of Transportation from the NHTSA campaign. The dimensions of our columns and rows are 27886 by 15 respectively. The various columns are: Report received Date, NHTSA ID, Recall Link, Manufacturer, Subject, Component, MFR Campaign Number, Recall Type, Potentially Affected, Recall Description, Consequence Summary, Corrective Action, Park Outside Advisory, Do Not Drive Advisory, Completion Rate % The DATA TYPES are: Date, Time, VARCHAR, TEXT, INT. 

The dataset comprises recall details pertaining to particular NHTSA initiatives. Users have the option to refine their search based on criteria such as manufacturer and component. Additionally, filtering by recall category—tires, vehicles, car seats, and equipment—is available. The dataset encompasses campaign data dating back to 1966. It shows completion rates sourced from the most recent Recall Quarterly Report or Annual Report, starting from the first quarter of 2015 (2015-1) onwards.

One manipulation that needed to be done on the data was the COUNT function. This was utilized to count the number of recalls during each year. Also, filters were implemented on the manufacturers and type of recall. We put these filters on to narrow down the recalls to the main safety features (seatbelts and airbags) along with only focusing on the main car manufacturers with notable amounts of recalls. Trend lines to better illustrate the purpose of the graphics had also been added.

Questions:

Q1. Over the last 30 years, what car safety recalls have been most prevalent, and when did they start increasing?
<img width="397" alt="image" src="https://github.com/ryannair02/MIST4610-GP-2/assets/150095773/7b45a554-bb14-4190-865e-def8cbe0d51f">

Justification: 
This visualization shows an increasing trend of airbag-related recalls starting in 2014, while seatbelt-related recalls are relatively stagnant. This dramatic increase in airbag-related recalls prompts our second question involving the companies behind these recalls.


Q2. Since the trendline on airbags depicts a sharp increase since 2014, which auto manufacturer is responsible for the most number of recalls?

<img width="468" alt="image" src="https://github.com/ryannair02/MIST4610-GP-2/assets/150095773/190be1e3-85a9-4fed-a1ed-1d00a6b3da43">

Justification: 
This visualization illustrates the companies (BMW, Chrysler, Ford, General Motors, Volkswagon) that are the more prevalent recall offenders as well as the count of the number of airbag-related recalls around their product offerings between the years 2014-2021.

Conclusion: 

According to our findings, between the years of 2014-2021, General Motors had the most number of recalls in the period (81) followed by Chrysler and Ford tied at 61 recalls, Volkswagon at 60, and BMW at 57 recalls. This in part maybe caused by the Takata airbag recall which originated in the year of 2014. These five companies were the overwhelming majority of all auto manufacturer companies' recalls.
