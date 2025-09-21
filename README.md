<!-- 
1. Clone the repo
2. add your changes and push
3. open https://dashboard.render.com/
4. click on new > web service 
    - add build command pip install -r requirements.txt
    - add start command as uvicorn api.main:app --host 0.0.0.0 --port 10000
    - add env variables from .env file
5. create postgres from render 
5. add as a poostgres url endpoint in .env file
 -->