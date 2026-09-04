## How to run project

1. Create virtual env
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Apply migrations
```bash
python manage.py migrate
```
4. Run the server
```bash
python manage.py runserver
```

## Endpoints
### Hello
- / - h
- fancy-hello/ - better hello (with header)
- \<str:name\>/ - personal greeting

### ToDoList
- todolist/ - list of tasks
- todolist/add/ - add new task