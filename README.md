# miniprojectfifa19

El presente proyecto se elabora como parte de las actividades del Bootcamp de DataAnalytics de Ironhack con el fin de implementar herramientas de análisis de datos a nivel de limpieza, exploración y tratamiento de datos a través de modelo de regresión multilinear Ordinary Least Squares. 

La base de datos utilizada es Fifa21, que se puede encontrar en el siguiente enlace: https://www.kaggle.com/datasets/ekrembayar/fifa-21-complete-player-dataset?select=fifa21_male2.csv

# Planteamiento
The research objective is to identify variables that affect player's market value in the event that a football club is considering investing in quarry players in order to sell them as an income diversification strategy in the mid-long term.

For this purpose, 49 variables have been considered: 
'Name','Age', 'OVA', 'Nationality', 'Club', 'BP', 'POT', 'Height', 'Weight', 'foot', 'Value', 'Wage', 'Release Clause', 'IR', 'Attacking', 'Crossing', 'Finishing', 'Heading Accuracy', 'Short Passing', 'Volleys', 'Skill', 'Dribbling', 'Curve', 'FK Accuracy', 'Long Passing', 'Ball Control', 'Movement', 'Acceleration', 'Sprint Speed', 'Agility', 'Reactions', 'Balance', 'Power', 'Shot Power', 'Jumping', 'Stamina', 'Strength', 'Long Shots', 'Mentality',	'Aggression',	'Interceptions', 'Positioning', 'Vision', 'Penalties', 'Composure', 'Defending', 'Marking', 'Standing Tackle', 'Sliding Tackle', 'Goalkeeping'

Variables that aggregate other variables (indices) have been mostly excluded due to:
1. information would be redundant - most aggregated variables are composed of a player's physical and mental attributes but it is nos disclosed as the exact variables icluded or weighs assigned to them.
2. Due to the nature of the study, it is important to know as detailed as possible what physical and mental attributes of a player 

Variables that were specific to a players base position were excluded as well
