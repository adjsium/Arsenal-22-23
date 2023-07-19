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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#references">References</a></li>

  </ol>
</details>

<h3>How to see interactive graph</h3>
<img src="https://imgur.com/6kPobQm.gif" alt="how-to" width="400">
<details>

<summary>Open Notebook in Colab</summary>

### Click into .ipynb file and open file in Google Colab

[Google Colab](https://colab.research.google.com/github/adjsium/Arsenal-22-23/blob/main/Arsenal%20notebook.ipynb)

<img src="https://imgur.com/t3PNxfN.png" alt="colab" width="600">

### Click Runtime and Run All

<img src="https://i.imgur.com/u9xzHKj.png" alt="runtime" width="600">

### This notebook is connected to GitHub Click Run anyway
<img src="https://i.imgur.com/FGma5qY.png" alt="warning" width="560">

### Scroll down to see interactive plots by Plotly Library
<img src="https://imgur.com/6kPobQm.gif" alt="how-to" width="560">

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
<h4>First, lets take a look of seasonal average data:</h4> <br>
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


## Contributing

We welcome contributions to the Arsenal 2022/2023 Premier League Data Analysis project! If you are interested in contributing, please follow the guidelines below:

1. **Fork the Repository**: Start by forking this repository to your own GitHub account.

2. **Clone the Repository**: Clone the forked repository to your local machine using the following command:

3. **Create a Branch**: Create a new branch for your contribution. Use a descriptive branch name that reflects the nature of your work.

4. **Make Changes**: Make the necessary changes or additions to the project files based on your contribution.

5. **Test Your Changes**: Ensure that your changes are working as expected and do not introduce any issues.

6. **Commit Your Changes**: Commit your changes with a clear and descriptive commit message.

7. **Push Changes**: Push your changes to your forked repository.

8. **Submit a Pull Request**: Go to the original repository on GitHub and submit a pull request. Provide a clear and detailed description of your changes and the purpose of your contribution.

9. **Review and Collaboration**: The project maintainers will review your pull request, provide feedback, and collaborate with you to ensure the quality and compatibility of your contribution.

Please note that by contributing to this project, you agree to license your contributions under the same open-source license as the repository.

Thank you for your interest in contributing to the Arsenal 2022/2023 Premier League Data Analysis project! We appreciate your support and look forward to your valuable contributions.


## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The MIT License is a permissive open-source license that allows modification, distribution, and commercial use of the project's code and assets. However, it requires including the original license and copyright notice in any copies or derivatives.

Contributions to this project are welcome. By contributing, you agree that your contributions will be subject to the terms of the MIT License.


## References

- [FBref](https://fbref.com/): A comprehensive football statistics website providing detailed data on teams, players, and matches.
- [Stats Perform Opta](https://www.statsperform.com/opta/): A leading sports data provider offering advanced analytics and performance metrics.
- [Football-Data.co.uk](https://www.football-data.co.uk/): A reliable source for football data, including historical match results and betting odds.

The data and information used in this project were sourced from the above references. Please refer to the respective websites for detailed data usage and attribution requirements.
