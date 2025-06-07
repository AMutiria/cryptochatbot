CryptoAdvisor Chatbot
Created by Group 60 
Project Overview
Welcome to CryptoAdvisor! This is a simple Python-based chatbot designed to provide basic information and recommendations on cryptocurrencies, focusing on profitability and sustainability aspects. It uses a predefined dataset to answer queries about trending, eco-friendly, and profitable digital currencies.

Features
Crypto Data: Contains a small, predefined dataset of cryptocurrencies (Bitcoin, Ethereum, Cardano) with attributes like price trend, market cap, energy use, and sustainability scores.

Eco-Friendly Crypto: Lists several cryptocurrencies known for their lower environmental impact, along with brief descriptions.

Trending Crypto: Identifies cryptocurrencies with a "rising" price trend.

Most Sustainable Crypto: Recommends the cryptocurrency with the highest sustainability score in the dataset.

Profitable Crypto: Suggests a cryptocurrency that is both "rising" in price and has a "high" market capitalization.

Interactive Chatbot: Allows users to query the bot for information.

Deliverables Breakdown
The provided code combines several "deliverables":

DELIVERABLE 1 (crypto_advisor function): Sets up the initial crypto_db (predefined dataset) and displays a welcome message.

DELIVERABLE 2 (get_eco_friendly_crypto function): Provides a separate list of eco-friendly cryptocurrencies with explanations.

DELIVERABLE 3 & 4 (Functions get_trending_crypto, get_most_sustainable, get_profitable, and chatbot): Implement the core logic for fetching and recommending cryptocurrencies based on user queries, and manage the main interactive chat loop.

How to Run the Chatbot
To run this chatbot, you'll need Python installed on your system.

Save the code: Save the provided Python code into a file named crypto_chatbot.py (or any other .py extension).

Open a terminal/command prompt: Navigate to the directory where you saved the file.

cd C:\Users\Ashley\OneDrive\Desktop\python nav\Group chatbot

Run the script: Execute the Python script using the command:

python crypto_chatbot.py

How to Use the Chatbot
Once the chatbot is running, you'll see a welcome message. You can then type your queries.

Sample Queries you can try:

Trending Crypto Queries:

Which crypto is trending up?

What coins are trending?

Show me trending cryptos.

Which cryptocurrencies are going up?

Sustainability Queries:

What’s the most sustainable coin?

Which crypto is eco-friendly?

Recommend a sustainable cryptocurrency.

Which coin is best for the environment?

Profitability Queries:

Which crypto is most profitable?

What is the best coin to invest in?

Which crypto has the best profit?

Recommend a profitable cryptocurrency.

Exit Queries:

exit

quit

Unrecognized Query Example:

Tell me a joke. (The bot will respond that it didn't understand.)

Limitations
The chatbot uses a predefined, static dataset. It does not fetch real-time market data.

The recommendations are based solely on the hardcoded attributes.

It has limited natural language understanding and relies on keyword matching for queries.

