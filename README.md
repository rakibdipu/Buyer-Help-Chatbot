# Buyer Help Chatbot

AI-powered international shopping assistant with live web search capabilities.

## Features

- Live web search for products and prices
- Product comparison across Amazon, Alibaba, eBay
- Order tracking assistance
- Import duties and customs information
- Return and refund policy guidance
- Real-time typing indicators
- Responsive design

## Tech Stack

- React 18
- Vite
- JavaScript
- CSS3

Install dependencies:

bashnpm install

Start development server:

bashnpm run dev

Open browser:

http://localhost:5173
Build for Production
bashnpm run build
Project Structure
buyer-help-chatbot/
├── src/
│   ├── App.jsx          # Main chatbot component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
├── index.html           # HTML template
├── vite.config.js       # Vite configuration
└── package.json         # Dependencies
Usage
Type your questions about products, shopping, or international buying. The chatbot will search the web and provide relevant information.
Contributing
Pull requests are welcome. For major changes, please open an issue first.
License
MIT

---

## **Step 2: Initialize Git**

Open terminal in your project folder:
bash
# Initialize git repository
git init

# Add all files
git add .

# Make first commit
git commit -m "Initial commit: Buyer Help Chatbot with live web search"

Step 3: Create GitHub Repository

Go to https://github.com
Click the "+" icon (top right) → "New repository"
Fill in:

Repository name: buyer-help-chatbot
Description: "AI-powered buyer assistant with live web search"
Public or Private (your choice)
DON'T check "Initialize with README" (you already have one)


Click "Create repository"


Step 4: Connect and Push
GitHub will show you commands. Use these:
bash# Add remote repository
git remote add origin https://github.com/YOUR_USERNAME/buyer-help-chatbot.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
Replace YOUR_USERNAME with your actual GitHub username.

Step 5: Verify Upload
Go to your GitHub repository URL:
https://github.com/YOUR_USERNAME/buyer-help-chatbot
You should see all your files.

Step 6: Deploy Online (Optional)
Deploy to Vercel (Recommended - Free):

Go to https://vercel.com
Sign in with GitHub
Click "Import Project"
Select your repository
Click "Deploy"
Done! You'll get a live URL like: buyer-help-chatbot.vercel.app

Or Deploy to Netlify:

Go to https://netlify.com
Sign in with GitHub
Click "Add new site" → "Import an existing project"
Select your repository
Build settings:

Build command: npm run build
Publish directory: dist


Click "Deploy"


Future Updates:
When you make changes:
bash# Check what changed
git status

# Add changes
git add .

# Commit with message
git commit -m "Add new feature: XYZ"

# Push to GitHub
git push

Your package.json should have:
json{
  "name": "buyer-help-chatbot",
  "private": true,
  "version": "1.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "@vitejs/plugin-react": "^4.2.1",
    "vite": "^5.0.8"
  }
}
