# Portfolia - Financial Portfolio Tracker

Welcome to Portfolia! In this interview, you will create a portfolio tracker that allows users to view, add, and manage their stock buys. This project is designed to evaluate your skills in state management, component design, and data handling.

<img src="dashboard.png?raw=true" width="600" />

## Project Overview

You will build a single-page application using either Vue, React, or Angular. We've provided starter projects for each framework in the respective folders (`vue`, `react`, `angular`). Your task is to hydrate the application with data from a hosted JSON file, allow users to add new stock buys, and provide a detailed view for each stock buy.

## Requirements

1. **Hydrate Data**: Fetch and display data from the provided JSON file.
2. **Add New Stock Buys**: Implement a form to add new stock buys.
3. **Detail View**: Allow users to click on a stock buy to view more detailed information.

## Instructions

1. Clone this repository.
2. Navigate to the folder of your chosen framework (`vue`, `react`, or `angular`).
3. Install the dependencies and start the development server.
4. Fetch data from the hosted JSON file and display it in the application.
5. Implement the feature to add new stock buys.
6. Implement click-through on each stock block to show a more detailed view of that stock buy.

## JSON Data

You can fetch the stock buy data from the following link:

[Stock Buys JSON](http://jon.allocate.biz.s3-website-us-east-1.amazonaws.com/stock-buys.json)

## Figma Design

You can find the design for the application in the following Figma file:

[Figma Design](https://www.figma.com/design/P1oBgoCVbTTY8NbiDIigYH/Portfolia?node-id=0-1&t=ykg1Oeiy3Ot4DFhB-1)

## Starter Project Links

- [Vue Starter Project](./vue)
- [React Starter Project](./react)
- [Angular Starter Project](./angular)

## Getting Started

### Vue
```sh
cd vue
npm install
npm run dev
```

### React
```sh
cd react
npm install
npm start
```

### Angular
```sh
cd angular
npm install
ng serve
```

## Evaluation Criteria
- Proper data fetching and state management.
- Clear and responsive UI design matching the Figma file.
- Clean, maintainable code with proper component structure.
- Functionality to add new stock buys and view detailed information.