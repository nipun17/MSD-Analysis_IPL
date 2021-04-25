# MSD-Analysis_IPL
MS Dhoni IPL analysis based over the IPL Season from 2008-2019



Indian Premier League (IPL) is a Twenty20 cricket format league in India. It is usually played in April and May every year. As of 2019, the title sponsor of the game is Vivo. The league was founded by Board of Control for Cricket India (BCCI) in 2008.

Content
Data till Season 11 (2008 - 2019)
matches.csv - Match by match data
deliveries.csv - Ball by ball data

matches dataset:
id: Match Id
season: IPL Year
city: City at which match played
date: Date on which match played
team1: Team 1 from the match
team2: Team 2 from the match
toss_winner: Team which won the toss
toss_decision: Bat/Bowl on winning toss
result: Result type if it is normal or No result or Tie/super over
dl_applied: Duckworth Luis apllied
winner: Team who won 
win_by_runs: How many runs does team won
win_by_wickets: How many wickets were left for team which won
player_of_match: Player of the match
venue: Stadium Name
umpire1: Umpire Name
umpire2: Second Umpire Name
umpire3: Third Umpire Name

deliveries Dataset:
match_id: Match Id
inning: Inning no for the match
batting_team: Team batting
bowling_team: Team bowling
over: Over no. 1-20
ball: Ball no.
batsman: Strike Batsman name
non_striker: Non Striker batsman name
bowler: Bowler name
is_super_over: Is it a super over?
wide_runs: Wide ball runs
bye_runs: Byes runs
legbye_runs: Leg byes runs
noball_runs: No ball runs
penalty_runs: Any penalty runs
batsman_runs: Batsman runs
extra_runs: Extra runs
total_runs: Total runs
player_dismissed: Batsman name who got out
dismissal_kind: Type of dismissal
fielder: Fielder name if its run out or catch
