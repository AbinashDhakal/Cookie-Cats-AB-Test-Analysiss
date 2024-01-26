## Cookie Cats AB-Test Analysis
# Introduction
Cookie Cats is a popular mobile puzzle game developed by Tactile Entertainment, featuring singing cats and a classic "connect three"-style puzzle. This analysis focuses on an AB-test conducted to evaluate the impact of moving the first gate in the game from level 30 to level 40 on player retention.

# Data Overview
The dataset includes information from 90,189 players who installed the game during the AB-test. Key variables include:

userid: A unique identifier for each player.
version: Whether the player was in the control group (gate_30) or the group with the moved gate (gate_40).
sum_gamerounds: The number of game rounds played by the player in the first 14 days after install.
retention_1: Did the player come back and play 1 day after installing?
retention_7: Did the player come back and play 7 days after installing?
AB-Test Analysis
# 1. Distribution of Game Rounds
A histogram was plotted to visualize the distribution of game rounds played during the first week. The analysis showed various player engagement levels, with some players not playing at all, while others played extensively.

# 2. Overall 1-day Retention
The overall 1-day retention for all players was approximately 44.5%, indicating that almost half of the players returned to play the game one day after installation.

# 3. 1-day Retention by AB-group
1-day retention was compared between the two AB-groups. The retention for gate_30 was 44.8%, while for gate_40, it was 44.2%. Although a small difference, bootstrapping analysis suggested a 95.8% probability that 1-day retention is better when the gate is at level 30.

# 4. 7-day Retention by AB-group
Looking at 7-day retention, gate_30 had a rate of 19.0%, and gate_40 had a rate of 18.2%. Bootstrapping analysis indicated a 100% probability that 7-day retention is higher when the gate is at level 30.

# 5. Conclusion
The analysis concludes that there is strong evidence supporting higher retention rates when the gate is at level 30 compared to level 40. Therefore, it is recommended not to move the gate from level 30 to level 40 to maintain high player retention.

# 6. Additional Insights
The theory of hedonic adaptation was briefly discussed as a possible explanation for higher retention at level 30. It suggests that by forcing players to take a break at a gate, their enjoyment of the game is prolonged.

Decision
Given the data and bootstrap analysis results, the recommendation is not to move the gate from level 30 to level 40.
