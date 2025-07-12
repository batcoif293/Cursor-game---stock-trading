# Stock Trading Game Android App

A React Native mobile application that simulates stock trading with a fun and interactive interface.

## 🚀 **NEW SHOP SYSTEM ADDED**

**🛒 EXCITING NEW FEATURES:**
- **🏠 Luxury Apartment**: Buy for $12,000 - unlocks your personal space
- **🚗 Pontiac Aztec**: Purchase for $7,000 - your unique ride  
- **🏠 My House**: View all your possessions after buying an apartment
- **💰 Shopping Experience**: Beautiful shop interface with item details
- **💾 Persistence**: All purchases are saved and loaded automatically

## 🚀 **PERMISSIONS FIXED - NO PERMISSIONS REQUIRED**

**🔧 STORAGE PERMISSIONS ISSUE COMPLETELY RESOLVED:**
- **✅ Internal Storage**: Switched to app's private internal storage
- **✅ No Permissions Required**: Works on all Android versions without any permissions
- **✅ Secure & Reliable**: Files stored in app-private directory
- **✅ Auto-Backup**: Automatically backed up by Android system
- **✅ Fixed Settings Menu**: All buttons now work properly

## Features

### **Trading Features**
- 📱 **Buy and Sell Stocks**: Interactive buy/sell buttons for 6 different stocks
- 💰 **Portfolio Management**: Track your cash balance, portfolio value, and total worth
- 📊 **Real-time Stock Data**: Dynamic stock prices that change every 3 seconds
- 🎯 **Percentage-based Trading**: Choose what percentage of your balance to invest
- 📈 **Stock Portfolio Tracking**: See exactly how many shares you own of each stock

### **Shop & Lifestyle Features**
- 🛒 **Shop System**: Buy luxury items with your trading profits
- � **Luxury Apartment**: $12,000 downtown apartment with city views
- 🚗 **Pontiac Aztec**: $7,000 unique SUV for your daily commute
- 🏠 **My House**: Personal space to view all your possessions (unlocked with apartment)
- 💎 **Collection System**: Build your collection of luxury items

### **Game Features**
- �🎮 **Game-like Experience**: Start with $10,000 virtual money to trade
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

## Shop Items

### **🏠 Real Estate**
- **Luxury Apartment** - $12,000
  - Beautiful downtown apartment with city views
  - Unlocks your personal space and "My House" feature
  - Essential for accessing your possessions collection

### **🚗 Vehicles**
- **Pontiac Aztec** - $7,000
  - Unique and distinctive SUV
  - Perfect for your daily commute
  - Adds style to your virtual lifestyle

## Game Mechanics

### **Stock Trading**
- **Price Updates**: Stock prices change every **3 seconds** with random fluctuations
- **Fluctuation Range**: Prices can fluctuate up to ±2% per update
- **Price Floor**: Minimum price floor at 50% of original stock price
- **Visual Feedback**: Real-time green/red change indicators

### **Shopping System**
- **Shop Access**: Orange "🛒 SHOP" button in the main menu
- **Purchase Confirmation**: Confirm before buying expensive items
- **Ownership Tracking**: Items marked as "OWNED" after purchase
- **Balance Check**: Prevents purchases if insufficient funds
- **Item Details**: Full descriptions and categories for each item

### **House System**
- **Apartment Required**: "🏠 MY HOUSE" button appears after buying apartment
- **Possessions View**: See all your owned items with details
- **Collection Display**: Beautiful interface showing your purchases
- **Item Values**: See the original purchase price of each item

### **Save System**
- **Internal Storage**: Uses app's private directory (no permissions needed)
- **Manual Save**: Blue "💾 SAVE" button in the header
- **Auto-Save**: Automatic save every 30 seconds (silent)
- **Auto-Load**: Properly loads game on startup
- **Complete Persistence**: Saves stocks, portfolio, balance, AND possessions
- **Force Load**: Settings menu option with detailed feedback

