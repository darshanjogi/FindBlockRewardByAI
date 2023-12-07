# FindBlockRewardByAI  📊

Overview
The Ethereum Block Reward Predictor is a project that combines a Node.js server (Server.js) and a machine learning script (ml.py) to fetch, process, and predict future Ethereum block rewards. It provides a streamlined way to gather historical block reward data and leverage machine learning to forecast potential rewards.


## How it Works 🛠️

Node.js Server (Server.js):

Fetches Ethereum block reward data from Etherscan API.
Processes the data and exports it to a CSV file (block_data.csv).
Runs- node server.js 

Machine Learning Script (ml.py):

Reads block_data.csv and loads it into a Pandas DataFrame.
Visualizes the data with a scatter plot.
Trains a Random Forest Regressor to predict future block rewards.
Outputs the predicted block reward for a given timestamp.

Output - 
<img width="1110" alt="image" src="https://github.com/darshanjogi/FindBlockRewardByAI/assets/64300256/6e27177a-99cc-477e-b64f-4908011f2197">





