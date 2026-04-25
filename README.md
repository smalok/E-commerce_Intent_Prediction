# E-commerce_Intent_Prediction

A modern AI-powered e-commerce intent prediction system built with React, TypeScript, and Google's Gemini API.

## Overview

This project predicts customer purchase intent based on user interactions and behavior patterns using machine learning and natural language processing. It provides real-time analytics and insights into customer shopping intentions.

## Features

- 🤖 **AI-Powered Predictions**: Uses Google Gemini API for intent analysis
- 📊 **Dashboard Overview**: Real-time analytics and metrics
- 📈 **Prediction Tracking**: Track prediction results and accuracy
- 🎨 **Modern UI**: Built with React and custom UI components
- ⚡ **Fast Development**: Vite for rapid development and build
- 📱 **Responsive Design**: Works seamlessly on all devices

## Tech Stack

- **Frontend**: React + TypeScript
- **Build Tool**: Vite
- **State Management**: Redux Toolkit
- **API**: Google Gemini API
- **UI Components**: Custom React components
- **Styling**: CSS + Tailwind utilities

## Project Structure

```
├── components/          # Reusable UI components
│   └── ui/             # Component library
├── src/
│   ├── features/       # Feature modules
│   │   ├── dashboard/  # Dashboard views
│   │   └── predictions/# Prediction features
│   ├── lib/            # Utilities and helpers
│   ├── App.tsx         # Main app component
│   └── store.ts        # Redux store configuration
├── package.json        # Dependencies
└── vite.config.ts      # Vite configuration
```

## Installation

**Prerequisites:**
- Node.js (v16 or higher)
- npm or yarn

1. **Clone the repository**
   ```bash
   git clone https://github.com/smalok/E-commerce_Intent_Prediction.git
   cd E-commerce_Intent_Prediction
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   - Create a `.env.local` file in the root directory
   - Add your Gemini API key:
   ```
   VITE_GEMINI_API_KEY=your_api_key_here
   ```

## Running the Application

**Development Mode:**
```bash
npm run dev
```

The app will run at `http://localhost:5173`

**Production Build:**
```bash
npm run build
```

**Preview Build:**
```bash
npm run preview
```

## Usage

1. Navigate to the dashboard to view analytics
2. Use the prediction form to submit customer data
3. View real-time predictions and insights
4. Track historical prediction results

## API Integration

This project uses Google's Gemini API for intent prediction. Make sure to:
1. Get your API key from [Google AI Studio](https://ai.google.dev/)
2. Set it in your `.env.local` file
3. Ensure your quota is sufficient for your usage

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

This project is open source and available under the MIT License.

## Author

**smalok** - E-commerce Intent Prediction System

---

For more information and support, please visit the [GitHub repository](https://github.com/smalok/E-commerce_Intent_Prediction)
