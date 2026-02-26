# zoho-cliq-zerodha-kite-extension
Why a Zerodha Integration for Zoho Cliq Matters Today (AI-Powered Kite Integration)
In a fast-paced work environment, many professionals also keep an eye on the stock market — checking prices, tracking positions, and monitoring alerts.
 This usually requires switching to the Zerodha Kite app or opening a separate browser, which interrupts workflow and causes productivity loss.
Stockers solves this by bringing essential trading utilities directly inside Zoho Cliq — where users already spend most of their workday.

DOCUMENTATION: https://workdrive.zohoexternal.com/file/7tqdd1b60c7bf3c2d457995c460018147ce8e 
TUTORIAL VIDEO : https://workdrive.zohoexternal.com/file/7tqdda94a5ee0eaa34f1282c7224d5a7ef3df
DOWNLOAD LINK : https://cliq.zoho.com/installapp.do?id=7419 

🚀 Why Our Integration Is Needed
1️⃣ No More Switching Apps for Stock Tracking
Users usually open Kite multiple times a day just to:
1.	Check stock prices

2.	Monitor holdings and positions

3.	See if target is hit

Stockers brings all these actions inside chat:
✔ Stay focused
 ✔ No new tabs
 ✔ No workflow interruptions


2️⃣ Portfolio Visibility Right Inside Cliq
Users can check:
1.	Current holdings

2.	Positions

3.	P&L overview

4.	Live price summary

All through simple chat commands like:
  1	current stocks
  2	price tcs

➡ This gives instant access to essential investment information while working.


3️⃣ Smart Price Alerts Without Manual Monitoring
Users often worry:
“Did the stock reach my target?”
 “Did I miss the movement?”
Stockers allows them to set alerts directly:
1	alert set reliance 2600

🕒 Automatically monitored
 🔔 Alert sent at 3:25 PM if target reached
 ✔ No need to sit and watch charts


4️⃣ Quick Market News Updates
Instead of browsing multiple websites:
1	news

➡ Shows latest business and finance headlines
Keeps users aware of what may affect their stocks.


5️⃣ Simple, Chat-Based Experience
Employees already use Cliq daily for:
1.	Messaging

2.	Meetings & updates

3.	Team discussions

Stockers turns it into a smart workspace with:
✔ Real-time stock queries
 ✔ Alerts
 ✔ Portfolio view
 ✔ News feed
All with zero distraction.


🧩 Perfect Fit for Modern Teams
Stockers enhances how professionals:
Need	Stockers Response
Quick market glance	Fast chat commands
Accountability with holdings	Portfolio in chat
Time-sensitive actions	Alerts
Reliable news	Aggregated business headlines
It becomes a financial companion inside a work productivity platform.




🎯 Final Conclusion
Stockers isn’t just a convenience tool —
 it removes friction in how users interact with stock markets during work.
It:
✔ Reduces context switching
 ✔ Saves time
 ✔ Enables faster decisions
 ✔ Helps employees stay productive while staying informed
For users who monitor markets daily,
 Stockers becomes an essential part of their workflow.




 


Stockers – AI + Automation for Smarter Zerodha Trading (ZOHO CLIQ)
1. Executive Summary
Stockers Bot is an advanced trading automation and financial intelligence assistant designed to operate natively within Zoho Cliq. It seamlessly integrates with Zerodha's trading APIs to provide users with real-time market data, portfolio monitoring, AI-driven stock analysis, and automated price alerts, all accessible through simple chat commands.
The core value proposition is eliminating the need for context switching by embedding complex financial tools directly into the user's communication platform.
2. How to Use Stockers Bot — User Guide
SAMPLE PPT : https://workdrive.zohoexternal.com/file/7tqdd1b60c7bf3c2d457995c460018147ce8e
TUTORIAL VIDEO : https://workdrive.zohoexternal.com/file/7tqdda94a5ee0eaa34f1282c7224d5a7ef3df
Step 1️⃣ — Connect Zerodha

