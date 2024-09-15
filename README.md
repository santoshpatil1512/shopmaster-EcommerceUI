
# E-commerce Web Application

This is a modern e-commerce web application built using **React** with **Vite** as the build tool. The project includes **TailwindCSS** for styling, and several key libraries to enhance functionality, such as **react-slick** for carousels and **aos** for scroll animations.

## Table of Contents

- [Getting Started](#getting-started)
- [Features](#features)
- [Scripts](#scripts)
- [Dependencies](#dependencies)
- [Development](#development)

## Getting Started

### Prerequisites

Ensure that you have Node.js and npm installed on your machine. If not, download and install from [Node.js](https://nodejs.org/).

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/santoshpatil1512/shopmaster-EcommerceUI.git
   ```

2. **Navigate to the project folder**:

   ```bash
   cd 11_ecommerce_web
   ```

3. **Install the dependencies**:

   ```bash
   npm install
   ```

### Running the Application

After installing the dependencies, you can run the application in development mode:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` by default.

### Building for Production

To create a production-ready build, run:

```bash
npm run build
```

This will output the production files in the `dist/` folder.

### Preview the Production Build

To preview the build locally:

```bash
npm run preview
```

## Features

- **React**: A modern JavaScript library for building user interfaces.
- **Vite**: A fast and lightweight build tool.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.
- **AOS (Animate on Scroll)**: Library to animate elements when they scroll into view.
- **React Slick**: A carousel component for React.
- **Slick Carousel**: For slick carousels and sliders.
- **ESLint**: Code linting with a focus on React best practices.

## Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the app for production.
- `npm run preview`: Previews the production build locally.
- `npm run lint`: Lints the codebase with ESLint.

## Dependencies

### Main Dependencies

- `react`: ^18.2.0
- `react-dom`: ^18.2.0
- `aos`: ^2.3.4
- `react-slick`: ^0.29.0
- `slick-carousel`: ^1.8.1
- `react-icons`: ^4.12.0

### Development Dependencies

- `@vitejs/plugin-react`: ^4.2.1
- `tailwindcss`: ^3.4.0
- `eslint`: ^8.55.0
- `eslint-plugin-react`: ^7.33.2
- `vite`: ^5.0.8

## Development

This project follows a modular structure with React components and TailwindCSS for styling. You can easily customize or extend the features using the following tools:

- **React Components**: Components are created using modern hooks and functional components.
- **TailwindCSS**: All styling is done with Tailwind classes. You can modify the `tailwind.config.js` file to customize the theme and extend Tailwind features.
- **ESLint**: Linting is configured with React-specific plugins to ensure best practices.

Feel free to contribute to this project or use it as a base for your own e-commerce platform.

## License

This project is private and not licensed for public use.
