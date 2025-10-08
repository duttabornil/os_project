# Simple Kitchen Scheduler

A basic, client-side visualizer for a first-in, first-out (FIFO) task queue, using a simple kitchen theme. It's built with HTML, CSS, and JavaScript.

## Description

This project demonstrates a minimal task queue system using a kitchen metaphor. Dishes are added to an orders queue and cooked sequentially, with visual feedback showing the current state of each order.

## Features

- **Add Dishes**: Create orders with a custom dish name and cooking time (in seconds)
- **FIFO Queue Processing**: Dishes are cooked in the order they are added
- **Real-time Countdown**: Watch dishes cook with a live countdown timer
- **Three-State Display**: 
  - **Orders Queue**: Dishes waiting to be cooked
  - **Now Cooking**: The dish currently being prepared with countdown timer
  - **Completed Dishes**: Finished dishes with checkmarks
- **Kitchen Controls**:
  - **Start Cooking**: Begin preparing dishes from the queue
  - **Reset**: Clear all lists and stop the cooking process
- **Responsive Design**: Works on desktop and mobile devices

## How to Run

1. Download the `index.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No installation or server setup required!

## Usage

1. **Add a Dish**:
   - Enter a dish name (e.g., "Spaghetti Carbonara")
   - Set the cooking time in seconds (e.g., 5)
   - Click "Add Dish"

2. **Start Cooking**:
   - Once you've added one or more dishes, click "Start Cooking"
   - Watch as dishes move from "Orders Queue" to "Now Cooking" to "Completed Dishes"

3. **Reset Everything**:
   - Click "Reset" at any time to clear all dishes and stop the cooking process

## Technical Details

- **Frontend**: Pure HTML5, CSS3, and Vanilla JavaScript (ES6+)
- **No Dependencies**: Single self-contained file
- **Browser Compatibility**: Works in all modern browsers
- **Architecture**: Object-oriented JavaScript with a TaskScheduler 
