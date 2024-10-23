# Quick Tasker

The Quick Tasker is a web application that allows users to manage tasks efficiently. Built with Symfony, it offers an intuitive interface for creating, organizing, and tracking tasks, providing users with productivity tools to manage their workflow.

## Features

- **User Authentication**: User registration, login, and logout.
- **Task Management**: Add, edit, delete, and mark tasks as complete or incomplete.
- **Task Categories**: Organize tasks into different categories for better management.
- **Task Deadlines**: Assign due dates to tasks and highlight overdue tasks.
- **User Dashboard**: Summary of tasks, including filtering by status, priority, or category.
- **Notifications**: Email reminders for upcoming and overdue tasks.
- **Security: Two-factor authentication (2FA)** and password reset functionality.

# Quick Tasker - TODOs

## Version 0.1
- **User Authentication**
    - [ ] Implement authentication system
    - [ ] User registration
    - [ ] User login and logout

- **Basic Task Management**
    - [ ] Create, view, and list tasks.
    - [ ] Task properties: title, description, due date, and status (pending/completed).

- **Dashboard Setup**
    - [ ] Basic user dashboard to display tasks.

## Version 0.2
- **Task Editing and Deletion**
    - [ ] Add functionality to edit tasks.
    - [ ] Add task deletion functionality.

- **Task Categories**
    - [ ] Create task categories (e.g., "Work", "Personal", "Urgent").
    - [ ] Filter tasks by category on the dashboard.
  
- **Task Priorities**
    - [ ] Add a priority system (low, medium, high) to tasks.
    - [ ] Display task priorities on the dashboard.

## Version 0.3
- **Task Deadlines**
    - [ ] Add a deadline field to tasks.
    - [ ] Highlight overdue tasks on the dashboard.

- **Task Sorting and Filtering**
    - [ ] Add sorting options for tasks (by due date, priority).
    - [ ] Filter tasks by status (pending, completed) and priority.
  
- **Dashboard Enhancements**
    - [ ] Improved task overview, showing total tasks, tasks by category, and upcoming deadlines.
    - [ ] Add quick actions to complete or edit tasks from the dashboard.

## Version 0.4
- **User Notifications**
    - [ ] Email reminders for upcoming and overdue tasks.
    - [ ] Allow users to set notification preferences (e.g., frequency of reminders).

- **UI/UX Improvements**
    - [ ] Improve the user interface for better navigation.
    - [ ] Add mobile-responsive design.

## Version 0.5
- **Data Export**
    - [ ] Allow users to export tasks to CSV or Excel.
    - [ ] Add the option to download tasks filtered by status, category, or priority.

- **Security Enhancements**
    - [ ] Implement password reset functionality.
    - [ ] Add two-factor authentication (2FA) for enhanced security.

## Version 1.0
- **Task Reports and Analytics**
    - [ ] Generate detailed reports, such as task completion rates, overdue tasks, and category-based reports.
    - [ ] Monthly/weekly summaries for task progress.

- **Advanced Task Filters**
    - [ ] Add advanced filtering options (e.g., filter by date range, priority, category).
    - [ ] Sorting and grouping options for tasks in different views.

- **Deployment**
    - [ ] Finalize project for production deployment.
    - [ ] Write user manual and deployment guide.


## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/jakuubkoo/Quick-Tasker.git
   cd quick-tasker
   ```
2. Install dependencies:
   ```sh
   composer install
   npm install
   npm run dev
   ```
3. Set up the database:
   ```sh
   php bin/console doctrine:database:create
   php bin/console doctrine:migrations:migrate
   ```
4. Run the server:
   ```sh
   symfony server:start
   ```
5. Access the application:
   ```sh
   Open your web browser and navigate to `http://localhost:8000`
   ```

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests for any features, bug fixes, or enhancements.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.
