# Logbook-Pro Pilot Logging Software

![Build](https://github.com/R35007/vite-react-typescript/actions/workflows/build.yml/badge.svg) ![Lints](https://github.com/R35007/vite-react-typescript/actions/workflows/lints.yml/badge.svg) ![Tests](https://github.com/R35007/vite-react-typescript/actions/workflows/tests.yml/badge.svg) ![Cypress](https://github.com/R35007/vite-react-typescript/actions/workflows/cypress.yml/badge.svg)

> A simple vite react typescript starter template with husky, conventional commit, eslint, stylelint, prettier, sass, tailwindcss, material ui, tanstack routing, redux and saga, vitest and cypress

## [Trying this Online!](https://codesandbox.io/p/github/R35007/vite-react-typescript/main?file=/src/main.tsx)


## Installation

```bash
# For full template
npx degit R35007/vite-react-typescript#main myapp # main branch

# For starter template
npx degit R35007/vite-react-typescript#feature/1/starter myapp # feature/1/starter branch
```

## NPM Scripts

### Vite scripts

```bash
npm run start                 # start development server
npm run dev                   # start development server
npm run build                 # build production bundle to 'dist' directly
npm run preview               # start production server
```

### Lint scripts

```bash
npm run lint:scripts          # check scripts
npm run lint:scripts:fix      # fix scripts
npm run lint:styles           # check styles
npm run lint:styles:fix       # fix styles
npm run format                # check code formatting
npm run format:fix            # fix code formatting
npm run lint:ts               # check types
npm run lint                  # check scripts, check styles, check formats and check types
npm run lint:fix              # fix scripts, fix styles, fix formats and check types
npm run lint:staged           # does npm run lint only for staged files
```

### Test scripts

```bash
npm run test             # run test
npm run test:coverage    # run test with code coverage
npm run cy:open          # open cypress ui
npm run cy:run           # run cypress test in headless mode
npm run cy:run:e2e       # run cypress end 2 end test in headless mode
npm run cy:run:component # run cypress component test in headless mode
```

### Report scripts

```bash
npm run lint:scripts:report   # generate eslint reports in reports/eslint.html
npm run lint:report           # generate eslint reports
```

### Utility scripts

```bash
npm run validate              # check scripts, check styles, check formats, check types and builds the project
npm run validate:fix          # fix scripts, fix styles, fix formats, check types and builds the project
npm run validate:staged       # does npm run lint only for staged files and builds the project
npm run prepare               # create Husky hooks
npm run clean                 # removes node_modules package-lock.json .husky dist reports
npm run uninstall:husky       # uninstall husky and remove .husky folder
npm run uninstall:tailwindcss # uninstall tailwindcss and its related plugins
npm run uninstall:cypress     # uninstall cypress and its related plugins and test files
npm run commit                # cli prompt for conventional commit
```

## Goal
As a platform built by pilots, for pilots, this is meant to be an open-source, accessible application that will allow anyone in need of an electronic logbook application to log flight hours, produce reports, maintain airplanes, and manage maintenance logs.

## Getting started

### Cloning the repository
```bash
git clone https://github.com/Rowson3D/logbook-pro.git
```

### Installing Node.JS

### [Learn more about Node.JS!](https://nodejs.org/en)

```bash 
# Verify node version
node --version

# Verify npx version
npx --version

# Verify npm version
npm --verision
```

### Getting Started with Vite / React

```bash
# For full template
npx degit R35007/vite-react-typescript#main myapp # main branch

# For starter template
npx degit R35007/vite-react-typescript#feature/1/starter myapp # feature/1/starter branch
```

## NPM Scripts

### Vite scripts

```bash
npm run start                 # start development server
npm run dev                   # start development server
npm run build                 # build production bundle to 'dist' directly
npm run preview               # start production server
```

### Lint scripts

```bash
npm run lint:scripts          # check scripts
npm run lint:scripts:fix      # fix scripts
npm run lint:styles           # check styles
npm run lint:styles:fix       # fix styles
npm run format                # check code formatting
npm run format:fix            # fix code formatting
npm run lint:ts               # check types
npm run lint                  # check scripts, check styles, check formats and check types
npm run lint:fix              # fix scripts, fix styles, fix formats and check types
npm run lint:staged           # does npm run lint only for staged files
```

### Test scripts

```bash
npm run test             # run test
npm run test:coverage    # run test with code coverage
npm run cy:open          # open cypress ui
npm run cy:run           # run cypress test in headless mode
npm run cy:run:e2e       # run cypress end 2 end test in headless mode
npm run cy:run:component # run cypress component test in headless mode
```

### Report scripts

```bash
npm run lint:scripts:report   # generate eslint reports in reports/eslint.html
npm run lint:report           # generate eslint reports
```

### Utility scripts

```bash
npm run validate              # check scripts, check styles, check formats, check types and builds the project
npm run validate:fix          # fix scripts, fix styles, fix formats, check types and builds the project
npm run validate:staged       # does npm run lint only for staged files and builds the project
npm run prepare               # create Husky hooks
npm run clean                 # removes node_modules package-lock.json .husky dist reports
npm run uninstall:husky       # uninstall husky and remove .husky folder
npm run uninstall:tailwindcss # uninstall tailwindcss and its related plugins
npm run uninstall:cypress     # uninstall cypress and its related plugins and test files
npm run commit                # cli prompt for conventional commit
```

### Run Locally

1. **Install Dependencies**: Make sure you have Node.js and npm installed. Then, navigate to your project directory and run:
    ```bash
    npm install
    ```

2. **Start Development Server**: Run the following command to start the development server:
    ```bash
    npm start
    ```

3. **Open Browser**: Your React app will automatically open in your default web browser.

### Debugging

- **Browser Developer Tools**: Use your browser's developer tools (e.g., Chrome DevTools) to inspect elements, debug JavaScript, and monitor network activity.

- **React Developer Tools**: Install the React Developer Tools browser extension to debug React components, inspect component hierarchies, and track component state.

# The Future

## Objective
The objective of the following is to outline the potential opportunities and/or features that are planned to be designed into the software.

## Features
1. **Flight Logging:**
   - Ability for pilots to log details of their flights, including date, aircraft type, departure and arrival airports, flight duration, etc.
   
2. **Aircraft Management:**
   - Functionality to manage aircraft details, such as registration number, model, capacity, maintenance logs, etc.

3. **Reporting:**
   - Generate customizable reports based on logged flights, including summaries, statistics, and historical data analysis.

4. **Reminders (stretch goal):**
   - Set reminders for upcoming flights, maintenance schedules, license renewals, etc.

5. **User Authentication:**
   - Secure authentication system for pilots to access their logbook data.

6. **Data Visualization:**
   - Visual representation of flight data using charts, graphs, and maps for better analysis.

7. **Export/Import:**
   - Ability to export logbook data in various formats (e.g., CSV, PDF) and import data from other sources.

8. **Cross-Platform Compatibility:**
   - Support for web browsers and mobile devices to access the application seamlessly.

## Technical Considerations
1. **Front-End Technologies:**
   - HTML, CSS, Typescript
   - Frameworks: React.js, Vite.js
   
2. **Back-End Technologies:**
   - Node.js
   - Database: MongoDB
   
3. **Authentication:**
   - Implement JWT (JSON Web Tokens) for secure authentication.
   
4. **Database Design:**
   - Design schema for storing flight logs, aircraft details, user profiles, etc.

5. **API Design:**
   - RESTful API for communication between front end and back end.
   
6. **Deployment:**
   - Deploy application to a cloud platform like AWS, Heroku, or Google Cloud Platform.
   
7. **Testing:**
   - Unit testing for individual components.
   - Integration testing for API endpoints.
   
8. **Security:**
   - Implement measures to prevent unauthorized access and protect user data.
   
9. **Scalability:**
   - Design architecture to handle increasing user load and data volume.

## Next Steps
1. **Wireframing and Mockups:**
   - Create wireframes and mockups to visualize the application's layout and user interface.
   
2. **Development Environment Setup:**
   - Install necessary development tools and set up the development environment.
   
3. **Database Implementation:**
   - Design and implement the database schema.
   
4. **Front-End Development:**
   - Start building the user interface and front-end functionality.
   
5. **Back-End Development:**
   - Implement server-side logic and APIs.
   
6. **Integration and Testing:**
   - Integrate front end with back end and perform testing.
   
7. **Deployment and Maintenance:**
   - Deploy the application and plan for regular maintenance and updates.

## Contributing
Contributors are welcome!

If you encounter a bug, please open an issue.

Contributing guidelines etc will be available as the project matures.

## Licenses
This project is licensed under the following:
1. **GNU General Public License**
   - Because we believe open source is the future, the user is free to run, study, share, and modify the software.
   - All assets are publicly available and accessible through the software.

