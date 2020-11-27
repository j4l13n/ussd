# USSD APP (Africa's Talking APIs)

This is to test USSD app using Africa's talking USSD API and django


### Run the application

```
$ python3 -m venv ./venv/
$ pip install -r requirements.txt
$ python manage.py runserver
```

### Ngrok was used for the callback url

Install Ngrok and run it on the same port Django url uses

```
./ngrok http 8000
```
use the given link as your callback url
