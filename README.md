# Nuxt 3 Starter (with Tailwind CSS, Pinia, and DaisyUI)

Welcome to my Nuxt 3 Starter. I've created this one to make starting a beautiful Nuxt 3 project easier. It includes Tailwind CSS, Pinia, and DaisyUI.

## Getting Started

### Prerequisites

Ensure you have the following installed on your local development machine:

- Node.js and npm. More info [here](https://nodejs.org/en/download/).
- A code editor such as VSCode. You can download VSCode [here](https://code.visualstudio.com/download).
- Git. More info [here](https://git-scm.com/downloads).

### Clone the repository

First, navigate to the main page of the repository. Under the repository name, click the green "Code" button. Copy the clone URL for the repository.

Open Terminal (or Terminal in WS2), navigate to the location where you would like to clone the repository and run:

```
git clone <repository-url>
cd <repository-folder>
```

### Install Dependencies

After cloning the repository, navigate to the root directory of the project in your terminal and run the following command to install necessary dependencies:

```
npm install
```

### Run the Application

In order to start the server and run the application in a development environment, execute:

```
npm run dev
```

The server will start, and you can access the application in your web browser at `http://localhost:3000`.

## Using Nuxt 3 Starter

This repository is designed to be a starting point for your Nuxt 3 applications. It provides a standardized, high-quality foundation for building successful projects.

### Structure

The repository is structured as follows:

- ``` /pages ```: contains the pages of the application. Refer to the [Nuxt 3 Documentation](https://v3.nuxtjs.org/docs/get-started/routing) for more information on how to create pages.
- ``` /layouts ```: This directory contains layout components, which dictate the structure of the page where other components will be slotted in.
- ``` /store ```: This directory contains the Pinia store.
- ``` /assets ```: contains uncompiled assets such as images, fonts, etc. As well as the css file for global styles.
  
For more information on the Nuxt 3 directory structure, refer to the [Nuxt 3 Documentation](https://v3.nuxtjs.org/docs/directory-structure/nuxt).

### Styling

The project uses [TailwindCSS](https://tailwindcss.com/) for styling and [DaisyUI](https://daisyui.com/) for additional UI components.

### State Management

Pinia is used for state management in the project. It is a simpler and more straightforward way to manage state in Vue.js and Nuxt.js applications.
[Pinia](https://pinia.vuejs.org/)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

MIT License

Copyright (c) 2023 @Zeerats

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

