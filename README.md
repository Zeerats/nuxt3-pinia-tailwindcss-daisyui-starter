# Nuxt 3 Starter

Welcome to the Nuxt 3 Starter! This repository was built with a few key technologies in mind to make your development experience smoother and more efficient. These technologies include Nuxt 3, Tailwind CSS, Pinia, and DaisyUI.

## Getting Started

### Prerequisites

Ensure you have the following installed on your local development machine:

- Node.js and npm
- A code editor such as VSCode
- Git

### Clone the repository

First, navigate to the main page of the repository. Under the repository name, click the green "Code" button. Copy the clone URL for the repository.

Open Terminal (or Terminal in WS2), navigate to the location where you would like to clone the repository and run:

CODE
git clone <repository-url>
cd <repository-folder>
CODE

### Install Dependencies

After cloning the repository, navigate to the root directory of the project in your terminal and run the following command to install necessary dependencies:

CODE
npm install
CODE

### Run the Application

In order to start the server and run the application in a development environment, execute:

CODE
npm run dev
CODE

The server will start, and you can access the application in your web browser at `http://localhost:3000`.

## Using Nuxt 3 Starter

This repository is designed to be a starting point for your Nuxt 3 applications. It provides a standardized, high-quality foundation for building successful projects.

### Structure

The repository is structured as follows:

- CODE src/components CODE: This directory contains all the Vue components that are used in the application.
- CODE src/layouts CODE: This directory contains layout components, which dictate the structure of the page where other components will be slotted in.
- CODE src/pages CODE: This directory contains the page components.
- CODE src/store CODE: This directory contains the Pinia store.

### Styling

The project uses Tailwind CSS for styling and DaisyUI for additional UI components. 

### State Management

Pinia is used for state management in the project. It is a simpler and more straightforward way to manage state in Vue.js and Nuxt.js applications.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

