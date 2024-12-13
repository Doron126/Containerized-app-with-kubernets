# Flask Simple API

This is a simple Flask API to manage tasks.

## Endpoints
- `GET /tasks`: Retrieve all tasks.
- `POST /tasks`: Add a new task. Requires `{"name": "Task Name"}` in the request body.
- `PUT /tasks/<task_id>`: Update a task by ID. Requires `{"name": "Task Name", "done": true}` in the request body.
- `DELETE /tasks/<task_id>`: Delete a task by ID.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the app: `python app.py`
