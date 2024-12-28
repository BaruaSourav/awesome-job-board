
# Vite + React + Tailwind Playground

This repository is a starter template for building a React application using [Vite](https://vitejs.dev/) and [Tailwind CSS](https://tailwindcss.com/) for styling.

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version 16 or higher recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) (npm is used in this guide)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Development

To start the development server:
```bash
npm run dev
```

This will start the Vite development server. Open your browser and navigate to `http://localhost:5173` (or the URL provided in the terminal).

### Build for Production

To create an optimized production build:
```bash
npm run build
```

The build output will be located in the `dist` directory.

### Preview Production Build

To preview the production build locally:
```bash
npm run preview
```

## Project Structure

```plaintext
├── public/            # Static assets
├── src/
│   ├── assets/        # Images, fonts, etc.
│   ├── components/    # Reusable React components
│   ├── pages/         # Page components
│   ├── App.jsx        # Root component
│   ├── main.jsx       # Entry point
│   └── index.css      # Tailwind imports and global styles
├── .gitignore         # Git ignore rules
├── index.html         # HTML template
├── package.json       # Project metadata and scripts
├── postcss.config.js  # PostCSS configuration
├── tailwind.config.js # Tailwind CSS configuration
└── vite.config.js     # Vite configuration
```

## Customizing Tailwind CSS

Tailwind CSS can be customized via the `tailwind.config.js` file. Learn more in the [Tailwind CSS documentation](https://tailwindcss.com/docs/configuration).

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run preview`: Preview the production build.

## Resources

- [Vite Documentation](https://vitejs.dev/guide/)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## License

This project is licensed under the [MIT License](./LICENSE).

