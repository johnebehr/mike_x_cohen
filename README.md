<div style="text-align:center">
<h1>Math With Mike X. Cohen</h1>
<h2>Udemy Math Stuff With Mike X. Cohen</h2>
</div>
<hr style="border: 3px solid #393e46; width:70%; margin:0 auto;">

### Setting up the Python Environment
- ```bash
  $ # Create the Python Virtual Environment
  $ python3.9 -m venv .venv
  $ # Activate the Virtual Environment
  $ source .venv/bin/activate
  $ # Update/Upgrade Pip, Setuptools, & Wheel 
  $ python -m pip install --upgrade pip setuptools wheel
  $ # Installing Math dependencies
  $ python -m pip install autopep8 pylint pytz python-dateutil numpy sqlalchemy scipy sympy xlsxwriter matplotlib pymysql pandas ipykernel jupyter
  $ # Make the virtual environement IPython Kernel available to Jupyter 
  $ python -m ipkernel install --user --name=.venv
  $ # Document your Python libriary installations
  $ python -m pip freeze > requirements.txt
  ```