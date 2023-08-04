<h1 align="center"> BMI-calculator</h1>

<p align="center"> 
  <a href="#" target="_blank"><img width="1063" alt="Screenshot 2023-03-08 220416" src="https://github.com/PramodTejra/BMI-calculator/assets/99544644/c529e5b9-0377-4f42-98fe-f7a053ca167b">
">
<img width="1079" alt="Screenshot 2023-03-08 220553" src="https://github.com/PramodTejra/BMI-calculator/assets/99544644/c98de376-a1c8-439e-96fa-a1a19a3610f7">

  </a>
</p>

## How to Use 📋

- You'll need Node.js (which comes with npm) installed on your computer. While installing `nodejs`, try to install versions which are equal or greater than the versions mentioned in badges above.
- After the successful installation of `nodejs` and `npm`, clone the repository into your local system.

```bash
# Clone this repository
git clone https://github.com/PramodTejra/BMI-calculator.git

# Go into the repository
cd BMI-calculator

# Install dependencies
npm install

# Start a local dev server, it will open the website locally on your browser
npm start
```

## React BMI Calculator

A BMI (Body Mass Index) calculator is a simple application that allows users to calculate their BMI based on their height and weight. React, a popular JavaScript library for building user interfaces, can be utilized to create an interactive and responsive BMI calculator web application. Here's a short overview of how you can implement it using React:

## 1. Set up the Project:
Start by creating a new React project using create-react-app or your preferred method. Open your project in a code editor.

## 2. Component Structure:
Create components for your BMI calculator. The main components you'll need are:

App.js: The main component that holds the BMI calculator's logic and state.
InputField.js: A component for input fields (height and weight) that handles user input.
Button.js: A component for the "Calculate" button to trigger the BMI calculation.
Result.js: A component to display the calculated BMI and its interpretation.

## 3. State Management:
In the App.js, set up a state to hold the user's height, weight, and calculated BMI. Use React hooks (e.g., useState) to manage the state.

## 4. Handling User Input:
In the InputField.js component, handle user input for height and weight. Use onChange events to update the respective state variables in the App.js component.

## 5. BMI Calculation:
Implement a function in App.js to calculate the BMI based on the user's height and weight. The BMI formula is BMI = weight (kg) / (height (m) * height (m)).
 
## 6. Calculate Button:
In the Button.js component, create a button that, when clicked, calls the BMI calculation function.

## 7. Displaying the Result:
In the Result.js component, show the calculated BMI and an interpretation of the result (e.g., "Underweight," "Normal Weight," "Overweight," "Obese," etc.).

## 8. Styling:
Apply CSS or use a UI library like Bootstrap to style your components and make the BMI calculator visually appealing.

## 9. Testing:
Test the BMI calculator with different height and weight inputs to ensure it calculates the BMI accurately and displays the results correctly.

## 10. Deploy:
Finally, deploy your React BMI calculator to a hosting platform so that others can access and use it online.

Remember that the BMI is just an indicator of body fatness and has its limitations. It does not account for factors such as muscle mass or individual variations. Always consult with a healthcare professional for a comprehensive health assessment.

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
