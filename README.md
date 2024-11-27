# Berlin_Mauerweg (with Crime Visualisation)

 This started as a project to visualise Berlin crime along the Berlin wall and turned into a Tableau visualisation project.
 You can access that visualisation at the below link. 
 
### https://public.tableau.com/app/profile/johann.drayne/viz/BerlinCrimeByDistrict/ExecutiveDB
<img width="600" alt="Screenshot 2024-11-27 at 13 35 18" src="https://github.com/user-attachments/assets/ab955152-084f-4208-b0de-46fe5612cd9f">


If you want to read more about the repo,read below... :)

## INFO
#### Analysis
`src/berlin-mauerweg/analysis.ipynb`
#### Data
`src/berlin-mauerweg/data`
#### Figures
`src/berlin-mauerweg/figures`
Interactive plotly figures are saved as .html so you can download, open in your browser of choice and interact with the figures.


 <img width="600" height="500" alt="berlin-crime-slider-example" src="https://github.com/user-attachments/assets/7e12c312-d83a-4e12-8bd4-4d25dd5173e4">
 
# WHY?
I wanted to walk the length of the Berlin wall, but given that it is 155km I would have to walk through the night. 
I did not want to walk through the forest at night, but I was also not a fan of being in remote Berlin districts that I do not know well at 4am after being awake for more than 25hours.
So like any good data enthusiast, I decided to get data from the Berlin police on crime in the different districts in Berlin and compare this to the location of the Berlin wall, to see how 'dangerous' this walk would actually be. 

## CURRENT STATE:
31.10.2024 : Crime data on each district (for various crimes) and Berlin Wall route is plotted. 

## TODO:
- Analyse the probability of a crime being committed in the area given the amount of time I will be spending in any one area given the length of the Berlin Wall and the frequency of crime.
- Add in calculation for the best starting point that minimises chance of crime over the duration of the walk. 
- Add in factors whihc take into account the time of day. 



