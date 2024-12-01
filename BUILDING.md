# Building EduPlanner Development Environment

**EduPlanner** is a web application built using **React** and **Next.js**. This guide will walk you through the process of setting up your local development environment to start working on EduPlanner.

### Prerequisites

To get started, ensure you have the following software installed on your machine:

* **[Node.js](https://nodejs.org/en/)** v20.x.x or higher
* **[PNPM](https://pnpm.io/fr/installation)** v9.14.x or higher (optional but recommended for development)
* **[Git](https://git-scm.com/)** for version control
* **[Visual Studio Code](https://code.visualstudio.com/)** (optional but recommended for development)

### Installing Dependencies

1. **Clone the repository**

Start by cloning the **EduPlanner repository** to your local machine:

```bash
git clone https://github.com/afi-dev/eduplanner.git
cd eduplanner
```

2. **Install Node.js dependencies**

Use **PNPM** to install all necessary dependencies:

```bash
pnpm install
```

This will download all the required packages for running and building EduPlanner.

### Setting Up the Development Environment

Once the dependencies are installed, you're ready to set up your local development environment. Here's how you can run EduPlanner locally.

1. **Start the development server**

   Run the following command to start the development server:

```bash
pnpm run dev
```

This will start a local NextJS server on `http://localhost:3000`. Open this URL in your browser to see EduPlanner in action.

This will keep the development server running and automatically refresh the page when any changes are made.

### Building for Production

Once you're satisfied with your changes and ready to prepare for production, you'll need to build the project for deployment. To generate a production build, use:

```bash
pnpm run build
```

This will create an optimized production version of the application. The compiled files will be located in the `/.next/` directory.

### Running the Application in Production Mode

If you want to run the application in a production-like environment locally to test the built version, use:

```bash
pnpm exec next start
```

This will start a production server that serves the optimized build.

### Conclusion

Now you have everything set up to start developing with EduPlanner. You can modify the code, add new features, and test everything locally. When you're ready to share your changes, remember to commit and push them to the GitHub repository.
