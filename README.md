# Conversor de Moedas 💱

A currency converter web app built with TypeScript that converts between currencies using live exchange rates.

## Features
- Convert between multiple currencies
- Real-time exchange rates
- Clean, responsive interface

## Tech Stack
- **TypeScript** — core conversion logic
- **Vite** — dev server and build tooling
- **HTML & CSS** — interface and styling

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) installed

### Installation
```bash
# Clone the repository
git clone https://github.com/fe-bg/Conversor-de-Moedas.git

# Navigate into the project
cd Conversor-de-Moedas

# Install dependencies
npm install
```

### Running the app
```bash
# Start the development server
npm run dev
```
This starts the Vite dev server and prints a local URL (usually **http://localhost:5173**). Open it in your browser — the page reloads automatically as you edit files.

To stop the server, press **Ctrl + C** in the terminal.

### Building for production
```bash
# Compile TypeScript and bundle into the dist/ folder
npm run build

# Preview the production build locally
npm run preview
```

## How it works
The app takes an amount and a source/target currency, fetches the current exchange rate, and displays the converted value. The conversion logic is written in TypeScript for type safety.

## Roadmap / Ideas
- [ ] Add a currency-swap button
- [ ] Show recent conversion history
- [ ] Support more currencies

## Author
**Felipe Beledelli**
- GitHub: [@fe-bg](https://github.com/fe-bg)
- LinkedIn: [in/felipebeledelli](https://www.linkedin.com/in/felipebeledelli)
