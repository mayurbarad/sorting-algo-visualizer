# React + Vite

# Sorting Visualizer

A visual representation of various sorting algorithms implemented in React with Vite.

## Features

- Visualize different sorting algorithms: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort.
- Adjust the speed and length of the array.
- Generate a new random array.
- Watch step-by-step comparisons and swaps.

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have Node.js and npm installed on your machine.

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/mayurbarad/sorting-algo-visualizer.git
    ```

2. Navigate to the project directory:
    ```sh
    cd sorting-visualizer
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

4. Start the development server:
    ```sh
    npm run dev
    ```

5. Open your browser and go to `http://localhost:3000`.

## Project Structure

```plaintext
sorting-visualizer/
├── public/
├── src/
│   ├── algorithms/
│   │   ├── bubbleSort.js
│   │   ├── insertionSort.js
│   │   ├── mergeSort.js
│   │   ├── quickSort.js
│   │   └── selectionSort.js
│   ├── components/
│   │   ├── Bars.js
│   │   └── Navbar.js
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── index.html
├── package.json
└── README.md
