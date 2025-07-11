# Stock Trading Game Android App

A React Native mobile application that simulates stock trading with a fun and interactive interface.

## 🚀 **LATEST VERSION - ALL FEATURES WORKING**

**🆕 NEW FEATURES ADDED:**
- **✅ Dynamic Price Updates**: Stock prices now update every 3 seconds automatically
- **✅ Save/Load Game**: Manual save button creates a file on your phone
- **✅ Auto-Save**: Game automatically saves every 30 seconds
- **✅ Reset Button**: Complete game reset with confirmation dialog
- **✅ Persistent Storage**: Game state loads automatically when you open the app

## Features

- 📱 **Buy and Sell Stocks**: Interactive buy/sell buttons for 6 different stocks
- 💰 **Portfolio Management**: Track your cash balance, portfolio value, and total worth
- 📊 **Real-time Stock Data**: Dynamic stock prices that change every 3 seconds
- 🎯 **Percentage-based Trading**: Choose what percentage of your balance to invest
- 📈 **Stock Portfolio Tracking**: See exactly how many shares you own of each stock
- 🎮 **Game-like Experience**: Start with $10,000 virtual money to trade
- 💾 **Save System**: Manual and automatic save functionality
- 🔄 **Reset Functionality**: Complete game reset option
- 📱 **Persistent Data**: Your progress is saved to your phone's storage

## Available Stocks

- **AAPL** - Apple Inc.
- **GOOGL** - Alphabet Inc.
- **MSFT** - Microsoft Corp.
- **TSLA** - Tesla Inc.
- **AMZN** - Amazon.com Inc.
- **NVDA** - NVIDIA Corp.

## Game Mechanics

### **Price Updates**
- Stock prices change every **3 seconds** with random fluctuations
- Prices can fluctuate up to ±2% per update
- Minimum price floor at 50% of original stock price
- Real-time visual feedback with green/red change indicators

### **Save System**
- **Manual Save**: Blue "💾 SAVE" button in the header
- **Auto-Save**: Automatic save every 30 seconds (silent)
- **Save Location**: `/Android/data/com.stocktradinggame/files/StockTradingGameSave.json`
- **Auto-Load**: Game automatically loads your saved progress on startup

### **Reset System**
- **Reset Button**: Orange "🔄 RESET" button in the header
- **Confirmation Dialog**: Prevents accidental resets
- **Complete Reset**: Returns to $10,000 cash, no stocks, original prices

## How to Use

1. **Install the APK**: Download `StockTradingGame.apk` to your Android device
2. **Enable Unknown Sources**: Go to Settings > Security > Enable "Install from Unknown Sources"
3. **Install**: Tap the APK file and follow installation prompts
4. **Grant Permissions**: Allow storage access when prompted (needed for save/load)
5. **Start Trading**: You begin with $10,000 virtual cash
6. **Watch Prices**: Stock prices update automatically every 3 seconds
7. **Buy Stocks**: Tap the green "BUY" button next to any stock
8. **Choose Investment**: Enter the percentage of your balance to invest (1-100%)
9. **Sell Stocks**: Tap the red "SELL" button to sell a percentage of your holdings
10. **Save Progress**: Tap "💾 SAVE" to manually save (or wait for auto-save)
11. **Reset Game**: Tap "🔄 RESET" if you want to start over

## App Interface

### **Header Section**
- **Game Title**: "Stock Trading Game"
- **Cash Balance**: Your available money for trading
- **Portfolio Value**: Current value of all your stock holdings
- **Total Value**: Cash + Portfolio (your net worth)
- **💾 SAVE Button**: Manual save to phone storage
- **🔄 RESET Button**: Reset game with confirmation

### **Status Indicator**
- **Price Update Notice**: "📈 Prices update every 3 seconds • Auto-save every 30 seconds"

### **Stock Cards**
- **Stock Symbol & Name**: Company ticker and full name
- **Current Price**: Real-time updating price
- **Price Change**: Daily change amount and percentage (color-coded)
- **Shares Owned**: How many shares you currently own
- **BUY/SELL Buttons**: Green buy, red sell (disabled if no shares)

### **Trading Modal**
- **Stock Information**: Current price display
- **Percentage Input**: Enter 1-100% investment amount
- **Live Preview**: Shows exact dollar amount and shares
- **Confirm/Cancel**: Complete or abort the transaction

## Technical Details

- **Platform**: React Native (Android APK)
- **File Size**: ~96MB
- **Requirements**: Android 7.0+ (API level 24+)
- **Architecture**: Built with React Native 0.80.1
- **JavaScript Bundle**: Properly included and optimized
- **Storage Permissions**: Required for save/load functionality
- **File System**: Uses react-native-fs for local storage

## Installation Steps

1. **Download**: Get the `StockTradingGame.apk` file (96MB)
2. **Security Settings**: Enable installation from unknown sources:
   - Go to `Settings` > `Security` > `Unknown Sources` (Enable)
   - Or `Settings` > `Apps` > `Special Access` > `Install Unknown Apps`
3. **Install**: Open file manager, locate the APK, and tap to install
4. **Permissions**: Grant storage permission when prompted (essential for save/load)
5. **Launch**: Find "Stock Trading Game" in your app drawer and open it
6. **Start Trading**: Begin with $10,000 and start your trading journey!

## Troubleshooting

- ✅ **"Unable to load script" error**: FIXED in current version
- ✅ **JavaScript bundle**: Now properly included in APK
- ✅ **App crashes on startup**: Should no longer occur with fixed version
- ✅ **Static prices**: FIXED - Prices now update every 3 seconds
- ✅ **No save functionality**: FIXED - Full save/load system implemented
- ⚠️ **Storage permission denied**: App will work but won't save progress
- ⚠️ **Save file not found**: Game will start with default values

## What's New in Latest Version

### � **Major New Features**
- **📈 Dynamic Price Updates**: Stock prices change every 3 seconds with realistic fluctuations
- **� Manual Save System**: Blue save button creates `StockTradingGameSave.json` on your device
- **⏰ Auto-Save Feature**: Silent auto-save every 30 seconds to preserve progress
- **🔄 Reset Functionality**: Orange reset button with confirmation dialog
- **📱 Persistent Storage**: Automatic loading of saved game on app startup
- **� Storage Permissions**: Added proper Android permissions for file access

### 🛠️ **Technical Improvements**
- **react-native-fs Integration**: Professional file system operations
- **Interval Management**: Proper cleanup of timers and intervals
- **Error Handling**: Graceful fallback if save/load operations fail
- **Memory Management**: Efficient price update system
- **UI Enhancements**: Status indicators and progress feedback

### 📊 **Game Mechanics**
- **Price Algorithm**: ±2% random fluctuations every 3 seconds
- **Price Floor**: Minimum 50% of original stock price (prevents crashes)
- **Save Format**: JSON format with balance, portfolio, stocks, and timestamp
- **Auto-Load**: Seamless continuation of previous gaming session

---

*This is a simulation game for educational and entertainment purposes only. No real money or actual stock trading is involved.*