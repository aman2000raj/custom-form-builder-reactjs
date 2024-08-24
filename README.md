# Form Builder ReactJS

## Overview
A dynamic form builder and renderer using **React**, **jQuery**, **formBuilder**, and **react-json-view**. This application allows users to build custom forms via a drag-and-drop interface, render them dynamically, and preview or submit the form data in JSON format.

## Live Demo

You can view the live demo of the application at [https://your-custom-form-builder.netlify.app/](https://your-custom-form-builder.netlify.app/).


## Features
- **Drag-and-Drop Form Builder**: Create forms using `formBuilder`.
- **Form Renderer**: Render and submit the built forms.
- **JSON Preview**: View form schema and submission data using `react-json-view`.
- **Clear & Reset**: Options to clear the form and rebuild.

## Installation

1. Clone the repository:
   ```bash
   `git clone https://github.com/your-username/custom-form-builder-reactjs.git
   cd form-builder-reactjs`

   1.  Install dependencies:

    `npm install`

    2.  Start the development server:

    `npm start`

Usage
-----

1.  **Build a Form**: Use the drag-and-drop interface to create forms.
2.  **Save & Preview**: Save the form schema and view it in JSON format.
3.  **Render & Submit**: Fill out the generated form and submit it to preview the form data in JSON format.
4.  **Clear**: Reset the form using the clear option.

Project Structure
-----------------

    
    |-- /src
        |-- components/        # FormBuilder, FormRender
        |-- context/           # MyContext for state management
    |-- App.js                 # Main component
    |-- index.js               # Entry point
    |-- package.json           # Dependencies and scripts



Key Components
--------------

-   **App.js**: Wraps `FormBuilder` and `FormRender` in a context provider to manage global state.
-   **FormBuilder.js**: Provides the form-building interface using jQuery `formBuilder`.
-   **FormRender.js**: Renders and submits the form.
-   **context.js**: Provides shared state using React Context API.

Scripts
-------

-   **`npm start`**: Start the development server.
-   **`npm test`**: Run tests.

   
