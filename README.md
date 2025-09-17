# Carbon Footprint Calculator with Dashboard

## Introduction

The Carbon Footprint Calculator with Dashboard is a simple web application which aims to help individuals and organizations estimate their carbon footprint by considering various scope-wise parameters, including Scope 1 (fossil fuel and fugitives), Scope 2 (electricity), and Scope 3 (water and waste). This calculator provides a user-friendly interface for data input and visualizes the carbon emissions data using interactive charts. <br>
<!-- Along with the calculator, the dashboard provides the lates news related to the activities taking place in the SEE department, such as projects, talks, papers published etc.<br> -->

The calculator is deployed at : https://iitk.ac.in/ckc/carbon-calculator/ <br>

## Features of the Calculator

### 1. Scope-wise Parameters

The Carbon Footprint Calculator allows users to input data for different scopes of carbon emissions, including:

- **Scope 1: Fossil Fuel Emissions**
  - Users can enter data related to fossil fuel consumption, such as gasoline, diesel, and other direct emissions.

- **Scope 1: Fugitive Emissions**
  - This section allows users to input data related to fugitive emissions, including methane and other greenhouse gases released from various sources.

- **Scope 2: Electricity Consumption**
  - Users can input data regarding electricity consumption, helping them understand the indirect emissions associated with their energy usage.

- **Scope 3: Water and Waste**
  - This section allows users to enter data related to water consumption and waste generation, providing a comprehensive overview of their environmental impact.

### 2. Calculation and Visualization

- The application calculates the total carbon footprint by summing up emissions from all three scopes.

- Interactive charts generated using Chart.js provide users with a visual representation of their carbon emissions data. These charts help users gain insights into which areas contribute the most to their carbon footprint.

<!-- ## Features of the Dashboard

### 1. Comprehensive display of activities at SEE, IIT Kanpur

- Data corresponding to a range of verticals such as projects, papers published, talks etc. can be viewed by the user


### 2. Support for uploading new data via admin login

- The admin can log into the server and update the data that is being displayed. Along with this, the current data can also be downloaded as an Excel Sheet. -->


## Tech Used

- **React.js**: The application is built using React.js, a popular JavaScript library for building user interfaces.
- **ExcelJS** : For calculations of emission values from the excel sheet uploaded by the user.
- **Chart.js**: Chart.js is used for creating interactive charts that display carbon emissions data.
<!-- - **MongoDB** : For storage and retrieval of dashboard data.
- **Node.js with ExpressJS**: For creating a backend server to interact with the MongoDB database. -->

## Installation

To run the Carbon Footprint Calculator on your local machine, follow these steps:

1. Clone the GitHub repository: `git clone`

2. Navigate to all the directories and install dependencies in the respective directories: `npm install`.

3. Start the development server: `npm start`.

<!-- 4. Naviage to the backend folder using `cd ../backend` and run `node server.js` to start the backend server. -->

