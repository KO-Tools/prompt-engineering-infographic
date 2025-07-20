# Prompt Engineering Infographic

An interactive infographic guide to mastering prompt engineering with AI. Features visual explanations, charts, and interactive tools for enhancing prompts.

## 🎯 Overview

This project provides an interactive, visual guide to prompt engineering that helps users understand and apply the five core ingredients of effective AI prompts:
- **Task**: Explicitly state the action to be performed
- **Context**: Provide the 'why' and background for your request
- **Persona**: Assign a role to the AI for a specific tone and style
- **Format**: Define the desired output structure
- **Example**: Show, don't just tell, with a clear example

## 🚀 Live Demo

[View Live Demo](https://your-netlify-url.netlify.app) *(Update this after deployment)*

## ✨ Features

- **Interactive Charts**: Visual representation of prompt components using Chart.js
- **Prompt Enhancer**: AI-powered tool to improve basic prompts (requires Gemini API key)
- **Idea Generator**: Generate creative prompt ideas based on topics
- **Responsive Design**: Fully responsive layout with Tailwind CSS
- **Educational Content**: Clear explanations and pro-tips for effective prompting

## 🛠️ Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Chart.js for data visualization
- Google Fonts (Inter)
- Gemini API for AI features

## 📦 Deployment

### Deploy to Netlify

1. Fork or clone this repository
2. Sign up for a [Netlify account](https://app.netlify.com/signup) if you don't have one
3. Click the button below to deploy:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/KO-Tools/prompt-engineering-infographic)

### Manual Deployment

1. Clone the repository:
   ```bash
   git clone https://github.com/KO-Tools/prompt-engineering-infographic.git
   cd prompt-engineering-infographic
   ```

2. The project is ready to deploy as-is. Simply drag and drop the project folder into Netlify's deployment area, or use the Netlify CLI:
   ```bash
   npm install -g netlify-cli
   netlify deploy
   netlify deploy --prod
   ```

## 🔑 API Configuration

To enable the AI-powered features (Prompt Enhancer and Idea Generator):

1. Get a Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Open `index.html`
3. Find the line `const apiKey = "";` (around line 396)
4. Replace the empty string with your API key: `const apiKey = "your-api-key-here";`

**Important**: For production deployments, consider using environment variables or a backend service to secure your API key.

### Using Environment Variables (Recommended for Production)

Instead of hardcoding the API key, you can modify the code to fetch it from a backend endpoint or use Netlify Functions to secure your API key.

## 🎨 Customization

The color scheme uses Kind Oasis brand colors:
- Primary Dark Green: `#3A5F4B`
- Darker Green: `#2C4A3C`
- Medium Green: `#668767`
- Light Green: `#A5D6A7`
- Very Light Green: `#D2E8D3`
- Background: `#FAF8F5`

To customize colors, search and replace these hex values in `index.html`.

## 📁 Project Structure

```
prompt-engineering-infographic/
├── index.html          # Main application file
├── README.md          # This file
├── netlify.toml       # Netlify configuration
└── .gitignore        # Git ignore file
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👏 Credits

Created by [Kind Oasis](https://github.com/KO-Tools) - AI/Automation Team

---

**Note**: The AI features require a valid Gemini API key to function. Without it, the infographic will still display all educational content and visualizations, but the interactive AI tools will show an error message.