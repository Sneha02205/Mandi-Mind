# MandiMind: AI-Powered Price Prediction for Farmers

## 1. Problem Statement

Farmers in India often sell their crops at suboptimal prices because they lack access to crucial market information. They typically only know the current day's price in their local mandi and have no visibility into future price trends or prices in other nearby markets. This information gap leads to significant profit losses, estimated at 30-50%, as they might sell too early or in a less profitable market.

### Why This Matters

- **Vulnerability of Small Farmers:** With 80% of Indian farmers being small or marginal, they are highly sensitive to price fluctuations.
- **Lack of Bargaining Power:** Without market data, farmers have little to no leverage against middlemen.
- **Income Instability:** Unpredictable income contributes to financial distress and debt in rural communities.

## 2. The Solution: MandiMind

MandiMind is a web application designed to empower farmers with actionable market intelligence. By providing data-driven insights, it helps them decide **when** and **where** to sell their crops to maximize their profits.

### Core Features

1.  **Crop & Location Input:** A simple interface for farmers to select their crop and current location.
2.  **AI-Powered Price Forecasting:** The backend uses a machine learning model to predict future prices for the selected crop.
3.  **Multi-Mandi Comparison:** The system fetches and compares prices from multiple nearby mandis.
4.  **Net Profit Calculation:** It automatically calculates the estimated net profit after factoring in transportation costs.
5.  **Clear & Simple Recommendation:** The application provides a straightforward recommendation:
    - **✅ SELL NOW:** If current prices are optimal, it highlights the best mandi to sell at.
    - **⏳ WAIT:** If the forecast predicts a price increase, it shows the potential profit gain from waiting.

## 3. Demo Flow

A user visiting the site will experience the following:

1.  **Choose Crop & Location:** The farmer selects a crop (e.g., "Tomato") and their location.
2.  **Get Prediction:** The system processes the request.
3.  **View Results:** The application displays:
    - The predicted price trend for the upcoming days.
    - The best mandi to sell at **today**.
    - A clear calculation of the net profit difference (e.g., "Wait 3 days for a potential +₹350/quintal profit").
4.  **Receive Actionable Advice:** A final, clear message: **SELL NOW** or **WAIT**.

## 4. Tech Stack

-   **Frontend:** HTML, CSS, JavaScript
-   **Backend:** Flask for the API and to serve the ML model.
-   **Machine Learning:** Random Forest for price prediction and handling nonlinear data well.
