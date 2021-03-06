# Bike Sharing Project

## Overview of Project

 Produce a story using data visualizations created using Tableau using public data on a bike-sharing program in New York. The overall goal is to conduct bike trip analysis.

For this analysis, we will also use Pandas to change the "tripduration" column from the CSV Dataset from an integer to a datetime datatype. Then, using the converted datatype, we will create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders Show the number of bike trips for all riders and genders for each hour of each day of the week Show the number of bike trips for each type of user and gender for each day of the week. Finally, we will add these new visualizations to the two we created in this module for our final presentation and analysis to pitch to investors.

- Deliverable 1: Change Trip Duration to a Datetime Format (Pandas)
- Deliverable 2: Create Visualizations for the Trip Analysis (Tableau)
- Deliverable 3: Create a Story and Report for the Final Presentation (README File)

## Deliverable 1:

Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

## Results for Deliverable 1
![Code for Deliverable 1](https://github.com/MuddassirR/bikesharing/blob/main/deliverabe1.png)

## Deliverable 2:
Using Tableau, create visualizations that show:

- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

## Results for Deliverable 2:
**The completed data visualization story can be found [here](https://public.tableau.com/app/profile/muddassir.raza/viz/BikeSharing_16229740475760/FINALSTORYREPORT).**
The data visualization story prior to starting the challenge (module) can be found [here](https://public.tableau.com/app/profile/muddassir.raza/viz/NYCStory_16229673704850/NYCStory). There is a small description provided for each visualization as a caption. 

## Summary

We see from our overall analysis that there are over 80% subscribers and 20% customers/non-subcribers. While this number is high, it could be improved by greater marketing techniques in areas with lower subscribers. We also see that majority of riders were males. Normally, we may think this is because males are more comfortable with going out at night alone, but we see that males and females both have the same time peak in the number of rides per day: both genders generally see an increase in rides between 1 to 5 or 7 AM. We also see that stations that tend to have the highest starting trips also tend to have the highest ending trips, indicating that maintenance can be prioritized towards stations who have more trips assuming they require more care. 
