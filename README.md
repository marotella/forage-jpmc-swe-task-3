# JPMC Task 3

# Description:

This task was through Forage, which works with companies to design virutal internship experiences. This specific task is one of three tasks for JPMorgan Chase. This task helped me to learn how traders use a trading dashboard for trading analysis and stock price monitoring


# Goals:

The task required me to work with JPMorgan's Perspective in order to to generate a live graph that displays a data feed. This data feed would be used by traders to monitor stock prices.

I needed to debug and adjust code so that live data would be appropriately aggregated and display the highest leverage data points in real time for users.


# Purpose
You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor.

Recall that the purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12-month historical average ratio.

# Acceptance Criteria

This ticket is done when the numbers from the python script render properly in the live perspective graph. That means the ratio between the two stock prices is tracked and displayed, the upper and lower bounds are shown on the graph, and an alert is shown whenever the bounds are crossed.

# Technologies used:
- Python
- React
- Perspective
