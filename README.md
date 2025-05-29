# Fancy Counter React

A simple and interactive counter app built with React and Vite. The counter can be incremented or decremented using buttons, reset to zero, and also incremented with the spacebar. When the counter reaches 5, it becomes "locked" and disables further increments.

## Features

- Increment and decrement the counter using buttons
- Reset the counter to zero
- Increment the counter with the spacebar key
- Counter locks at 5 and disables further increments
- Visual feedback when the counter is locked

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/fancy-counter-react.git
   cd fancy-counter-react
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

### Running the App

Start the development server:
```sh
npm run dev
# or
yarn dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

## Project Structure

```
src/
  ├── App.jsx
  ├── Card.jsx
  ├── Title.jsx
  ├── Count.jsx
  ├── ResetButton.jsx
  ├── ButtonContainer.jsx
  ├── CountButton.jsx
  └── ...
```

## Usage

- Click the "+" or "-" buttons to change the counter.
- Press the spacebar to increment the counter.
- Click "Reset" to set the counter back to zero.
- When the counter reaches 5, it locks and disables further increments.

## License

This project is licensed under the MIT License.
