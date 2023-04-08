# baypets
-------------


1. Initialize and activate a virtualenv:
```
cd baypets/
python -m venv .venv
source .venv/bin/activate
```

2. Install the dependencies:
```
.venv/bin/pip install -r requirements.txt
```

3. Run the development server:
```
export FLASK_APP=app
flask db init
flask db migrate
```
4. Run the development server:
```
export FLASK_APP=app
export FLASK_ENV=development
.venv/bin/python3 app.py
```

5. Navigate to Home page [http://127.0.0.1:5062/](http://127.0.0.1:5062/)


## deploying it on Heroku

```bash
heroku create bay-pets

git push heroku main
```

Open up [https://bay-pets.herokuapp.com/](https://bay-pets.herokuapp.com/)
or [bay-pets.com](bay-pets.com)
