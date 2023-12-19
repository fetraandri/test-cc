## Modifications Made

1. **Switch Statement:**
   - Replaced multiple `if-else` statements with a `switch` statement for better readability and maintainability.

2. **Asynchronous Delay:**
   - Replaced the synchronous delay function with an asynchronous delay using `setTimeout` to avoid blocking the event loop.

3. **Reset Cooker Method:**
   - Added a `resetCooker` method to reset cooker variables when removing rice.

4. **Separation of Concerns:**
   - Moved user input handling and processing into separate functions (`handleUserChoice`).

5. **Cleaner Exiting:**
   - Used `process.exit()` to cleanly exit the application when the user chooses to exit.
