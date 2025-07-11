# Stock Trading Game Android App

A React Native mobile application that simulates stock trading with a fun and interactive interface.

## 🚀 **FINAL VERSION - ALL FEATURES COMPLETE**

**🆕 ALL REQUESTED FEATURES IMPLEMENTED:**
- **✅ Fixed Auto-Load**: Automatic game loading on startup now works properly
- **✅ Settings Menu**: Gear icon opens settings with advanced options
- **✅ Force Load Button**: Manual load with detailed feedback and diagnostics
- **✅ Save File Access**: View, edit, and manage your save file location
- **✅ Animated Background**: Smooth color transitions cycling every 32 seconds
- **✅ Enhanced Logging**: Detailed console logs for debugging save/load issues

## Features

- 📱 **Buy and Sell Stocks**: Interactive buy/sell buttons for 6 different stocks
- 💰 **Portfolio Management**: Track your cash balance, portfolio value, and total worth
- 📊 **Real-time Stock Data**: Dynamic stock prices that change every 3 seconds
- 🎯 **Percentage-based Trading**: Choose what percentage of your balance to invest
- 📈 **Stock Portfolio Tracking**: See exactly how many shares you own of each stock
- 🎮 **Game-like Experience**: Start with $10,000 virtual money to trade
- 💾 **Advanced Save System**: Manual, auto-save, and force load functionality
- 🔄 **Reset Functionality**: Complete game reset option with confirmation
- 📱 **Persistent Data**: Your progress is saved to your phone's storage
- ⚙️ **Settings Menu**: Advanced options for file management and debugging
- 🌈 **Animated Background**: Smooth color transitions for visual appeal

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
- **Auto-Load**: Fixed - now properly loads game on startup
- **Force Load**: Settings menu option with detailed feedback
- **Save Location**: `/Android/data/com.stocktradinggame/files/StockTradingGameSave.json`

### **Reset System**
- **Reset Button**: Orange "🔄 RESET" button in the header
- **Confirmation Dialog**: Prevents accidental resets
- **Complete Reset**: Returns to $10,000 cash, no stocks, original prices

### **Settings Menu**
- **Access**: Gear icon (⚙️) in top-right corner
- **Force Load**: Manual load with success/error feedback
- **File Access**: View save file location and contents
- **Permission Management**: Request/check storage permissions
- **Diagnostics**: File existence, size, and content preview

### **Animated Background**
- **Color Cycle**: Smooth transitions between 4 colors
- **Duration**: Complete cycle every 32 seconds (8 seconds per color)
- **Colors**: Dark blue → Navy → Deep blue → Back to start
- **Performance**: Uses native driver for smooth animation

## How to Use

1. **Install the APK**: Download `StockTradingGame.apk` to your Android device
2. **Enable Unknown Sources**: Go to Settings > Security > Enable "Install from Unknown Sources"
3. **Install**: Tap the APK file and follow installation prompts
4. **Grant Permissions**: Allow storage access when prompted (essential for save/load)
5. **Start Trading**: You begin with $10,000 virtual cash
6. **Watch Prices**: Stock prices update automatically every 3 seconds
7. **Buy Stocks**: Tap the green "BUY" button next to any stock
8. **Choose Investment**: Enter the percentage of your balance to invest (1-100%)
9. **Sell Stocks**: Tap the red "SELL" button to sell a percentage of your holdings
10. **Save Progress**: Tap "💾 SAVE" to manually save (or wait for auto-save)
11. **Access Settings**: Tap the gear icon (⚙️) for advanced options
12. **Force Load**: Use settings menu if auto-load doesn't work
13. **Reset Game**: Tap "🔄 RESET" if you want to start over

## App Interface

### **Header Section**
- **Game Title**: "Stock Trading Game"
- **Settings Icon**: Gear (⚙️) button for advanced options
- **Cash Balance**: Your available money for trading
- **Portfolio Value**: Current value of all your stock holdings
- **Total Value**: Cash + Portfolio (your net worth)
- **💾 SAVE Button**: Manual save to phone storage
- **🔄 RESET Button**: Reset game with confirmation
- **Permission Warning**: Shows if storage access is denied

