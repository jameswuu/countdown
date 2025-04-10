# Custom Countdown Timer
A customizable countdown timer built with HTML, CSS, and JavaScript. This project allows users to set a custom countdown duration, pause and resume the timer, reset the timer, and clear all settings. Additionally, it tracks and displays previous countdown records along with their timestamps.

## Features
- **Customizable Countdown**: Users can input hours, minutes, and seconds to set a custom countdown duration.
- **Pause/Resume**: The countdown can be paused and resumed using the "Start" button.
- **Reset**: Resets the countdown to its original duration.
- **Clear**: Clears all input fields and resets the timer.
- **Record Keeping**: Tracks and displays previous countdown records.

## Usage
1. **Set Countdown Duration**: Enter hours, minutes, and seconds in the input fields.
2. **Start Countdown**: Click the "Start" button to begin the countdown. This button also serves as a pause button.
3. **Reset Countdown**: Click the "Reset" button to reset the countdown to its original duration.
4. **Clear All**: Click the "Clear" button to clear all input fields and reset the timer.

## Technical Details
- **Frontend**: Built using HTML for structure, CSS for styling, and JavaScript for functionality.
- **Countdown Logic**: Implemented using `setInterval` to decrement time every 10 milliseconds for precise timing.
- **Record Tracking**: New records are appended to the top of the historical records table each time a countdown is started.

## Future Enhancements
- **Save Records Locally**: Implement local storage to save historical records even after page reload.
- **Enhanced UI**: Improve user interface with more intuitive design elements and responsive layout.
- **Additional Features**: Consider adding features like countdown alerts or notifications.