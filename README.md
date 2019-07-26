Python Code Louisville Expect Goals (XG) for English Premier League (EPL)

The following project will attempt to analyze whether Expected Goals matches the results of individual soccer games and seasons as a whole in the EPL.

From 538 expected goals are an estimate of how many goals a team “should” have scored, given the shots they took in that match. Each shot is assigned a probability of scoring based on its distance and angle from the goal, as well as the part of the body the shot was taken with, with an adjustment for which specific player took the shot.4 These individual shot probabilities are added together to produce a team’s shot-based expected goals for that match, which may be bigger or smaller than the number of goals it actually scored.

To accomplish this I found a csv file on 538 with game data for the last 3 seasons.   Within this data 538 stores the scores of each game along with the expected goals for each team.  I removed all other leagues concentrating on the English Premier League.  To reach a conclusion on this question I analyzed how closely the actual scores of the games matched up with the expected goal metric.  I also looked at how well using XG to get the final points/standings of a season stacked up against the real results.  

To visualize the data I used bar graphs to measure the accuracy of the xg model versus the actual results and scatter plots to see if the overall shape of the scatter between a actual score graph and a xg score graph was similar.  

Dependencies used were SQLite, pandas, numpy, and matplotlib.

Steps to run file:

Pull repo from https://github.com/kyleb740/python_xg_epl
Open Jupyter Notebooks
Run "xgEpl.ipynb"
