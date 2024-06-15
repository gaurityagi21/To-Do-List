# To-Do List App

## Testing Instructions

1. **Start the Application**:
   - Run `npm start` in your terminal to start the development server.
   - Open your browser and go to `http://localhost:3000` to view the app.

2. **Add a Task**:
   - Enter a task in the input field and click "Add Task".
   - Verify that the task appears in the list below.

3. **Complete and Undo Task**:
   - Click the "Complete" button next to a task to mark it as completed.
   - Click "Undo" to unmark the task as completed.

4. **Filter Tasks**:
   - Use the filter dropdown to select "Active", "Completed", or "All".
   - Ensure the task list updates according to the selected filter.

5. **Sort Tasks**:
   - Use the sort dropdown to choose "Ascending" or "Descending".
   - Verify that tasks are sorted correctly.

6. **Persistence Check**:
   - Close and reopen the app. Ensure that added tasks persist in the list.

## Notes
- The app uses localStorage to save tasks. Ensure your browser settings allow localStorage access.
