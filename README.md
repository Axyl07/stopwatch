# Stopwatch

A simple React-based stopwatch application that allows users to start, stop, and reset a timer with millisecond precision.

## Features
- Start the stopwatch
- Stop the stopwatch
- Reset the stopwatch
- Displays time in HH:MM:SS:MS format
- Uses React hooks (`useState`, `useEffect`, `useRef`) for state management

## Technologies Used
- React
- JavaScript
- HTML & CSS

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/stopwatch.git
   ```
2. Navigate to the project directory:
   ```sh
   cd stopwatch
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```

## Usage
1. Click the **Start** button to begin timing.
2. Click the **Stop** button to pause the stopwatch.
3. Click the **Reset** button to reset the time to `00:00:00:00`.

## Code Explanation
- `useState` is used to manage the stopwatch state (`isRunning` and `elapsedTime`).
- `useRef` is used to store the interval ID and start time without triggering re-renders.
- `useEffect` handles the timer updates and clears the interval when the stopwatch stops.
- The `formatTime` function ensures the time is displayed in a human-readable format.

## Contributing
Feel free to fork the repository and submit pull requests for improvements!


