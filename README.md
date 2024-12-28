# Multi-Asset-Price-Change-Tracker
Multi Asset Price Change Tracker
This script displays daily price changes for three assets (US100, US30, and US500) during the trading period from 18:00 (UTC-5) to 18:00 the following day. The data is presented in a clear and concise table format, including:

Asset Name
Price Change (Points)
Price Change (%)

This tool is ideal for tracking daily market performance directly on the chart in an organized table format. Calculations are based on the difference between the current price and the previous day's closing price.

Features:

Supports multiple assets.
Displays changes in both points and percentages.
Adapts to the start time of the new day (18:00 UTC-5).
Usage:
Add this script to your chart to monitor daily price changes for US100, US30, and US500. You can easily customize the asset tickers to fit your needs.

Technical Details:

The script uses request.security to fetch the previous day's closing price for each asset.
Data is presented in a table in the bottom-right corner of the chart.
Updates automatically with each new bar.
Note:
This script is optimized for assets traded on the CAPITALCOM platform. Make sure to use the correct ticker symbols to ensure accurate data.
