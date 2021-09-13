# College Football Statistics

 College football Saturdays are some of the best of the year. My interest in this idea derived from  The incorporated data are team stats from 2018 through 2020. 
 This is a non relational database. 

## Sources (Extract): 
    The data comes from the NCAA. The source csv files came from Kaggle.com.
    
## Transform: 
    1. Added years for each file. 
    2. Added unique IDs. 
    3. Split Conferences from thier respective Teams.
    4. Update column names.
    5. Append each file to each other. 

## Load: 
    The tables loaded into the database from the original CSVs were:
    
     - 'offense_passing'
     - 'defense_passing'
     - 'penalties'
     - 'offense_punts'
     - 'defense_punts'
     - 'offense_redzone'
     - 'defense_redzone'
     - 'offense_rushing'
     - 'defense_rushing'
     - 'sacks'
     - 'turnovers'
     - 'win_loss'
     - 'offense'
     - 'defense'
     - 'offense_firstdowns'
     - 'defense_firstdowns'
     - 'offense_fourthdowns'
     - 'defense_fourthdowns'
     - 'offense_kickoffs'
     - 'defense_kickoffs'
     
     The above tables were chosen as I believed these were the best way to group the available data. I believe these give the user querying the database the best results when
     comparing teams and their respective stats.
  
    