### **Settings Menu**
- **🔄 Force Load Game**: Manual load with detailed feedback
- **📁 Open Save File**: View file location, size, and content preview
- **🔐 Request Permissions**: Check and request storage permissions

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
- **File Size**: ~97MB
- **Requirements**: Android 7.0+ (API level 24+)
- **Architecture**: Built with React Native 0.80.1
- **JavaScript Bundle**: Properly included and optimized
- **Storage Permissions**: Required for save/load functionality
- **File System**: Uses react-native-fs for local storage
- **Animation**: Uses React Native Animated API for background effects

## Installation Steps

1. **Download**: Get the `StockTradingGame.apk` file (97MB)
2. **Security Settings**: Enable installation from unknown sources:
   - Go to `Settings` > `Security` > `Unknown Sources` (Enable)
   - Or `Settings` > `Apps` > `Special Access` > `Install Unknown Apps`
3. **Install**: Open file manager, locate the APK, and tap to install
4. **Permissions**: Grant storage permission when prompted (essential for save/load)
5. **Launch**: Find "Stock Trading Game" in your app drawer and open it
6. **Start Trading**: Begin with $10,000 and start your trading journey!

## Troubleshooting

### ✅ **Fixed Issues**
- **"Unable to load script" error**: FIXED in current version
- **JavaScript bundle**: Now properly included in APK
- **App crashes on startup**: Should no longer occur with fixed version
- **Static prices**: FIXED - Prices now update every 3 seconds
- **No save functionality**: FIXED - Full save/load system implemented
- **Auto-load not working**: FIXED with enhanced logging and error handling

### 🛠️ **Advanced Troubleshooting**
- **Save/Load Issues**: Use settings menu → Force Load for detailed diagnostics
- **Permission Problems**: Settings menu shows exact permission status
- **File Access**: Settings menu provides file location and content preview
- **Missing Save File**: Force load will show if file exists and provide details

### ⚠️ **Known Limitations**
- **Storage permission denied**: App will work but won't save progress
- **File corruption**: Force load will detect and report file issues
- **Android file manager**: Some devices may not open file:// URLs

## What's New in Final Version

### 🔥 **Major Fixes & Enhancements**
- **� Fixed Auto-Load**: Now properly loads saved games on startup
- **⚙️ Settings Menu**: Complete settings interface with gear icon access
- **🔄 Force Load**: Manual load button with detailed success/error feedback
- **� File Management**: View save file location, open directory, preview contents
- **🌈 Animated Background**: Smooth color transitions cycling every 32 seconds
- **🔐 Enhanced Permissions**: Better permission handling and status feedback

### 🛠️ **Technical Improvements**
- **Detailed Logging**: Console logs for debugging save/load operations
- **Error Handling**: Comprehensive error messages for file operations
- **UI Polish**: Semi-transparent backgrounds, better visual hierarchy
- **Performance**: Optimized animation using native driver
- **Diagnostics**: File existence, size, and content inspection tools

### 📊 **Enhanced User Experience**
- **Visual Feedback**: Loading screens, permission warnings, status indicators
- **File Access**: Direct access to save file for manual editing
- **Debugging Tools**: Settings menu provides complete system diagnostics
- **Graceful Degradation**: App works even without storage permissions
- **Professional UI**: Modern design with animated background effects

---

*This is a simulation game for educational and entertainment purposes only. No real money or actual stock trading is involved.*

## Save File Format

The save file (`StockTradingGameSave.json`) contains:
```json
{
  "balance": 10000,
  "portfolio": {
    "AAPL": 5.2341,
    "GOOGL": 2.1234
  },
  "stocks": [
    {
      "symbol": "AAPL",
      "name": "Apple Inc.",
      "price": 187.45,
      "change": 2.13,
      "changePercent": 1.15,
      "basePrice": 185.32
    }
  ],
  "timestamp": 1641234567890
}
```

You can manually edit this file to modify your game state if needed.