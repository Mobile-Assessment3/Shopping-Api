# Shopping-Api


1. Set up a Virtual Environment
   # On Linux or macOS (use sudo)
    - Create a virtual environment yourenvName
    - python3 -m venv yourenvName
  # On window
   - Create a virtual environment yourenvName
   - python3 -m venv yourenvName

  # Activate the virtual environment
   - source yourenvName/bin/activate

2. Requirements
- (Database) Postgres latest
- Python version 3.11.7
- (Programming) Python 3.11.7
- (Web framework) Django 5.0.2

3. Install project requirement
   - pip install -r requirements/base.txt
     
4. Run the project
   - python manage.py migrate
   - python manage.py runserver
   - Visit http://127.0.0.1:8000/api in your web browser or a tool like 
  
