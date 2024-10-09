# Django To-Do List with User Authentication Project

This Django project is a simple To-Do List application with user authentication. It allows users to create, update, and delete tasks, as well as mark them as completed or incomplete. User authentication ensures that each user has their own personalized to-do list.

<p align="center">
  <img src="https://github.com/swatimeher1998/Django-Todo-Planner/blob/main/Django-To-Do-planner.png" width="650" height="360" />
</p>

## Features

- **User Authentication**: Users can sign up for an account and log in securely.
- **To-Do List Management**: Users can create new tasks, view existing tasks, update task details, mark tasks as completed or incomplete, and delete tasks.
- **User-specific To-Do Lists**: Each user has their own personalized to-do list, ensuring privacy and organization.
- **Responsive Design**: The application is designed to be responsive and user-friendly across various devices and screen sizes.

## Installation

To run this Django project locally, follow these steps:

1. **Clone the Repository**: 
   ```
   git clone https://github.com/swameher/Django-Todo-Planner.git
   ```

2. **Navigate to the Project Directory**:
   ```
   cd Django-Todo-Planner
   ```

3. **Apply Database Migrations**:
   ```
   python3 manage.py migrate
   ```

4. **Create a Superuser** (Optional, for admin access):
   ```
   python3 manage.py createsuperuser
   ```

5. **Run the Development Server**:
   ```
   python3 manage.py runserver
   ```

6. **Access the Application**:
   Visit `http://127.0.0.1:8000/` in your web browser to access the application.

## Usage

1. **Sign Up / Log In**:
   - If you are a new user, sign up for an account using a valid email address and password.
   - If you already have an account, log in with your credentials.

2. **View Tasks**:
   - Upon logging in, you will be directed to your personalized to-do list page.
   - Here, you can view all your tasks, including completed and incomplete ones.

3. **Add a Task**:
   - Click on the "Add Task" button to create a new task.
   - Enter the task details and click "Submit" to add it to your to-do list.

4. **Update a Task**:
   - To update a task, click on the task name to view its details.
   - Here, you can edit the task description, or status (completed/incomplete).
   - Click "Submit" to update the task.

5. **Mark Task as Completed/Incomplete**:
   - On the task details page, you can mark a task as completed or incomplete by toggling the status.
   - Click "Submit" to apply the changes.

6. **Delete a Task**:
   - To delete a task, click on the task name to view its details.
   - Click on the "Delete" button to remove the task from your to-do list.

7. **Log Out**:
   - Click on the "Log Out" link to securely log out of your account.

## Contributing

Contributions to this Django To-Do List project are welcome! If you encounter any bugs, have feature requests, or want to contribute enhancements, please feel free to submit a pull request or open an issue on the GitHub repository.