### **Reset System**
- **Reset Button**: Red "🔄 RESET" button in the header
- **Confirmation Dialog**: Prevents accidental resets
- **Complete Reset**: Returns to $10,000 cash, no stocks, no possessions, original prices

## How to Use

### **Basic Trading**
1. **Install the APK**: Download `StockTradingGame.apk` to your Android device
2. **Enable Unknown Sources**: Go to Settings > Security > Enable "Install from Unknown Sources"
3. **Install**: Tap the APK file and follow installation prompts
4. **Start Trading**: No permissions needed - begin immediately with $10,000
5. **Watch Prices**: Stock prices update automatically every 3 seconds
6. **Buy Stocks**: Tap the green "BUY" button next to any stock
7. **Choose Investment**: Enter the percentage of your balance to invest (1-100%)
8. **Sell Stocks**: Tap the red "SELL" button to sell a percentage of your holdings

### **Shopping & Lifestyle**
9. **Make Profits**: Trade stocks to build up your cash balance
10. **Visit Shop**: Tap the orange "🛒 SHOP" button when you have enough money
11. **Buy Apartment**: Purchase the $12,000 luxury apartment first
12. **Access House**: The green "🏠 MY HOUSE" button appears after buying apartment
13. **Buy More Items**: Purchase the Pontiac Aztec or save for future items
14. **View Collection**: Use "My House" to see all your possessions

### **Game Management**
15. **Save Progress**: Tap "💾 SAVE" to manually save (or wait for auto-save)
16. **Access Settings**: Tap the gear icon (⚙️) for advanced options
17. **Force Load**: Use settings menu if you need to manually reload
18. **Reset Game**: Tap "🔄 RESET" if you want to start over

## App Interface

### **Header Section**
- **Game Title**: "Stock Trading Game"
- **Settings Icon**: Gear (⚙️) button for advanced options
- **Cash Balance**: Your available money for trading and shopping
- **Portfolio Value**: Current value of all your stock holdings
- **Total Value**: Cash + Portfolio (your net worth)
- **Control Buttons**:
  - **💾 SAVE**: Manual save to internal storage
  - **� SHOP**: Access the shop (orange button)
  - **🔄 RESET**: Reset game with confirmation (red button)
- **🏠 MY HOUSE**: Appears after buying apartment (green button)

### **Shop Interface**
- **Balance Display**: Shows current cash available for shopping
- **Item Cards**: Each item displays:
  - **Large Emoji**: Visual representation of the item
  - **Name & Category**: Item title and category (Real Estate, Vehicle)
  - **Description**: Detailed description of the item
  - **Price**: Cost in dollars
  - **Buy/Owned Button**: Purchase button or "OWNED" status
- **Scrollable List**: Browse through all available items
- **Purchase Confirmation**: Confirm expensive purchases

### **My House Interface**
- **Possessions Collection**: View all owned items
- **Item Details**: Same information as shop, plus:
  - **Original Value**: What you paid for the item
  - **Collection Display**: Beautiful layout of your purchases
- **Empty State**: Encourages shopping if no items owned

### **Stock Trading Interface**
- **Price Updates**: "📈 Prices update every 3 seconds • Auto-save every 30 seconds"
- **Storage Info**: "✅ Using secure internal storage (no permissions required)"
- **Stock Cards**: Company info, current price, changes, owned shares
- **BUY/SELL Buttons**: Green buy, red sell (disabled if no shares)

## Technical Details

- **Platform**: React Native (Android APK)
- **File Size**: ~97MB
- **Requirements**: Android 7.0+ (API level 24+)
- **Architecture**: Built with React Native 0.80.1
- **JavaScript Bundle**: Properly included and optimized
- **Storage**: Internal storage (no permissions required)
- **File System**: Uses react-native-fs for internal storage operations
- **Animation**: Uses React Native Animated API for background effects
- **State Management**: Complete game state including possessions
- **Compatibility**: Works on all Android versions (7.0 to 14+)

