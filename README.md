# Worlds-LOL-Swiss-Stimulator
This is a web-based Swiss-system format simulator​ designed to simulate the tournament format commonly used in esports (such as League of Legendscompetitions), which combines a Swiss stage with a knockout stage.
Core Tournament Format
The simulator strictly follows a two-phase format: "Round of 16" Swiss Stage + "Round of 8" Single-elimination Knockout Stage:
Phase A (Swiss Stage): 16 teams compete. Teams that achieve 3 wins​ advance to the next phase, while teams that accumulate 3 losses​ are eliminated, until 8 qualifying teams are determined.
Phase B (Knockout Stage): The 8 qualified teams proceed through a single-elimination bracket of Quarterfinals → Semifinals → Finals, ultimately deciding the Champion, Runner-up, Top 4, and Top 8.
Key Features & Functionalities
Complete Tournament Simulation: Users can customize the names​ and initial power levels​ of all 16 teams. The simulator automatically determines the outcome of each individual game and match based on a complex set of dynamic power calculation rules (including per-game win bonuses, upset victory bonuses, defense mode, etc.).
Multi-Season Operation: Supports running consecutive seasons. At the end of each season, teams receive permanent power bonuses and honor records based on their final placement (Champion, Runner-up, etc.), and a new season begins automatically.
Comprehensive Data Tracking & Statistics:
Individual Team Data: Tracks each team's real-time power level, match/game win rates, number of upset victories, season/historical highest/lowest power, and more.
Honor System: Cumulatively records the total number of championships, runner-up finishes, top 4 placements, etc., for each team, permanently displayed as star icons (★/☆) in the interface.
Match History: Saves all completed matches with their results, viewable with pagination.
Professional Multi-Panel Interface Layout: The interface is divided into several coordinated panels that display in real-time:
Power Ranking: A list of teams sorted by their current base power.
Schedule Panel: Shows all current round matchups, predicted win rates, and head-to-head history.
Live Match Panel: Details every individual game of the ongoing match, including power composition, bonus breakdown, and results.
Results Panel: Dynamically updates team qualification, elimination status, and final placements for each phase.
Team Data Panel: Displays detailed statistical data for all teams in a table format.
Control Panel: Provides control functions like confirming grouping, starting the next match, proceeding to the next phase, and ending the season.
Core Mechanics
The simulator's core lies in its dynamic power calculation system. Beyond the base power, it incorporates several real-time variables that influence outcomes:
Per-Game Win Bonus: Winning a game grants a bonus to power in the next game.
Upset Victory Bonus: The lower-powered team in an upset win receives a sustained bonus.
Defense Mode: Automatically triggers when a team is down 0:2 in a match, providing a significant initial power bonus that gradually decays over subsequent games, simulating a "comeback" scenario.
End-of-Season Bonuses: After a season concludes, teams permanently increase their base power based on their final placement (Champion, Runner-up, etc.).
In summary, this simulator is not just a visual demonstration of a tournament format; it is a deep simulation application featuring a complex economy system, extensive data statistics, and multi-season progression elements.
