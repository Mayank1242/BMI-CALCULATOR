# Deploying a React BMI Calculator to GitHub Pages 📊

A simple and interactive BMI (Body Mass Index) calculator built using React.js.

## Introduction 🚀

This BMI Calculator React.js website is designed to help users calculate their Body Mass Index quickly and easily. It provides a user-friendly interface where users can input their height and weight, and it calculates their BMI based on the provided data.

## Features 🌟

- Calculate BMI based on height and weight inputs.
- Visual representation of BMI categories.
- Easy-to-use and responsive design.
- Provides information on BMI categories (e.g., underweight, normal weight, overweight, etc.).
- Clear and concise results display.

## Installation 🛠️

1. **Clone this repository** to your local machine: git clone https://github.com/Mayank1242/BMI-CALCULATOR.git

2. Navigate to the project directory: cd bmi-calculator-react

3. Install project dependencies: npm install

## Deploying to GitHub Pages

1. Open package.json: In your project's package.json file, make sure the "homepage" field is set correctly. It should be in the format https://github.com/Mayank1242/BMI-CALCULATOR. Update it if necessary.

2. Build the React App: Build your React app to generate a build folder: npm run build

3. Install the gh-pages Package: If you haven't already, install the gh-pages package as a development dependency:
npm install gh-pages --save-dev

4. Add Deployment Script: In your package.json file, add the following to the "scripts" section:

  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
}

5. Deploy to GitHub Pages: Run the deployment script to deploy your React app to GitHub Pages: npm run deploy

6. Access Your Deployed Website: After a few minutes, your React BMI Calculator will be accessible at the URL specified in the "GitHub Pages" section of your repository settings (e.g. https://mayank1242.github.io/BMI-CALCULATOR/)

## Usage 📝

1. Start the development server: npm start

2. Open your web browser and visit http://localhost:3000 to access the BMI Calculator website.

3. Enter your height and weight to calculate your BMI.

4. View your BMI category and interpretation based on the calculated BMI.
 
## Contributing 🤝

We welcome contributions to improve this project. Feel free to submit issues, fork the repository, and create pull requests to enhance it.
