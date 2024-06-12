# React Forms and Form Validation

React application that creates a form with validation for required fields without using third-party libraries. It displays error messages, disables submission until all fields are filled correctly, and shows all the filled details on a new route after a successful submission.

## Scripts

In the project directory, you can run :

### `npm start`

Runs the app in development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload if you make changes.  
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.  
See the section about running tests for more information.

### `npm run build`

Builds the app for production to the `build` folder.  
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.  
Your app is ready to be deployed!

See the section about deployment for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you eject, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc.) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point, you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However, we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Project Details

### Form Fields

- **First Name** : Required
- **Last Name** : Required
- **Username** : Required
- **E-mail** : Required (must be a valid email format)
- **Password** : Required (with show/hide functionality)
- **Phone No.** : Required (country code __ number)
- **Country** : Required (dropdown)
- **City** : Required (dropdown)
- **Pan No.** : Required
- **Aadhar No.** : Required

### Features

- **Validation**: Each field is validated, and error messages are displayed if the requirements are not met.
- **Submit Button**: The form's submit button is disabled until all fields are correctly filled.
- **Success Route**: Upon successful submission, the form details are displayed on a new route.

## Folder Structure

```
React-Form/
├── README.md
├── node_modules/
├── package.json
├── public/
│   └── index.html
└── src/
    ├── components/
    │   └── Form-component.js
    ├── styles.css
    └── index.js
```


## Dependencies

This project uses React. Ensure you have Node.js installed, then you can install the dependencies using:

```bash
npm install
```

# 
![image](https://github.com/ravikant-diwakar/React-Form/assets/110620635/20183044-6a58-4791-a59f-374d88a843fd)

#
![image](https://github.com/ravikant-diwakar/React-Form/assets/110620635/5d99560e-29df-436a-bebe-56571ea36523)

#
![image](https://github.com/ravikant-diwakar/React-Form/assets/110620635/9cba489a-7bfe-437d-8761-9c68379208c1)
