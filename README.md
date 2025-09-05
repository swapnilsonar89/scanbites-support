# 🍎 ScanBites - Smart Food Scanner

A beautiful, cost-optimized React Native app that scans food barcodes and analyzes ingredients with FREE local intelligence and optional premium AI to help you make healthier food choices.

## ✨ Features

### 📱 **Smart Scanning**
- **Barcode scanner** with animated scan frame and haptic feedback
- **Smart OCR fallback** for ingredient panels with free-first approach
- **Cost-optimized analysis** using local intelligence + optional premium AI

### 🧠 **AI-Powered Analysis**
- **FREE local analysis** for 90% of scans - no API costs!
- **Smart cost optimization** - premium AI only when needed
- **Personalized insights** based on your dietary preferences
- **Pros & cons** breakdown for each product
- **Allergen detection** and warnings
- **Nutritional scoring** with Nutri-Score and NOVA ratings

### 🥗 **Dietary Preferences**
- Vegan, Vegetarian, Halal, Kosher options
- Gluten-free and Lactose-free detection
- Custom allergen and ingredient avoidance lists
- Tailored recommendations based on your needs

### 💝 **Social Impact**
- **Donation tracking** for hunger-fighting charities
- Support for Feeding America, No Kid Hungry, and World Central Kitchen
- **Private impact metrics** stored locally on your device

### 🆓 **Cost Optimization**
- **90% FREE analysis** using advanced local intelligence
- **Smart OCR** tries free methods before premium AI
- **Optional OpenAI integration** for complex ingredient photos
- **Transparent cost indicators** - you always know what's free vs premium

## 🚀 Quick Start

### Prerequisites
- Node.js and npm
- Expo CLI (`npm install -g expo-cli`)
- OpenAI API key (OPTIONAL - app works great without it!)

### Installation
```bash
# Clone and install dependencies
npm install

# Start the development server
npm run ios     # for iOS
npm run android # for Android
```

### Setup
1. **Open the app** and complete the onboarding experience
2. **Start scanning immediately** - most features work without any setup!
3. **Optional**: Get your OpenAI API key from [OpenAI Platform](https://platform.openai.com/api-keys)
4. **Optional**: Go to Settings ⚙️ and enter your API key for premium OCR
5. **Set your dietary preferences** for personalized analysis

## 🎨 Beautiful Design

### Modern UI Features
- **Consistent blue theme** (#2563eb) throughout the app
- **Smooth animations** and haptic feedback
- **Card-based layouts** with subtle shadows
- **Emoji-enhanced sections** for better visual hierarchy
- **Professional typography** with proper spacing
- **Cost transparency** indicators

### User Experience
- **Intuitive onboarding** explaining free vs premium features
- **Real-time OCR choice** - free or premium options
- **Loading states** with elegant animations and cost indicators
- **Error handling** with helpful fallback suggestions
- **Accessibility** considerations throughout

## 🛠 Technical Details

### Built With
- **React Native** with TypeScript
- **Expo** for cross-platform development
- **Local analysis engine** for ingredient intelligence
- **Free OCR system** with smart enhancement
- **OpenAI API** (optional) for premium analysis
- **Open Food Facts** database for product lookup
- **Expo Camera** for barcode scanning
- **Expo Haptics** for tactile feedback

### Architecture
- **No backend required** - everything runs on device
- **Secure storage** using Expo SecureStore for API keys
- **Privacy-first** - all data stays on your device
- **Cost-optimized** - local processing first, API calls only when needed
- **Offline-capable** impact tracking

## 🔒 Privacy & Security

- **API keys** are stored securely on-device using encrypted storage
- **Dietary preferences** never leave your device
- **Donation tracking** is completely private and local
- **Minimal external calls** - only to Open Food Facts and optionally OpenAI
- **No user tracking** or analytics - completely standalone

## 📱 App Icon

The app includes a beautiful custom icon featuring:
- **Blue gradient background** matching the app theme
- **Food symbolism** (apple with leaf)
- **Scanning elements** (barcode lines, scan frame)
- **Health indicators** (checkmark, AI sparkle)

## 🚢 App Store

ScanBites is available on the iOS App Store! The app features:
- **iPhone-optimized** experience
- **No subscriptions** - optional premium features only
- **Complete privacy** - no data collection
- **Professional quality** UI and user experience

## 🤝 Contributing

This project demonstrates modern React Native development with cost optimization and privacy-first design principles.

## 📄 License

MIT License - See LICENSE file for details.

---

**Disclaimer**: This app provides general educational information about food ingredients and should not be considered medical advice. Always consult healthcare professionals for dietary and health decisions.