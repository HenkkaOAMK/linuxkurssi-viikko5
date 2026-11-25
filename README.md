# Week 5 - LLM-Chat to cPouta

This is my Week 5 assignement for Linux course.

The idea was to create a Python web application using Flask + Gunicorn, where user can chat with a language moidel through a web page.
Application runs locally on my own server. I used my existing cPouta Server to do this. In this work I used my A server, not the one I made last week where database 
is read-only replica.

Messages are stored in MariaDB and conversations stay visible after reloading the page.

Application is deployed automatically to my cPouta server using GitHub Actions and SSH.

Applications used:
- Flask
- Gunicorn
- Nginx
- MariaDB
- Ollama
- GitHub Actions

Files:
- app.py
- db.py
- test_app.py
- scritps/server-setup-sh
- scripts/deploy.sh
- deploy/nginx/chatapp.conf
- deploy/systemd/chatapp.service


Passwords, private keys and other secrets are not stored in this repository.
