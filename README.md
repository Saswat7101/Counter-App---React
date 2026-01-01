# Behind Scenes Counter App

A modern React-based counter application built with Vite, featuring counter history tracking and configuration options.

## Features

- Increment and decrement counter values
- View counter history
- Configure counter settings
- Responsive UI with custom icons
- Built with React 19 and Vite for fast development

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd react-counter-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Technologies Used

- **React** 19.0.0 - UI library
- **Vite** 4.4.5 - Build tool and dev server
- **Million** 3.1.11 - React optimization library
- **ESLint** - Code linting

## Project Structure

```
src/
├── components/
│   ├── Counter/
│   │   ├── Counter.jsx
│   │   ├── CounterHistory.jsx
│   │   ├── CounterOutput.jsx
│   │   └── ConfigureCounter.jsx
│   ├── UI/
│   │   ├── IconButton.jsx
│   │   └── Icons/
│   │       ├── ArrowRightIcon.jsx
│   │       ├── MinusIcon.jsx
│   │       └── PlusIcon.jsx
│   └── Header.jsx
├── App.jsx
├── main.jsx
├── index.css
└── log.js
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run linting: `npm run lint`
5. Submit a pull request

## License

This project is private and not licensed for public use.
