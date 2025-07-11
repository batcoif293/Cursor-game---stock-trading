# Stock Trading Game Android App

A React Native mobile application that simulates stock trading with a fun and interactive interface.

## 🚀 **PERMISSIONS FIXED - NO PERMISSIONS REQUIRED**

**🔧 STORAGE PERMISSIONS ISSUE COMPLETELY RESOLVED:**
- **✅ Internal Storage**: Switched to app's private internal storage
- **✅ No Permissions Required**: Works on all Android versions without any permissions
- **✅ Secure & Reliable**: Files stored in app-private directory
- **✅ Auto-Backup**: Automatically backed up by Android system
- **✅ Fixed Settings Menu**: All buttons now work properly

## Features

- 📱 **Buy and Sell Stocks**: Interactive buy/sell buttons for 6 different stocks
- 💰 **Portfolio Management**: Track your cash balance, portfolio value, and total worth
- 📊 **Real-time Stock Data**: Dynamic stock prices that change every 3 seconds
- 🎯 **Percentage-based Trading**: Choose what percentage of your balance to invest
- 📈 **Stock Portfolio Tracking**: See exactly how many shares you own of each stock
- 🎮 **Game-like Experience**: Start with $10,000 virtual money to trade
- 💾 **Secure Save System**: Internal storage with automatic backup
- 🔄 **Reset Functionality**: Complete game reset option with confirmation
- 📱 **Zero Permissions**: No storage permissions required - works instantly
- ⚙️ **Settings Menu**: Force load, file info, and system status
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
- **Internal Storage**: Uses app's private directory (no permissions needed)
- **Manual Save**: Blue "💾 SAVE" button in the header
- **Auto-Save**: Automatic save every 30 seconds (silent)
- **Auto-Load**: Properly loads game on startup
- **Force Load**: Settings menu option with detailed feedback
- **Save Location**: App's internal storage (automatically backed up)

### **Reset System**
- **Reset Button**: Orange "🔄 RESET" button in the header
- **Confirmation Dialog**: Prevents accidental resets
- **Complete Reset**: Returns to $10,000 cash, no stocks, original prices

### **Settings Menu**
- **Access**: Gear icon (⚙️) in top-right corner
- **Force Load**: Manual load with success/error feedback
- **File Info**: View save file details, size, and content preview
- **Storage Status**: Shows that no permissions are required

### **Animated Background**
- **Color Cycle**: Smooth transitions between 4 colors
- **Duration**: Complete cycle every 32 seconds (8 seconds per color)
- **Colors**: Dark blue → Navy → Deep blue → Back to start
- **Performance**: Uses native driver for smooth animation

## How to Use

1. **Install the APK**: Download `StockTradingGame.apk` to your Android device
2. **Enable Unknown Sources**: Go to Settings > Security > Enable "Install from Unknown Sources"
3. **Install**: Tap the APK file and follow installation prompts
4. **Start Trading**: No permissions needed - begin immediately with $10,000
5. **Watch Prices**: Stock prices update automatically every 3 seconds
6. **Buy Stocks**: Tap the green "BUY" button next to any stock
7. **Choose Investment**: Enter the percentage of your balance to invest (1-100%)
8. **Sell Stocks**: Tap the red "SELL" button to sell a percentage of your holdings
9. **Save Progress**: Tap "💾 SAVE" to manually save (or wait for auto-save)
10. **Access Settings**: Tap the gear icon (⚙️) for advanced options
11. **Force Load**: Use settings menu if you need to manually reload
12. **Reset Game**: Tap "🔄 RESET" if you want to start over

## App Interface

### **Header Section**
- **Game Title**: "Stock Trading Game"
- **Settings Icon**: Gear (⚙️) button for advanced options
- **Cash Balance**: Your available money for trading
- **Portfolio Value**: Current value of all your stock holdings
- **Total Value**: Cash + Portfolio (your net worth)
- **💾 SAVE Button**: Manual save to internal storage
- **🔄 RESET Button**: Reset game with confirmation

