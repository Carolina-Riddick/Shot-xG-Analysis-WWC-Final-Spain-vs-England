### Shot xG Analysis – WWC Final Spain vs England

This project performs a visual analysis of shot quality (xG) for three key Spanish players in the 2023 FIFA Women’s World Cup Final against England:

1. Aitana Bonmatí
2. Clàudia Pina
3. Olga Carmona

#### Data

The dataset comes from StatsBomb open event data and includes only shots. The dataframe was filtered to keep the relevant fields for xG analysis, such as:

1. Player name and ID
2. Shot location (x, y)
3. Shot end location (x, y, z)
4. Shot outcome
5. Shot body part
6. Under pressure indicator
7. Expected Goals value (shot_statsbomb_xg)
8. Missing values were checked and cleaned when necessary.

#### Visual Analysis

1. A pitch-based shot map was created to compare players:
2. Each shot is plotted at its on-pitch location
3. Marker size is proportional to the xG value
4. Different colors represent each player for easy comparison

This visualization helps identify where each player took shots from and which attempts had higher scoring probability.

#### Objective

The goal of this notebook is to provide an introductory player-level attacking analysis using open football event data. It highlights shooting tendencies and scoring threat in one of the most important matches in women’s football history.
<p align="center">
<img width="540" height="400" alt="Captura de pantalla 2025-11-19 a las 16 22 26" src="https://github.com/user-attachments/assets/e46b1cc3-cb48-4e2c-be65-c50d22076d1a" />

  
</p>



