# djangoreact
Minimal Django + ReactJS boilerplate

# Running it
1. Install dependencies
```bash
cd $DIR
pipenv install
cd frontend
npm install
```
2. Run Django and React
```
cd $DIR
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
cd frontend
npm start
```
3. Checkout the React app at `localhost:3000`
