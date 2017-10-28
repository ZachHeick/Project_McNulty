# Project McNulty: Supervised Learning and Online Gaming  
### Project 3 of Metis Data Science Bootcamp  

The third project at Metis concentrated on exploring multiple supervised learning techniques to see what we could learn from datasets of our choice. With this in mind, I was drawn to datasets about online video games. The professional video game scene has seen huge growth in both revenue and online stream numbers. Teams are competing for huge cash prizes, and with so much money on the line, these teams are now starting to use data science techniques in order to provide themselves with the best win conditions for the respective game they're playing. I was interested in match data from the most popular game in the world, *League* *of* *Legends*.  

### What is League of Legends?  

*League of Legends* is a multiplayer online battle arena (MOBA) video game published by Riot Games. The game consists of two teams of five human players. Each human player controls a champion with unique abilities and fights against the team of other players. Players can also ban a champion away from the other team, preventing that champion from being picked. The object of the game is destroy the opposing team's nexus, the final structure located in a base surrounded by other defensive structures that must be destroyed prior. Each League of Legends match is discrete.  

### Project Objective  

For this project, I was curious to see if I could predict the winner of a match based on what champions each team picked and banned, as well as what objectives in the game were taken first. The metric I wanted to maximize was accuracy.  

### Terminology  
Definitions for terminology I use throughout the notebooks.  

  * **Champion / Hero**: a player controlled character with unique abilities 
  * **Summoner Spell**: extra spells each champion gets, not unique to champion
  * **First Blood**: the first player kill of the game
  * **Tower**: the outermost defensive structure damaging enemies that get too close, protects the inhibitors and nexus
  * **Inhibitor**: defensive structure located before the nexus, doing no damage to enemies
  * **Nexus**: final defensive structure in a team's base, doing no damage to enemies
  * **Baron, Dragon, and Rift Herald**: neutral objectives located around the game map that teams can kill for in-game stat boosts

---  

`Project_Notebooks` contains the five notebooks for this project.  
  1. `Project_McNulty_SQL_Alchemy.ipynb`  
  2. `Project_McNulty_Cleaning.ipynb`  
  3. `Project_McNulty_Creating_EDA_Dataframes.ipynb`  
  4. `Project_McNulty_EDA_Visuals.ipynb`  
  5. `Project_McNulty_Modeling.ipynb`  

`Project_Data` contains pickle files created from notebooks.
