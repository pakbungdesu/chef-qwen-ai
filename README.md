# 🍳 Chef Qwen AI — Smart Recipe Generator

Chef Qwen AI is a React web application that uses artificial intelligence to generate custom, step-by-step recipes based on whatever ingredients the user has on hand. Built with React and powered by the Hugging Face Serverless Inference API.

## ✨ Features
* **Ingredient Tracker:** Add ingredients dynamically to a list.
* **Smart UI States:** Button includes smooth interactive hover/active scales, changing into a non-clickable gray loading element while fetching the AI payload.
* **AI Recipe Generation:** Connects directly to Hugging Face models to compile recipes based on your listed items.
* **Markdown Support:** Renders beautifully formatted headings, bullet points, and steps using `react-markdown`.

---

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### 1. Installation
Clone the repository and install the necessary package dependencies:
```bash
npm install
```

### 2. Environment Setup
You must secure your Hugging Face API token before running the project.

Create a file named `.env` in the root folder of the project (next to `package.json`):

```
REACT_APP_HF_ACCESS_TOKEN=your_huggingface_token_here
```
⚠️ Important: Do not upload your real .env file to GitHub. It is ignored by the system automatically if added to your `.gitignore.`

### 3. Running the App
Start the development server:

```Bash
npm start
```
Open http://localhost:3000 to view your recipe app in the browser.

## 🛠️ Built With
- React (Create React App workflow)

- Hugging Face Inference SDK (`@huggingface/inference`)

- React Markdown (`react-markdown`)

- CSS3 (Custom UI layout and button transitions)

## 📦 Available Component Scripts
`npm start`
Runs the app in development mode with active reload states.

`npm run build`
Builds and minifies the application to a production-ready build folder.