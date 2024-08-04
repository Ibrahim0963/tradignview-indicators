# tradignview-indicators
Eigene meiner einigen Tradingview-Indikatoren

Die Code oben sind Skripte für TradingView, ide in der "Pine Script-Sprache" geschrieben sind. 

**entry-targets.pine**: Dieses Skript erstellt Linien für Eintrittspreise, Ziel- und Stop-Loss-Preise in einem Trading-Chart und zeigt außerdem Prozentuale Gewinn- oder Verlustangaben an.

**rich-strategy.pine**: A combination of moving averages, Relative Strength Index (RSI), and volume.

**advanced-rich-strategy.pine**: A combination of MA, RSI, MACD, ATR.

**advanced-rich-strategy-2.pine**: A combination of EMAs, RSI, MACD, Bollinger Bands.

**mixed-1-und-2-advanced-strategy.pine**: A combination of advanced-rich-strategy and advanced-rich-strategy-2.


Weitere Skripte werde ich noch bald veröffentlichen :) 

---
# Forex market trading sessions using Germany's time zone
The Forex market trading sessions using Germany's time zone (Central European Time, CET) and Central European Summer Time (CEST) for daylight saving time. Germany operates on CET (UTC+1) during standard time and CEST (UTC+2) during daylight saving time.
- **Sydney Session: (quieter, sets weekly tone):**
   - Sydney Session (Winter): 11:00 PM to 8:00 AM
   - Sydney Session (Summer): 12:00 AM to 9:00 AM
- **Tokyo Session: Asian Session (first major center, JPY focus):**
   - Tokyo Session (Winter): 1:00 AM to 10:00 AM
   - Tokyo Session (Summer): 2:00 AM to 11:00 AM
- **London Session: European Session (high volatility, overlaps Tokyo and New York):**
   - London Session (Winter): 9:00 AM to 6:00 PM
   - London Session (Summer): 10:00 AM to 7:00 PM
- **New York Session: North American Session (major hub, significant impact from US data):**
   - New York Session (Winter): 2:00 PM to 11:00 PM
   - New York Session (Summer): 3:00 PM to 12:00 AM
- **Tokyo-London Overlap:**
   - Tokyo-London Overlap (Winter): 9:00 AM to 10:00 AM
   - Tokyo-London Overlap (Summer): 10:00 AM to 11:00 AM
- **London-New York Overlap:**
   - London-New York Overlap (Winter): 2:00 PM to 6:00 PM
   - London-New York Overlap (Summer): 3:00 PM to 7:00 PM