![302f679e-85e8-4e37-ae84-e100510dd3a3](https://github.com/user-attachments/assets/88043fc1-3d18-468e-a01a-d9484bb09796)

![7cd5a48f-1dcf-46b2-a778-eb29a15d9efa](https://github.com/user-attachments/assets/b1dddb4d-080e-4960-8635-d4967df9df52)




To link your trading account, you need to provide your API credentials securely.
Action	Description
Command	Type the slash command: /connectZerodha
Form	A secure form will appear in the chat.
Input	Enter your Zerodha API Key & API Secret.
Confirmation	Submit the form and wait for the bot's confirmation message.
Step 2️⃣ — Generate Access Token






![3d2505ab-ce34-49c2-a94f-144ae072bfc6](https://github.com/user-attachments/assets/077bb410-a7ba-4b31-bcfb-1ad87011d430)







The Access Token is required for all transactional and real-time data lookups.
Action	Description
Command	Type the slash command: /accessToken
Process	The bot will send a Kite login link.
Login	Log in with your Zerodha credentials via the link.
Result	The access token will be automatically generated and stored securely for use.

📌 Note: The access token is typically short-lived and must be refreshed daily to ensure continuous operation.
Step 3️⃣ — Check Token Status Anytime
Action	Description
Command	Type the slash command: /showToken
Result	The bot will display the status or the masked token value.
🎯 Main Commands to Use the Bot
Once connected, use these message commands for daily trading and market intelligence.
Function	Command	Example
Get stock price	price <symbol>	price tcs
AI Stock Analysis	ai analyse <symbol>	ai analyse infy
Show your portfolio	current stocks	N/A
Latest market news	news	N/A
🔔 Alerts & Targets
Action	Command	Example
Create price alert	alert set <symbol> <price>	alert set reliance 2600
Remove alerts	alert remove <symbol>	alert remove tcs
Instant target check	target <symbol> <price>	target hdfcbank 1500
💡 Bonus Tips
4.	✔ Multiple price alerts are allowed per stock.
5.	✔ A daily reminder will notify you if your access token is expired or nearing expiry.
6.	✔ Alerts fire automatically at 3:25 PM daily if the target price has been reached.
7.	✔ The visual Widget UI (stock_kite) opens automatically for data-heavy commands (e.g., news, current stocks, ai analyse).
3. Features and User Commands
The bot supports two types of interactions: conversational Message Commands for data retrieval, and secure Slash Commands for authentication and management.



![62696540-8165-4db8-9c40-070e6ae2511b](https://github.com/user-attachments/assets/c78e1f7e-316c-4f35-996e-42e39559e08e)



3.1. Message Commands (Conversational)
These commands trigger immediate data lookups and set up monitoring tasks.
Command	Description	Supported Symbols
current stocks	Displays the user's real-time portfolio, including holdings and open positions.	N/A
news	Fetches the latest business and financial news updates relevant to the market.	N/A
price <symbol>	Retrieves the live, real-time price quotation for a specified stock symbol.	e.g., tcs, infy, reliance
ai analyse <symbol>	Provides AI-based insights, trend prediction, and sentiment analysis for the stock.	e.g., hdfcbank
alert set <symbol> <price>	Creates a scheduled notification that triggers when the stock hits the target price. Multiple alerts are supported.	e.g., tcs 3500
alert remove <symbol>	Deletes all active price alerts associated with the specified stock symbol.	e.g., reliance
target <symbol> <price>	Performs an immediate, one-time check to see if the stock's current price has hit the specified target.	e.g., infy 1400
3.2. Slash Commands (Advanced Management)
These commands are used for secure setup and managing the connection to the Zerodha API.
Slash Command	Function	Description
/connectZerodha	API Credential Input	Prompts the user to securely enter their Zerodha API Key and API Secret via a structured input form.
/accessToken	Token Generation	Initiates the process to convert the Zerodha request_token into the long-lived access_token required for trading operations.
/showToken	Token Display	Displays the currently active access token to the user, ensuring the sensitive secret is always masked.
4. System Architecture and Components
Stockers Bot operates on a modular architecture, integrating the Zoho Cliq environment with external financial APIs and persistent storage.
4.1. Internal Functions
Core utility functions responsible for secure credential management and API workflow.
Function	Purpose	Security Notes
saveZerodhaCreds()	Stores the Zerodha API Key and API Secret in the system's database.	API Secret is never echoed or shown back to the user.
convertToken()	Executes the necessary API call to transform the temporary request_token (obtained during the login flow) into the persistent access_token.	The generated access_token is stored securely for use in subsequent Zerodha API calls.
4.2. Background Schedulers

Automated processes ensure the bot remains functional and delivers timely, proactive notifications.
Scheduler	What it Does	Execution Frequency	Rationale
access_token_alert	Reminds users that their Zerodha access token may be expiring and needs refreshing.	Daily	Ensures uninterrupted trading and data access.
stock_price_alert_checker	Compares the live price of all stocks in the stock_alerts table against their target prices.	3:25 PM Daily	Triggers sharp, real-time alert notifications before the market closes.
4.3. Database Schema
All user-defined price alerts are stored in the following database table, allowing for persistent monitoring and multi-alert functionality.
Table: stock_alerts
Field	Data Type	Purpose	Notes
user_id	String	Unique identifier for the Zoho Cliq user.	Used to direct alerts to the correct chat.
stock_name	String	The stock symbol being monitored (e.g., tcs).	
target_price	Numeric	The trigger price value.	Multiple records are allowed for the same stock symbol per user.
5. Zoho Cliq Widget: stock_kite
The stock_kite widget is an integrated dashboard that provides a rich visual experience, automatically opening upon execution of related commands (news, current stocks, ai analyse,etc.).
Sections within the Widget:
8.	Latest News: A feed of current business and market news.



![f11df89a-3e14-4107-b7b0-4fb1965005ff](https://github.com/user-attachments/assets/53023eae-b063-4c32-b65a-cff874cdcb51)




9.	My Portfolio: A summary view of the user's holdings and active positions.




![ff40c13c-41ba-41cb-a9c8-d89b7958f5c6](https://github.com/user-attachments/assets/0126eca1-e0ad-41dc-a9c0-bd9f0927ae9a)



10.	Profits: A dedicated section highlighting profitable trades or holdings.




![f06610af-9f63-4464-a9bb-7279eea7116e](https://github.com/user-attachments/assets/f2d41944-61dd-40fb-a491-fe56b0be2b39)





11.	Losses: A dedicated section highlighting losing trades or holdings for quick review.	
	
	
	
![0fe42425-829a-4c07-9737-61df0ddea36f](https://github.com/user-attachments/assets/48c8a129-4f3a-4b76-8dfc-e210f5187497)

	

12.	Analytics (Graph): Visual representation of stock performance


![21025285-a50d-4996-bb3f-db9a0a3feea5](https://github.com/user-attachments/assets/91c8fcb2-54e9-4c59-8505-861dd0e2ae38)



6. Value Proposition
Stokers Bot presents a unique and highly practical application, maximizing the utility of the Zoho Cliq platform.
Feature	Impact
Real Trading Integration	Demonstrates a practical, real-world financial use case with a high barrier to entry.
AI-based Analysis	Leverages modern AI capabilities to provide actionable decision support beyond simple data retrieval.
Automated Alerts (Real-Time)	Proactive scheduling prevents users from missing critical market opportunities or events.
Entirely inside Zoho Cliq	Zero friction and zero switching of tools, defining a superior, native user experience.
Security Handling	Focus on secure storage and masking of API secrets and tokens.


