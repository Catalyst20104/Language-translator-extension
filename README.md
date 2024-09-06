# Language Translation Extension
# Overview
The Language Translation Extension is a browser add-on that allows users to easily translate any webpage into their desired language. It integrates with popular translation API (Google Translate API) to deliver fast, reliable, and context-aware translations, improving accessibility and understanding of content from around the globe.

# Features
- Instant Text Translation: Select any text on a webpage to get an immediate translation.
- Multi-Language Support: Supports a wide range of languages, ensuring global usability.
- Contextual Awareness: Preserves meaning in complex or idiomatic phrases for accurate translations.
  
# Installation
1. Clone the repository:
- git clone [https://github.com/Catalyst20104/Language-translator-extension.git]
- cd language-translation-extension
  
2. Add the extension to your browser:
- For Chrome:
1. Open Chrome and navigate to chrome://extensions/.
2. Enable Developer mode.
3. Click on Load unpacked and select the cloned repository folder.
   
- For Firefox:
1. Open Firefox and navigate to about:debugging#/runtime/this-firefox.
2. Click on Load Temporary Add-on and select the cloned repository folder.
   
3. Configure API Key:

- Obtain an API key from Google Translate or Microsoft Azure Translator.
- Add the API key in the config.js file in the root directory: const API_KEY = https://translate.google.com/translate?hl=${request.language}&sl=auto&tl=${request.language}&u=${window.location.href};
- 
4.Run the extension:

- Click the extension icon to get the translation and Select language on any webpage.

# Usage
- Click Icon: Click on the extension icon in the toolbar to trigger the translation.
- Select language to Translation: Select language to translation to pop-up window or toolbar.
# Configuration
You can configure the following options within the extension settings:

- Default Language: Set the default target language for translations.
- Speech Output: Enable or disable text-to-speech for the translated text.
- Interface Customization: Adjust the appearance of the extension window and pop-ups.
# Technologies Used
- Frontend: HTML, CSS, JavaScript
- API: Google Translate API
- Browser Integration: Chrome or Firefox Extension API API: Google Translate API or Microsoft Azure Translator API Browser Integration: Chrome or Firefox Extension API
