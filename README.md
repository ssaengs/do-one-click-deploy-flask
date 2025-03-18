# One-Click Deploy: Flask Chuck Norris Joke API

This is a simple Flask API that fetches a random Chuck Norris joke and returns it as JSON. With **DigitalOcean's One-Click Deploy button**, you can instantly deploy this app in the cloud.

### **How It Works**
- When you visit `/`, the app fetches a random joke from the [Chuck Norris API](https://api.chucknorris.io/).
- Returns the joke as JSON.
- Runs on port **8080**.

### **Repository Structure**
```
do-one-click-deploy-flask/
│── app.py                 # Flask application fetching jokes
│── wsgi.py                # WSGI entry point for deployment
│── requirements.txt       # Dependencies for the Flask app
│── .do/
│   └── deploy.template.yaml  # DigitalOcean deployment configuration
│── README.md              # Project documentation
```

### **Deploy to DigitalOcean**
Click the button below to instantly deploy this app on **DigitalOcean App Platform**:

[![Deploy to DO](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/ajot/do-one-click-deploy-flask/tree/main&refcode=ab3d355caa45)

Or, use your referral link: [https://m.do.co/c/ab3d355caa45](https://m.do.co/c/ab3d355caa45)

### **Running Locally**
```bash
git clone https://github.com/ajot/do-one-click-deploy-flask.git
cd do-one-click-deploy-flask
pip install -r requirements.txt
python app.py
```

### **License**
MIT License