# my_paas_app
Open Google Cloud Shell
(Visit: https://shell.cloud.google.com)

git clone https://github.com/Saniya-Bhosale/my_paas_app.git
cd my_paas_app
(Optional) Install dependencies locally for testing

pip install -r requirements.txt
python3 main.py
⚠️ You'll only see output in the shell — this step is just for local test, not required for App Engine deployment.

Deploy to App Engine (PaaS)
gcloud app deploy
When prompted for region, choose: asia-south1 (Mumbai)

Open the deployed app
gcloud app browse
🔎 After Deployment
https://my-paas-app-xxxxx.ew.r.appspot.com/
And that’s it! Your app should display:
Hello from Google Cloud PaaS!
And show an alert saying: "Running on PaaS!"
