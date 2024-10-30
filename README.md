# Poker_Player_Markowitz

Poker Data Analysis and Player Portfolio Optimization
In this notebook, we will analyze poker hand history data to extract player statistics and construct an optimal portfolio of the top 20 players using Markowitz's portfolio theory. 

Objectives:
Parse poker hand history files to extract relevant data. Calculate key player statistics such as VPIP (Voluntarily Put Money in Pot), PFR (Pre-Flop Raise), Aggression Factor, net winnings, and variance. Identify the top 20 players based on net winnings per hand. Compute the covariance matrix of the net winnings among these top players. Adjust the covariance matrix to ensure it is positive semi-definite. Use portfolio optimization techniques to determine the optimal weights for each player in a portfolio, maximizing expected returns while controlling for risk.

To run:
- Open Notebook on Google Colab and Run All
- If files on server are not working:
1. download preferred data from online source
2. upload to drive
3. Uncomment:
#from google.colab import drive
#drive.mount('/content/drive')
4. Replace all instances of: def download_files_from_columbia_server(file_links, output_directory, n) with def download_files_from_google_drive(file_links, output_directory)


Data Source: 
B, David. “Outflopped.” Obfuscated Datamined Hand Histories - Outflopped, 2009, https://web.archive.org/web/20110205042259/www.outflopped.com/questions/286/obfuscated-datamined-hand-histories 
, 1000 NLP ONG Files
