1. Activate virtual environment before working on/running project 
   (if working in a new directory w/o venv installed, run "py -3 -m venv venv" first)
	a. run command ". venv/Scripts/activate"
	b. To exit virtual environment, run command "deactivate"
2. For a new venv, run "pip install -r requirements.txt"
   (if that doesn't work, "pip install Flask" and the rest of the list in requirements)

3. To run the flask application, execute:
	a. "export FLASK_APP=application.py"
	b. "flask run"
   Once server is running, type "localhost:5000" in web browser.
