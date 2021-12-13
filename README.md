# TraderDash
Portfolio Management and Algotrading Dashboard

Demo Video: https://www.youtube.com/watch?v=LJqdIFPlqe8
![image](https://user-images.githubusercontent.com/83811972/145789560-d0e63bca-36a9-4660-b205-d6cd0cfe81b4.png)

# Executive Summary
Our project’s objective was to design and develop an intelligent trading platform leveraging the fundamentals of investment, data visualisation and automation. We developed our prototype to solve the pain points of our selected target segment, and planned our product development in three phases : Design, Development & Test, and Deployment. 

Our target segment, who are retail traders, are still learning and sharpening their trading and investment knowledge and quantitative skills. They have heard about algorithmic trading (algo-trading) and are interested to find out more before diving into it. As such, they still want to retain control of their trading strategies but are open to learn and compare algo-trading strategies against their own manual trading strategies. They recognise the strengths in adopting algo-trading such as speed and removal of emotions in trading but they have yet to be comfortable in relinquishing control to the algorithm. 

# Phase 1: Design Thinking
In our design phase, we took an empathetic view during our users interviews to understand the issues and challenges faced by them.
From our interviews, we then charted out an empathy map and developed a persona called “Active Amos”. We created a customer journey and proceeded with an iterative process of design-and-test. The prototype that we built on Figma was shared with our users several times, to get valuable feedback for us to improve the overall experience and design. 

As we developed the features, we also ensured that our platform was viable in the market. We did extensive product research and compatibility to see where the USP of our product lies. 

# Phase 2: Development & Test
To develop trading algorithms, Python libraries like vectorbt and fastquant were used to run the backtesting and optimize the strategy respectively. All the strategies were backtested using at least 2 years of historical data to train and optimise the strategy. We then run the backtest result for each strategy per stock in the user's watchlist with a capital of $1,000 for the last 90 days. These results are then illustrated as individual strategy-stock ideas in our Opportunities and Backtesting page. 

We also adopted Modern Portfolio Theory to find the maximum risk adjusted returns (measured by Sharpe Ratio) and lowest risk (measured by standard deviation) in the portfolio with the optimal mix of weights for respective shares to achieve these two objectives. This is illustrated as recommended weights and an efficient frontier graph in our Portfolio-Test Rebalancing page.

At this stage, we focused on trading equities as it is the financial instrument of choice that our target segment is most interested in. We plan to expand to other types of assets in our future development phase.

# Phase 3: Deployment
To make TraderDash functional, we integrated portfolio visualisation, dashboard and reports using Power BI combined with a library of algo-trading strategies available for our users. Our platform applies this library of algo-trading strategies to the stocks in the users’ watchlists and open portfolio stocks, and recommends the best strategy-stock idea for the user to take action.

Our prototype is connected to API sources, news and public data to provide timely and summarized information needed for users to take timely action. It offers recommended weights of assets in the portfolio to meet the users’ required needs.

Our product is currently available on Power BI, with plans to make it available on web interface and mobile application so that it can be easily accessible to users.

