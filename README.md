Live Project Link: https://cnapp-dashboard.vercel.app/

React Project: "Accuknox" - README
Overview
This project is a React-based dashboard application that leverages Material-UI, Chart.js, and FontAwesome for its UI components and icons. It includes various widgets for cloud account monitoring and security assessments.

Prerequisites
Before running the project, ensure you have the following installed on your local machine:

Node.js (version 14.x or higher)
npm (Node Package Manager) or yarn

Installation
1. Clone the Repository
Clone the repository to your local machine using the following command:

  > git clone https://github.com/your-username/accuknox.git

2. Navigate to the Project Directory
   
  > cd accuknox

3.  Install Node modules

   > npm i

4. Install Dependencies
Install the necessary dependencies using npm or yarn:

  > npm install [nameAndVersion]

Running the Application
1. Start the Development Server
To run the project in development mode, use the following command:

  > npm start

This will start the development server, and the application will be available at http://localhost:3000/.

2. Building for Production
To build the project for production, use:

  > npm run build
> 
This will create an optimized build of the application in the build/ directory.

3. Running Tests
To run the test suite, use:

  > npm test


Project Structure
public/: Contains the static assets and the main index.html.
src/: Contains the main source code for the React application.
components/: Reusable React components.
App.js: Main application component.
index.js: Entry point for the React application.
package.json: Lists all the dependencies and scripts for the project.
Dependencies
The project relies on the following key dependencies:

React (react, react-dom): Core library for building user interfaces.
Material-UI (@mui/material, @mui/icons-material): Provides a collection of React components that implement Google’s Material Design.
Emotion (@emotion/react, @emotion/styled): Library for writing CSS styles with JavaScript.
FontAwesome (@fortawesome/react-fontawesome, @fortawesome/free-solid-svg-icons): Icon library.
Chart.js (chart.js, react-chartjs-2): Library for creating charts.
Testing Libraries (@testing-library/react, @testing-library/jest-dom, @testing-library/user-event): Utilities for testing React components.
