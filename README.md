Here’s a **`README.md`** file for your GitHub repository:  

---

# AI Chatbot  

This repository contains the code for a simple **AI Chatbot** application built using **HTML**, **CSS**, and **JavaScript**. The chatbot allows users to interact with an AI by sending text messages and uploading images. It dynamically displays user and AI responses in a visually appealing chat interface.  

---

## Features  

- **Interactive Chat Interface:**  
  Users can send messages and view AI responses in a structured, conversational format.  

- **Image Upload and Display:**  
  Supports uploading images, which are displayed alongside user messages.  

- **Smooth Animations and Loading Effects:**  
  Includes a loading animation to enhance user experience while awaiting AI responses.  

- **Responsive Design:**  
  Fully responsive layout for seamless use on different screen sizes, including mobile devices.  

---

## Technologies Used  

### **Frontend:**  
- **HTML:** Provides the structure of the chatbot application.  
- **CSS:** Handles the styling, including animations, themes, and responsive design.  
- **JavaScript:** Manages user interaction, API communication, and dynamic updates to the chat interface.  

### **API:**  
- The chatbot integrates with an **AI API** to generate responses based on user input.  
- **API Endpoint:** Replace `Api_Url` in `script.js` with your API key for functionality.  

---

## Installation  
  

1. Replace the placeholder API key in the `script.js` file with your actual API key:  
   ```javascript  
   const Api_Url = "https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=**Your-API-Key**";
   ```  

2. Open the `index.html` file in your browser to use the chatbot.  

---

## Usage  

1. **Send Messages:**  
   Type a message in the input field and press `Enter` or click the send button to interact with the AI.  

2. **Upload Images:**  
   Click the image button to upload an image. The image will be displayed alongside your message.  

3. **AI Responses:**  
   The AI will respond to your input dynamically.  

---

## Project Structure  

```
|-- index.html           # Chatbot interface structure  
|-- style.css            # Styling for the chatbot  
|-- script.js            # Handles chatbot functionality and API communication  
|-- images/              # Folder containing icons and assets for the chatbot  
```  

---
#Working model