## Installation Steps

1. **Download**: Get the `StockTradingGame.apk` file (97MB)
2. **Security Settings**: Enable installation from unknown sources:
   - Go to `Settings` > `Security` > `Unknown Sources` (Enable)
   - Or `Settings` > `Apps` > `Special Access` > `Install Unknown Apps`
3. **Install**: Open file manager, locate the APK, and tap to install
4. **Launch**: Find "Stock Trading Game" in your app drawer and open it
5. **Start Trading**: Begin immediately with $10,000 - no permissions needed!

## Game Strategy Tips

### **Early Game (Starting with $10,000)**
- Focus on stock trading to build up your cash
- Watch for good buying opportunities when prices dip
- Use percentage-based trading to manage risk
- Save regularly to protect your progress

### **Mid Game ($15,000 - $25,000)**
- Consider buying the Pontiac Aztec ($7,000) for your first possession
- Continue trading to build toward apartment money
- Diversify your stock portfolio for stable growth

### **Late Game ($25,000+)**
- Buy the luxury apartment ($12,000) to unlock "My House"
- Enjoy viewing your possessions collection
- Continue trading for the satisfaction of wealth building
- Save your progress and show off your success!

## Troubleshooting

### ✅ **All Issues Fixed**
- **"Unable to load script" error**: FIXED in current version
- **JavaScript bundle**: Now properly included in APK
- **App crashes on startup**: Should no longer occur with fixed version
- **Static prices**: FIXED - Prices now update every 3 seconds
- **No save functionality**: FIXED - Full save/load system implemented
- **Auto-load not working**: FIXED with enhanced logging and error handling
- **Storage permissions**: FIXED - No permissions required anymore!
- **Shop system**: All purchases save and load properly

### 📱 **For All Android Versions**
- **Android 7-14**: Works perfectly with internal storage
- **No Permission Dialogs**: App installs and runs immediately
- **Settings Integration**: No special permissions shown in Android settings
- **Backup Support**: Files automatically backed up by Android system

### 🛠️ **Advanced Features**
- **Force Load**: Use settings menu for manual loading with diagnostics
- **File Info**: View save file size, modification date, and content preview
- **Storage Status**: Confirms that internal storage is working properly

## What's New in This Version

### 🛒 **Brand New Shop System**
- **Complete Shopping Experience**: Beautiful shop interface with item browsing
- **Luxury Apartment**: $12,000 downtown apartment unlocks "My House" feature
- **Pontiac Aztec**: $7,000 unique SUV for your virtual lifestyle
- **My House Feature**: Personal space to view all your possessions
- **Purchase Persistence**: All purchases automatically save and load

### 🏠 **House & Possessions System**
- **Apartment Unlock**: "My House" button appears after buying apartment
- **Collection View**: Beautiful interface showing all owned items
- **Item Details**: View descriptions, categories, and original purchase prices
- **Ownership Tracking**: Items marked as "OWNED" in shop after purchase

### 🛠️ **Technical Improvements**
- **Enhanced Save System**: Now includes possessions data in save files
- **Shop Interface**: Scrollable shop with detailed item information
- **Purchase Confirmation**: Prevents accidental expensive purchases
- **Balance Checking**: Smart prevention of purchases with insufficient funds
- **UI Enhancements**: New buttons, better layout, improved navigation

### 📊 **Enhanced User Experience**
- **Goal-Oriented Gaming**: Trade stocks to afford luxury items
- **Collection Motivation**: Build your possessions collection
- **Lifestyle Simulation**: Virtual apartment and vehicle ownership
- **Progress Visualization**: See your wealth through possessions

## Save File Information

### **Updated Save Format**
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
  "possessions": {
    "apartment": true,
    "pontiac_aztec": true
  },
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