# AF305_ProgrammingForFinance
An interactive Smart Financial Management System using Python &amp; ipywidgets. This project evaluates loan eligibility and investment risk to assist in financial decision-making.
This project is a dynamic suite of financial tools, built as a Jupyter Notebook for the FAST-NUCES AF3005 Programming for Finance course. It leverages the power of ipywidgets to create an engaging and interactive user experience. Dive in and explore key financial concepts through hands-on simulations and analysis!

🚀 Key Features
1. 🏦 Loan Eligibility Wizard 🏦
Quickly determine loan eligibility based on key factors:

Inputs: Employment Status, Income, Credit Score.

Logic:

Instant rejection for unemployed applicants.

Income threshold: Requires a minimum income of PKR 50,000.

Credit score dictates interest rate tiers (5% or 8%) or rejection.

2. 📊 Investment Risk Compass 📊
Navigate the investment landscape with confidence!

Input: Comma-separated list of stock returns.

Analysis:

High Risk: Identified by any negative returns.

Medium Risk: All positive returns, but each is less than 5%.

Low Risk: All returns are 5% or greater.

3. 🧾 Loan Repayment Navigator 🧾
Stay on top of your loan payments with a clear, interactive schedule!

Inputs: Loan Amount, Monthly Payment.

Output: A detailed month-by-month repayment schedule.

Highlights:

Automatic calculation of the final, potentially partial, payment.

Clear and concise balance tracking.

4. 📈 Stock Price Alert System 📈
Track your stocks and get notified of important price changes!

Input: Comma-separated list of daily stock prices.

Features:

Intelligently skips any None values.

Sends alerts when prices reach or exceed PKR 200.

Provides daily progress tracking.

5. 💱 Currency Exchange Simulator 💱
Simulate currency exchange rate fluctuations and their impact!

Automated Simulation:

Starts with an initial rate of PKR 290/USD.

Increases by 1 PKR per day.

Simulation concludes when the rate reaches PKR 300/USD.
