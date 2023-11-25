# REST-APIs-with-the-Django-REST-Framework
using decorators in Django to add CRUD functionality

Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/django-task-manager.git
   cd django-task-manager
Install dependencies:
pip install -r requirements.txt

Apply migrations:
python manage.py migrate

Run the server:
python manage.py runserver

The application will be accessible at http://127.0.0.1:8000/.

Usage

API Endpoints

API Overview: /api/
Provides an overview of available API endpoints.

Task List: /api/task-list/
Returns a list of all tasks.

Task Detail: /api/task-detail/<str:pk>/
Returns details of a specific task.

Create Task: /api/task-create/
Creates a new task.

Update Task: /api/task-update/<str:pk>/
Updates an existing task.

Delete Task: /api/task-delete/<str:pk>/
Deletes a task.

Examples of API Usage

Sample requests can be found in the examples/ directory.
