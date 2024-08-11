# Welcome to your GPT Engineer project

## Project info

**Project**: trade-sculptor 

**URL**: https://run.gptengineer.app/projects/dbaf5b90-04dc-4e55-b19b-b45772b6da93/improve

**Description**: I have a gaming laptop with DDR4 64GB RAM and an 8GB RTX 3050 Ti GPU, and I'm looking to develop a Python-based desktop application that connects to an MQL4 script for trading EUR/USD with spreads ranging from 0.0 to 0.7 pips. My goal is to leverage the laptop's hardware to reduce latency and increase trade execution speed, while also incorporating a market maker strategy, deep learning, and machine learning.

The core of the application should include:

Market Maker Strategy:

The app should implement a market maker strategy, handling features such as Trailing Stop, Martingale, Dynamic Lot Sizing, and time-restricted trading.
It should execute frequent trades (high-frequency trading, HFT) with a focus on smaller profit margins per trade.
Deep Learning Integration:

Utilize deep learning models trained on CSV data to make trading decisions.
The deep learning component should continuously analyze market conditions and optimize trade entries and exits to align with the market maker strategy.
High-Frequency Trading (HFT) Optimization:

The strategy should focus on executing a large number of small, profitable trades, leveraging the market maker approach.
Machine Learning for Continuous Improvement:

Implement a machine learning system that improves the trading strategy over time. The more trades the bot executes, the more it learns and optimizes future trades.
Use reinforcement learning or similar techniques to reward profitable strategies and refine trade decision-making as the model processes more data.
User Interface (UI) Design:

A dashboard that displays real-time metrics (account balance, open trades, profit/loss, and market data).
Allow manual trade control, settings adjustments, and money management through the UI.
Include real-time performance monitoring (win rate, average trade duration, drawdown).
Testing and Optimization:

Backtest the strategy using historical data and optimize parameters using MT4 tools.
Forward test the strategy in a demo account to validate live market performance.
Enable continuous learning for the machine learning model to improve as more trade data is collected.
Risk Management:

Diversify trading across different currency pairs or instruments.
Implement strict drawdown limits and reduce lot sizes or pause trading when necessary.
Connecting the Desktop Application to MT4:

The application should connect to MT4 using Python, leveraging the MetaTrader 4 (MT4) API or MetaTrader Python libraries.
The most efficient and easy way to establish communication is by using network sockets, where the MQL4 script sends and receives data to and from the Python application in real-time. This setup allows for minimal latency and seamless data exchange between the Python app and MT4.
Ensure the connection is robust and supports real-time data flow, allowing the application to make and execute trade decisions quickly. 

## Who is the owner of this repository?
By default, GPT Engineer projects are created with public GitHub repositories.

However, you can easily transfer the repository to your own GitHub account by navigating to your [GPT Engineer project](https://run.gptengineer.app/projects/dbaf5b90-04dc-4e55-b19b-b45772b6da93/improve) and selecting Settings -> GitHub. 

## How can I edit this code?
There are several ways of editing your application.

**Use GPT Engineer**

Simply visit the GPT Engineer project at [GPT Engineer](https://run.gptengineer.app/projects/dbaf5b90-04dc-4e55-b19b-b45772b6da93/improve) and start prompting.

Changes made via gptengineer.app will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in the GPT Engineer UI.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps: 

```sh
git clone https://github.com/GPT-Engineer-App/trade-sculptor.git
cd trade-sculptor
npm i

# This will run a dev server with auto reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with .

- Vite
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

All GPT Engineer projects can be deployed directly via the GPT Engineer app. 

Simply visit your project at [GPT Engineer](https://run.gptengineer.app/projects/dbaf5b90-04dc-4e55-b19b-b45772b6da93/improve) and click on Share -> Publish.

## I want to use a custom domain - is that possible?

We don't support custom domains (yet). If you want to deploy your project under your own domain, then we recommend GitHub Pages.

To use GitHub Pages you will need to follow these steps: 
- Deploy your project using GitHub Pages - instructions [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site)
- Configure a custom domain for your GitHub Pages site - instructions [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)