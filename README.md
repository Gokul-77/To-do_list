# To-Do List

A simple To-Do List web application built with **Django** and **Bootstrap**. This application allows users to create, update, and delete tasks, providing a basic yet functional interface for task management.



## Features

* **Create Tasks**: Add new tasks to your to-do list.
* **Update Tasks**: Mark tasks as completed or modify them.
* **Delete Tasks**: Remove tasks from the list when no longer needed.
* **Responsive Design**: The app is built using **Bootstrap**, making it responsive across different devices.
* **Interactive UI**: Tasks can be struck through when completed, providing a clear distinction between completed and pending tasks.

## Technologies Used

* **Django**: The back-end framework for building the application.
* **Bootstrap**: The front-end framework for styling and responsiveness.
* **HTML/CSS**: Markup and styling for the app.
* **JavaScript**: For additional interactivity, if needed (optional based on further requirements).
* **SQLite**: The default database for storing tasks (you can switch to other databases like PostgreSQL or MySQL if needed).

## Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/Gokul-77/To-do_list.git
```

### Step 2: Navigate into the project directory

```bash
cd To-do_list
```

### Step 3: Set up a virtual environment (optional but recommended)

```bash
python -m venv venv
```

### Step 4: Activate the virtual environment

* On Windows:

  ```bash
  venv\Scripts\activate
  ```

* On macOS/Linux:

  ```bash
  source venv/bin/activate
  ```

### Step 5: Install the required dependencies

```bash
pip install -r requirements.txt
```

### Step 6: Apply database migrations

```bash
python manage.py migrate
```

### Step 7: Create a superuser (to access the Django admin panel)

```bash
python manage.py createsuperuser
```

### Step 8: Run the development server

```bash
python manage.py runserver
```

You can now access the app in your browser at `http://127.0.0.1:8000/`.

## Usage

1. Open the app in your browser.
2. Add tasks to your to-do list.
3. You can update tasks by clicking the "Update" button or delete them using the "Delete" button.
4. Completed tasks will be visually marked with a strike-through.

## Folder Structure

```
/task
    /to_do_list
        /migrations
        /templates
            /to_do_list
                base.html
                index.html
        /static
            /css
            /images
        /views.py
        /models.py
        /urls.py
        /forms.py
    /venv
    manage.py
    requirements.txt
    README.md
```
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