### **Settings Menu**
- **🔄 Force Load Game**: Manual load with detailed feedback
- **📁 Save File Info**: View file details, size, and content preview
- **✅ Storage Status**: Confirms no permissions are required

### **Status Indicator**
- **Price Updates**: "📈 Prices update every 3 seconds • Auto-save every 30 seconds"
- **Storage Info**: "✅ Using secure internal storage (no permissions required)"

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
- **Storage**: Internal storage (no permissions required)
- **File System**: Uses react-native-fs for internal storage operations
- **Animation**: Uses React Native Animated API for background effects
- **Compatibility**: Works on all Android versions (7.0 to 14+)

## Installation Steps

1. **Download**: Get the `StockTradingGame.apk` file (97MB)
2. **Security Settings**: Enable installation from unknown sources:
   - Go to `Settings` > `Security` > `Unknown Sources` (Enable)
   - Or `Settings` > `Apps` > `Special Access` > `Install Unknown Apps`
3. **Install**: Open file manager, locate the APK, and tap to install
4. **Launch**: Find "Stock Trading Game" in your app drawer and open it
5. **Start Trading**: Begin immediately with $10,000 - no permissions needed!

## Troubleshooting

### ✅ **All Issues Fixed**
- **"Unable to load script" error**: FIXED in current version
- **JavaScript bundle**: Now properly included in APK
- **App crashes on startup**: Should no longer occur with fixed version
- **Static prices**: FIXED - Prices now update every 3 seconds
- **No save functionality**: FIXED - Full save/load system implemented
- **Auto-load not working**: FIXED with enhanced logging and error handling
- **Storage permissions**: FIXED - No permissions required anymore!

### � **For All Android Versions**
- **Android 7-14**: Works perfectly with internal storage
- **No Permission Dialogs**: App installs and runs immediately
- **Settings Integration**: No special permissions shown in Android settings
- **Backup Support**: Files automatically backed up by Android system

### 🛠️ **Advanced Features**
- **Force Load**: Use settings menu for manual loading with diagnostics
- **File Info**: View save file size, modification date, and content preview
- **Storage Status**: Confirms that internal storage is working properly

## What's New in This Version

### � **Storage Permissions Completely Fixed**
- **No Permissions Required**: Switched from external to internal storage
- **Universal Compatibility**: Works on Android 7.0 through Android 14+
- **Instant Installation**: No permission dialogs or setup required
- **Settings Menu Fixed**: All buttons now work properly without permission checks

### 🛠️ **Technical Improvements**
- **Internal Storage**: Uses app's private directory (`DocumentDirectory`)
- **Automatic Backup**: Files backed up by Android system
- **Enhanced Security**: Files only accessible to this app
- **Simplified Code**: Removed all permission-related complexity
- **Better User Experience**: No permission warnings or disabled buttons

### 📊 **Enhanced User Interface**
- **Storage Status Indicator**: Shows that secure internal storage is active
- **Simplified Settings**: Clean interface without permission management
- **Instant Functionality**: All features work immediately after installation
- **Professional Experience**: No technical barriers for users

## Save File Information

### **Location**
- **Directory**: App's internal storage (private)
- **File**: `StockTradingGameSave.json`
- **Access**: Only accessible to this app
- **Backup**: Automatically backed up by Android

### **File Format**
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

### **Benefits of Internal Storage**
- ✅ **No Permissions**: Works on all Android versions without any permissions
- ✅ **Secure**: Files are private to the app
- ✅ **Reliable**: Not affected by Android's scoped storage restrictions
- ✅ **Backed Up**: Automatically included in Android's backup system
- ✅ **Clean Uninstall**: Files automatically removed when app is uninstalled

---

*This is a simulation game for educational and entertainment purposes only. No real money or actual stock trading is involved.*