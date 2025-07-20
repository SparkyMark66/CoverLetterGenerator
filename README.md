# AI Cover Letter Generator 📄✨

A simple, powerful, single-file web application that uses the Gemini AI to generate professional, tailored cover letters. This tool runs entirely in your browser with no installation required.

-----

## Features

  * **AI-Powered Content**: Leverages the Gemini API to create human-like, compelling cover letter content.
  * **Job Description Analysis**: Pasting a job description allows the AI to analyze the role's specific requirements and keywords, ensuring your cover letter is highly targeted.
  * **Detailed Customization**: Input fields for your skills, experience, key achievements, and personal tone of voice.
  * **Regenerate Option**: Don't like the first version? Click "Regenerate" to get a new take from the AI instantly.
  * **Copy to Clipboard**: Easily copy the generated text with a single click.
  * **Zero Installation**: The entire application is a single `.html` file that runs locally in your web browser.
  * **User-Friendly Error Handling**: Displays clear, helpful messages for common issues like API key errors or server overload.

-----

## How to Use

Follow these four simple steps to get the application running.

### 1\. Download the File

Download the `coverlettergenerator.html` file to your computer.

### 2\. Get Your API Key

This application requires a Google AI API key to function.

  * Go to **[Google AI Studio](https://aistudio.google.com/app/apikey)**.
  * Sign in with your Google account and click "**Create API key**".
  * Copy the generated key to your clipboard.

### 3\. Add the API Key to the File

  * Open the `cover-letter-generator.html` file with any text editor (like Notepad or VS Code).
  * Scroll to the bottom and find the `<script type="module">` section.
  * Locate the following line:
    ```javascript
    const apiKey = "YOUR_API_KEY";
    ```
  * Replace `"YOUR_API_KEY"` with the actual key you copied from Google AI Studio. Save the file.

### 4\. Run the Application

**Double-click the saved `cover-letter-generator.html` file.** It will open in your default web browser. You can now fill out the form and start generating cover letters\!

-----

## Requirements

No complex setup or installation is needed. You only need two things:

  * A modern **web browser** (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge).
  * An active **internet connection** (for communicating with the AI).
