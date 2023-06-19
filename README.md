# Company_Employee_RESTAPI

Get Started

# Introduction about the project

This project regards the Django Rest Framework. Using Django, I can create an API app called "Companies Data Management Application." With this application, 
I can add companies and employees and then check the number of registered companies and the number of employees in a particular company, among other things.
# Here is the some link for helping you check the data.

http://127.0.0.1:8000/api/v1/companies/

http://127.0.0.1:8000/api/v1/companies/1/

http://127.0.0.1:8000/api/v1/companies/1/employees/

# How to SETUP this project.
 
#### Windows

3. **Create and activate a virtual environment**
```python
python -m venv .venv
.venv\Scripts\activate
```

4. **Install dependencies**  
```python
python3 -m pip install --upgrade pip && pip3 install -r requirements.txt
```

5. **Run the server locally**  
```python
python3 manage.py runserver
```

#### macOS/ Linux

3. **Create and activate a virtual environment**
```python
python -m venv .venv
source .venv/bin/activate
```

**or **

```python
sudo apt-get install -y python3.10-venv
python3.10 -m venv <name og the env: .venv >
source .venv/bin/activate
```

4. **Install dependencies**
```python
python3 -m pip install --upgrade pip && pip3 install -r requirements.txt
```
5. **Run the Django server**
```python
python or python3 manage.py runserver
```

# create django project by using this command below:
```python -m pip install django```

```django-admin startproject <project-name>```
 
  ```cd <project-name>```
  
```python manage.py startapp <appname>```
  
  ```return s.no:5 (Run the Django server)```