Bild fürs CEST (Summer Time):
![image](https://github.com/user-attachments/assets/752b2c34-ae26-401c-99ff-9f90a6d22ca0)

Quelle: https://www.ig.com/de/trading-strategien/welche-sind-die-besten-forex-handelszeiten--200130

---

**Trading sessions** and **overlapping sessions** in the Forex market refer to different periods of trading activity and their impacts on market liquidity and volatility. Here’s a clear distinction between the two:

### **1. Trading Sessions**

Trading sessions refer to the main periods when major financial centers are open for trading. Each session is associated with a key financial center and has distinct characteristics:

#### **1.1. Sydney Session**
- **Germany Time (CET/CEST):** 
  - **Winter (CET):** 11:00 PM to 8:00 AM
  - **Summer (CEST):** 12:00 AM to 9:00 AM
- **Characteristics:**
  - The Sydney session is the first to open after the weekend.
  - It generally has lower volatility and trading volume.
  - Significant for the Australian Dollar (AUD) and New Zealand Dollar (NZD) currencies.

#### **1.2. Tokyo Session (Asian Session)**
- **Germany Time (CET/CEST):** 
  - **Winter (CET):** 1:00 AM to 10:00 AM
  - **Summer (CEST):** 2:00 AM to 11:00 AM
- **Characteristics:**
  - The Tokyo session starts after the Sydney session.
  - It sees increased activity and volatility, particularly in JPY and other Asian currencies.
  - Key economic releases from Asia can affect the market.

#### **1.3. London Session (European Session)**
- **Germany Time (CET/CEST):** 
  - **Winter (CET):** 9:00 AM to 6:00 PM
  - **Summer (CEST):** 10:00 AM to 7:00 PM
- **Characteristics:**
  - One of the largest and most important trading sessions.
  - Significant for trading European currencies and for market-moving news from Europe.
  - Overlaps with both the Tokyo and New York sessions.

#### **1.4. New York Session (North American Session)**
- **Germany Time (CET/CEST):** 
  - **Winter (CET):** 2:00 PM to 11:00 PM
  - **Summer (CEST):** 3:00 PM to 12:00 AM
- **Characteristics:**
  - The New York session is the last major session to open.
  - It is crucial for trading USD and for market-moving economic data from the US.
  - Overlaps with the London session.

### **2. Overlapping Sessions**

Overlapping sessions refer to the periods when two major financial centers' trading sessions overlap, leading to increased market activity and volatility:

#### **2.1. Tokyo-London Overlap**
- **Germany Time (CET/CEST):**
  - **Winter (CET):** 9:00 AM to 10:00 AM
  - **Summer (CEST):** 10:00 AM to 11:00 AM
- **Characteristics:**
  - This overlap sees increased trading activity and liquidity as both the Asian and European markets are open.
  - It is a good time for trading currency pairs involving JPY and EUR.
  - Can be a period of increased volatility due to the simultaneous influence of Asian and European market factors.

#### **2.2. London-New York Overlap**
- **Germany Time (CET/CEST):**
  - **Winter (CET):** 2:00 PM to 6:00 PM
  - **Summer (CEST):** 3:00 PM to 7:00 PM
- **Characteristics:**
  - This is the most active period in the Forex market with the highest trading volume and volatility.
  - Both the European and North American markets are open, leading to significant price movements.
  - Ideal for trading major currency pairs involving USD and EUR, as well as for reacting to economic news from both regions.

### **Summary**

- **Trading Sessions:**
  - **Sydney:** 11:00 PM to 8:00 AM CET (12:00 AM to 9:00 AM CEST)
  - **Tokyo:** 1:00 AM to 10:00 AM CET (2:00 AM to 11:00 AM CEST)
  - **London:** 9:00 AM to 6:00 PM CET (10:00 AM to 7:00 PM CEST)
  - **New York:** 2:00 PM to 11:00 PM CET (3:00 PM to 12:00 AM CEST)

- **Overlapping Sessions:**
  - **Tokyo-London:** 9:00 AM to 10:00 AM CET (10:00 AM to 11:00 AM CEST)
  - **London-New York:** 2:00 PM to 6:00 PM CET (3:00 PM to 7:00 PM CEST)

Understanding these sessions and their overlaps helps traders optimize their strategies based on market activity and liquidity.

---

# Trading terminology
   - **Spread:** The difference between the bid price and the ask price.
   - **Volatility:** The degree of variation in an asset’s price over time. Higher volatility indicates larger price swings.
   - **Moving Average:** A statistical calculation used to smooth out price data to identify trends. Common types are the Simple Moving Average (SMA) and Exponential Moving Average (EMA).
   - 
2. **Order Types:**
   - **Market Order:** An order to buy or sell an asset immediately at the current market price.
   - **Limit Order:** An order to buy or sell an asset at a specific price or better. A buy limit order is executed at the limit price or lower, and a sell limit order is executed at the limit price or higher.
   - **Stop-Loss Order:** An order to sell an asset when its price falls to a certain level to limit losses.
   - **Take-Profit Order:** An order to sell an asset when its price reaches a specified level to lock in profits.
   - **Stop-Limit Order:** An order that combines a stop order and a limit order. It becomes a limit order once the stop price is reached.


# Different types of markets
## 1. **Stocks**
   - **What are Stocks:** Stocks represent ownership in a company. When you buy a stock, you own a part of that company.
   - **Key Factors:**
     - **Company Performance:** Financial health, earnings reports, management quality, and growth prospects.
     - **Economic Indicators:** Interest rates, inflation, GDP growth, and employment data.
     - **Market Sentiment:** Investor perception and confidence in the market or specific sectors.
     - **News and Events:** Product launches, mergers and acquisitions, regulatory changes, and geopolitical events.

## 2. **Forex (Foreign Exchange)**
   - **What is Forex:** The forex market involves trading currencies. It’s the largest and most liquid market in the world.
   - **Key Factors:**
     - **Economic Indicators:** Interest rates, inflation, employment figures, and GDP data from different countries.
     - **Central Bank Policies:** Decisions on interest rates and monetary policy from central banks like the Federal Reserve, European Central Bank, and Bank of Japan.
     - **Political Stability:** Political events, elections, and government stability can affect currency values.
     - **Market Sentiment:** Risk appetite, geopolitical tensions, and overall market sentiment.

## 3. **Cryptocurrencies**
   - **What are Cryptocurrencies:** Digital or virtual currencies that use cryptography for security. The most well-known is Bitcoin.
   - **Key Factors:**
     - **Technological Developments:** Updates and advancements in blockchain technology, security improvements, and scalability solutions.
     - **Regulation:** Government regulations, legal status, and regulatory news can significantly impact prices.
     - **Market Sentiment:** Public perception, media coverage, and hype can drive price movements.
     - **Adoption:** The level of acceptance and usage of cryptocurrencies in real-world transactions and by institutions.

## 4. **Commodities**
   - **What are Commodities:** Physical goods like gold, silver, oil, natural gas, agricultural products, and more.
   - **Key Factors:**
     - **Supply and Demand:** Production levels, weather conditions, geopolitical events, and changes in consumption patterns.
     - **Economic Indicators:** Inflation rates, industrial output, and overall economic growth.
     - **Currency Values:** Commodity prices are often inversely related to the value of the US dollar.
     - **Market Sentiment:** Investor perception and speculative activities.

# How to learn:
1. **Technical Analysis:**
   - **Chart Patterns:** Learn to recognize chart patterns and trends specific to the market. Recognize patterns like head and shoulders, flags, and triangles
   - **Indicators:** Use technical indicators to analyze market movements. Use indicators such as moving averages, MACD, RSI, and Bollinger Bands to analyze price movements.

2. **Fundamental Analysis:**
   - **Company Financials:** For stocks, analyze financial statements, earnings reports, and business models.
   - **Economic Data:** For forex and commodities, monitor economic data releases and central bank announcements.
   - **Technological Updates:** For cryptocurrencies, stay updated on technological advancements and regulatory news.

3. **Practice:**
   - **Paper Trading:** Use paper trading accounts to practice trading without risking real money.
   - **Demo Accounts:** Many brokers offer demo accounts where you can trade with virtual money.

4. **Risk Management:**
   - **Position Sizing:** Determine how much of your capital to risk on a single trade.
   - **Stop-Loss Orders:** Use stop-loss orders to limit potential losses on a trade.
   - **Diversification:** Spread your investments across different assets to reduce risk.

5. **Trading Plan:**
   - **Set Goals:** Define clear, realistic objectives for your trading activities.
   - **Develop Strategies:** Create and test trading strategies that suit your goals and risk tolerance.
   - **Discipline:** Stick to your trading plan and avoid emotional decisions.
   - **Trading Style:** Choose a trading style (scalping, day trading, swing trading, position trading).

6. **Emotional Control:**
   - **Avoid Overtrading:** Don’t trade too frequently or impulsively.
   - **Manage Emotions:** Stay calm and composed, especially during market volatility. Avoid letting fear or greed dictate your trades.

7. **Patience and Realistic Expectations:**
   - **Long-Term Perspective:** Focus on long-term growth rather than quick profits.
   - **Accept Losses:** Understand that losses are part of trading, and focus on maintaining a positive overall performance.

# Practical Example:
Let’s say you are interested in trading stocks:
- **Understand Company Performance:** Study the financial health of companies. Look at their earnings reports, revenue growth, and profit margins.
- **Monitor Economic Indicators:** Keep an eye on interest rates, inflation, and GDP growth, as these can impact the stock market.
- **Follow News and Events:** Pay attention to news about product launches, mergers, and industry trends.
- **Analyze Market Sentiment:** Gauge investor sentiment through market surveys, sentiment indicators, and social media trends.

By thoroughly understanding the specific market you are trading in, you can make more informed decisions and develop strategies that are tailored to the unique characteristics of that market.

---
Trading Plattforms to pratice: 
- Trading View
- Meta5
- ig.com

---
# Different types of indicators
TradingView is a popular charting and trading platform that offers a wide array of tools for technical analysis, including indicators. Indicators on TradingView help traders analyze price movements, identify trends, and make informed trading decisions. Here’s an overview of the types of indicators available on TradingView and their purposes:

## 1. **Trend Indicators**
   - **Moving Averages (MA):** A line that shows the average price over a certain number of days. Common types include Simple Moving Average (SMA) and Exponential Moving Average (EMA). It helps to see the overall direction of the market. If the line is going up, the market is generally going up, and if it's going down, the market is generally going down.
   - **Moving Average Convergence Divergence (MACD):** shows the difference between two moving averages. It helps to identify changes in the market trend. When the MACD line crosses above the signal line, it might be a good time to buy. When it crosses below, it might be a good time to sell.
   - **Average Directional Index (ADX):** This measures the strength of a trend but not the direction. It helps traders determine whether the market is trending or ranging.

## 2. **Momentum Indicators**
   - **Relative Strength Index (RSI):** A number between 0 and 100 that shows if something is overbought (too high) or oversold (too low). If RSI is above 70, it might be overbought (too high and might go down). If RSI is below 30, it might be oversold (too low and might go up).
   - **Stochastic Oscillator:** compares the current price to the price range over a recent period. If the value is above 80, the market might be overbought (too high). If it's below 20, the market might be oversold (too low).
   - **Rate of Change (ROC):** This measures the percentage change between the current price and the price a certain number of periods ago.

## 3. **Volatility Indicators**
   - **Bollinger Bands:** Two lines that form a band around the price line based on volatility. If the price touches the upper band, it might be too high and could come down. If it touches the lower band, it might be too low and could go up.
   - **Average True Range (ATR):**  measure of how much the price moves on average during a given time period.It helps to understand market volatility. High ATR means the market is more volatile, while low ATR means the market is less volatile.

## 4. **Volume Indicators**
   - **On-Balance Volume (OBV):** This uses volume flow to predict changes in stock price. It’s calculated by adding volume on up days and subtracting it on down days. If OBV is going up, it might mean more people are buying. If OBV is going down, it might mean more people are selling.
   - **Volume Moving Average (VMA):** This is the average volume over a specified period, helping to smooth out volume data.

## 5. **Support and Resistance Indicators**
   - **Pivot Points:** Key price levels calculated from the previous day's prices.These levels can act as support (price stops going down) or resistance (price stops going up).
   - **Fibonacci Retracement:** Lines that indicate where the price might find support or resistance based on Fibonacci ratios. Use these lines to predict where the price might reverse direction.

## 6. **Custom Indicators**
   - **Pine Script:** TradingView allows users to create custom indicators using Pine Script, a lightweight scripting language. This enables traders to tailor indicators to their specific needs and strategies.

--- 
# Strategies:
- **Using RSI with Bollinger Bands:**
  - Add both RSI and Bollinger Bands to a chart.
  - When the RSI is above 70 and the price touches the upper Bollinger Band, it might indicate overbought conditions and a potential reversal.
  - Conversely, when the RSI is below 30 and the price touches the lower Bollinger Band, it might indicate oversold conditions and a potential buying opportunity.

## 1. **Moving Averages and MACD**
   - **Setup:**
     - Add a 50-period Simple Moving Average (SMA) and a 200-period SMA.
     - Add the MACD indicator.
   - **How to Use:**
     - **Golden Cross:** When the 50-SMA crosses above the 200-SMA, it’s a bullish signal (potential buy).
     - **Death Cross:** When the 50-SMA crosses below the 200-SMA, it’s a bearish signal (potential sell).
     - Use MACD to confirm the trend direction. For instance, if there’s a Golden Cross and the MACD line is above the signal line, it strengthens the buy signal.

## 2. **RSI and Bollinger Bands**
   - **Setup:**
     - Add the RSI indicator with default settings (14-period).
     - Add Bollinger Bands with default settings (20-period SMA and 2 standard deviations).
   - **How to Use:**
     - **Overbought Condition:** If RSI is above 70 and the price is near or above the upper Bollinger Band, it may indicate an overbought condition (potential sell).
     - **Oversold Condition:** If RSI is below 30 and the price is near or below the lower Bollinger Band, it may indicate an oversold condition (potential buy).

## 3. **Stochastic Oscillator and Support/Resistance Levels**
   - **Setup:**
     - Add the Stochastic Oscillator with default settings.
     - Identify key support and resistance levels on the chart.
   - **How to Use:**
     - When the Stochastic Oscillator is above 80 (overbought) and the price is near a resistance level, it may signal a potential sell.
     - When the Stochastic Oscillator is below 20 (oversold) and the price is near a support level, it may signal a potential buy.

## 4. **ATR and Breakouts**
   - **Setup:**
     - Add the ATR (Average True Range) indicator with default settings.
   - **How to Use:**
     - Use ATR to gauge the volatility. High ATR values indicate high volatility, while low ATR values indicate low volatility.
     - For breakout trades, wait for the price to move significantly above or below a support/resistance level with a rising ATR. This suggests a strong move backed by increased volatility.

## 5. **OBV and Price Divergence**
   - **Setup:**
     - Add the On-Balance Volume (OBV) indicator.
   - **How to Use:**
     - Look for divergences between the OBV and price. If the price is making new highs but the OBV is not, it may indicate a potential reversal or weakening trend (potential sell).
     - Conversely, if the price is making new lows but the OBV is not, it may indicate a potential reversal or strengthening trend (potential buy).

## 6. **Pivot Points and Fibonacci Retracement**
   - **Setup:**
     - Add Pivot Points (set to daily for day trading or weekly for swing trading).
     - Add Fibonacci Retracement levels from a significant high to a significant low.
   - **How to Use:**
     - Use Pivot Points as potential support and resistance levels. If the price breaks above a pivot point, it may indicate a continuation of the trend (potential buy). If it breaks below, it may indicate a reversal (potential sell).
     - Use Fibonacci Retracement levels to find potential support and resistance. For example, a 61.8% retracement level often acts as a strong support or resistance. Look for price action signals (like candlestick patterns) at these levels to confirm the trade.

## 7. **Combination of Indicators for a Comprehensive Strategy**
   - **Setup:**
     - Add a 20-period EMA (Exponential Moving Average).
     - Add RSI.
     - Add Bollinger Bands.
   - **How to Use:**
     - **Buy Signal:**
       - The price crosses above the 20-EMA.
       - RSI is above 50 but below 70.
       - The price is near the lower Bollinger Band or just bounced off it.
     - **Sell Signal:**
       - The price crosses below the 20-EMA.
       - RSI is below 50 but above 30.
       - The price is near the upper Bollinger Band or just bounced off it.

## Practical Example Summary:
- **Using Moving Averages and MACD:** Look for Golden Cross/Death Cross for trend direction and use MACD for confirmation.
- **Using RSI and Bollinger Bands:** Identify overbought/oversold conditions.
- **Using Stochastic Oscillator and Support/Resistance:** Combine overbought/oversold conditions with key price levels.
- **Using ATR for Breakouts:** Monitor ATR for volatility to confirm breakouts.
- **Using OBV for Divergence:** Spot divergences between OBV and price for potential reversals.
- **Using Pivot Points and Fibonacci Retracement:** Identify key support/resistance levels and confirm with price action.

By combining these indicators and setups, traders can develop robust strategies tailored to different market conditions.
