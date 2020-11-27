# USSD APP (Africa's Talking APIs)

This is a USSD app using Africa's talking USSD API and it is built using Django framework


### Run the application

```
$ git clone https://github.com/j4l13n/ussd.git
$ cd ussd
$ python3 -m venv ./venv/
$ pip install -r requirements.txt
$ python manage.py runserver
```

### Ngrok was used for the callback url

Install [Ngrok](https://ngrok.com/download) and run it on the same port Django url uses

```
./ngrok http 8000
```
use the given link as your callback url in Africa's talking system
