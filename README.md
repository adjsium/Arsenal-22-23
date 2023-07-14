<h1 id="top" align="center"> What's Actually Going on with Arsenal in the 2022/2023 Season? </h1>
<h3 align="center"> Arsenal 22/23 Premier league data analytics projects by <a href="https://www.linkedin.com/in/leonardo-wu-tech/">Leonardo Wu</a>, Data from https://www.football-data.co.uk/ and https://fbref.com/
.</h3>  


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents 🏟️</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#background-and-motivation">Background and Motivation</a></li>
      </ul>
      <ul>
        <li><a href="#what-is-xg">What is xG?</a></li>
      </ul>
      <ul>
        <li><a href="#glossary-and-terms">Glossary and Terms</a></li>
      </ul>
    </li>
    <li><a href="#seasonal-average-data">Seasonal Average Data</a> </li>
    <li><a href="#match-result-overview">Match Result Overview</a> </li>

  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
This project aims to utilise Python, Jupyther Notebook and Plotly library to visualise 2022-2023 PL Arsenal seasonal data and gain insight regarding how Arsenal performed this season.
- Question 1: How many matches Arsenal won with higher xG score?
- Question 2: When Arsenal start struggling on title race?
- Question 3: How effecient is Arsenal in this season?

<!-- Background and Motivation -->
### Background and Motivation
As a Arsenal fan and data-savvy person, I am curious the story behind Arsenal's seasonal data and <b> reveal why they struggling at the end of the season</b>, losing #1 position in Premier League thus season.

<h4>League Structure</h4>
The Premier League, consisting of <b> 20 teams</b> , follows a round-robin format. Each team plays <b> 38 matches in a season</b> , facing every other team twice. A win  earns<b> 3 points</b> , a draw results in<b> 1 point</b>, and a loss gives <b>no points</b>. The team with the most points at the end of the season is crowned <b>the champion</b>.

### What is xG?
Expected goal (xG)  is a way to measure the quality of a team or player's chances of<b> scoring a goal</b>. It takes into account factors like the <b>location of the shot</b>, <b>the type of shot</b>, and the <b> number of defenders </b>in the way. The higher the xG, the <b><i>more likely </i></b>a team to score.

### Glossary and Terms
- GF:Goals For (sometimes used in place of GS).
- GA:Goals Against (i.e., number of goals conceded by a team).
- ST:Shots Taken
- SA:Shots Against
- SOT:Shot on Target

## Seasonal Average Data
<h4>First, lets take a look of seasonal average data:</h4>h4> <br>
<img src="https://github.com/adjsium/Arsenal-22-23/assets/88283412/6349031e-fbb1-4303-8ca0-ea960ecbc58f?raw=true" width="700">
<details>
  <summary>Nerdy numbers 📈</summary>
- Point per match: 2.21053</br>
- Goal per match: 2.31579</br>
- Goal against per match: 1.13158</br>
- Corners taken: 5.86842</br>
- Corners against: 3.71053</br>
</details>


## Match Result Overview
<h4>Comparision on Shooting Stats and Cornering Statistics:</h4></br>
<img src="https://github.com/adjsium/Arsenal-22-23/assets/88283412/23c5cee8-ede2-4fd5-88d2-288626d7a834?raw=true" width="700"></br>
<h4>xG/xGa Statistics by match week:</h4></br>
<img src="https://github.com/adjsium/Arsenal-22-23/assets/88283412/41c2e368-0d28-429f-9f26-8f4187e52959?raw=true" width="700"></br>

Expected Goals (xG) that's used to measure how good scoring chances were in football games. Crazy thing is, sometimes <b>the team with a higher xG loses</b>, and <b>the team with a lower xG wins</b>. This can happen because the team with more xG might choke and not score, while the other team is more efficient and scores with less chances. So basically, having a high xG doesn't guarantee winning in football games.
<h4>Shooting Accuracy</h4>
<img src="/%20Data_Visualisation/Shots:Shots%20On%20Target.png?raw=true" width="700">

As indicated by the graph, Arsenal shooting accurcy drop since mid January 2023, the accurcy is below <b>35%</b> in the following <b>10 matches</b>.
