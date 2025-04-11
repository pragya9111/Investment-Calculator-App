# InvestmentCalculatorApp

The **InvestmentCalculatorApp** is a web-based application built using Angular. It allows users to calculate potential returns on investments based on various parameters such as principal amount, interest rate, and investment duration. The application is designed to provide a user-friendly interface and accurate calculations for financial planning.

## Live Preview

You can access the live version of the application here: [Investment Calculator App](https://investment-calculator-app-zeta.vercel.app/
)
## Project Overview

This project was developed using **Angular CLI** version 19.2.5. It demonstrates the use of Angular's core features, including components, services, and data binding, to create a dynamic and interactive user experience.

### Key Features

- **Investment Calculation**: Calculate returns based on user inputs like principal, rate of interest, and time period.
- **Dynamic Updates**: Real-time updates to the results as users modify input values.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Error Handling**: Validation for user inputs to ensure accurate calculations.
- **Modular Architecture**: Clean and maintainable code structure using Angular best practices.

## Folder Structure

The project follows a standard Angular folder structure:

```
investment-calculator-app/
├── src/
│   ├── app/
│   │   ├── components/       # Contains all reusable components
│   │   │   ├── calculator/   # Main investment calculator component
│   │   │   ├── header/       # Header component
│   │   │   └── footer/       # Footer component
│   │   ├── services/         # Contains application services (e.g., calculation logic)
│   │   ├── models/           # Defines TypeScript interfaces and models
│   │   └── app.module.ts     # Root module of the application
│   ├── assets/               # Static assets like images and styles
│   ├── environments/         # Environment-specific configurations
│   └── index.html            # Main HTML file
├── angular.json              # Angular CLI configuration
├── package.json              # Project dependencies and scripts
└── README.md                 # Project documentation
```

## Functionalities

1. **User Input**: Users can input the principal amount, interest rate, and investment duration.
2. **Real-Time Calculation**: The app dynamically calculates and displays the investment returns.
3. **Interactive UI**: A clean and intuitive interface for seamless user interaction.
4. **Validation**: Ensures all inputs are valid before performing calculations.
5. **Responsive Design**: Works flawlessly on devices of all sizes.

## How to Use

1. Clone the repository to your local machine.
2. Install dependencies using `npm install`.
3. Start the development server with `ng serve`.
4. Open your browser and navigate to `http://localhost:4200/`.

## Additional Resources

For more information about Angular, visit the [Angular Official Documentation](https://angular.io/docs).
