# Space Duck Studio Website

## Activating virtual environment
Before working on project, in Git Bash:
```bash
.venv/Scripts/activate
```

Load flask app by going into /app, running command:
```bash
python -m flask --app main run
```

## Tech stack
- Vue.js frontend framework
- Flask backend framework
- Firebase NoSQL database

## File structure
```bash
sds-website
├───.venv ---------------- virtual environment directory
├───app ------------------ python files
├───static --------------- static files
│   ├───css
│   ├───js
│   └───media
└───templates ------------ html templates
    ├───blocks
    └───components
```