# AI Summary for Articles - Chrome Extension

## Project Overview

AI Summary for Articles is a Chrome extension that helps users quickly understand the content of web articles by generating AI-powered summaries. The extension uses Google's Gemini AI to provide different types of summaries (brief, detailed, or bullet points) of any article the user is viewing.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Chrome Extension APIs**:
  - Manifest V3
  - Chrome Storage API
  - Chrome Tabs API
  - Chrome Scripting API
- **AI Integration**: Google Gemini API
- **Development Tools**: Chrome Extension Development Tools

## Key Features

1. **Multiple Summary Types**:

   - Brief summaries (2-3 sentences)
   - Detailed summaries (comprehensive coverage)
   - Bullet point summaries (5-7 key points)

2. **User-Friendly Interface**:

   - Simple popup interface
   - One-click summarization
   - Copy to clipboard functionality
   - Loading indicators for better UX

3. **Customization Options**:

   - API key management through options page
   - Summary type selection
   - Automatic text extraction from web pages

4. **Technical Features**:
   - Content script integration for text extraction
   - Background service worker for API calls
   - Secure API key storage
   - Error handling and user feedback

## Outcome/Impact

- **Efficiency**: Users can quickly understand article content without reading the entire text
- **Accessibility**: Makes content more accessible for users with limited time
- **Productivity**: Helps users process information faster and more effectively
- **Customization**: Flexible summary options cater to different user needs

## Installation

1. Clone this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked" and select the extension directory
5. Configure your Gemini API key in the extension options

## Usage

1. Navigate to any article you want to summarize
2. Click the extension icon in your Chrome toolbar
3. Select your preferred summary type
4. Click "Summarize" to generate the summary
5. Use the "Copy" button to copy the summary to your clipboard

## Requirements

- Google Chrome browser
- Valid Gemini API key
- Internet connection for API calls
