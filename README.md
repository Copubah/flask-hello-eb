# Flask App on AWS Elastic Beanstalk
- This is a simple Flask web application deployed on [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/), a Platform-as-a-Service (PaaS) that handles deployment, scaling, and monitoring of applications.

## 🧰 Tech Stack

- Python 3.x
- Flask
- AWS Elastic Beanstalk (Python Platform)

##  Project Structure

flask-eb-app/
│
├── application.py # Main Flask application
├── requirements.txt # Python dependencies
└── .ebextensions/
└── python.config # EB configuration


##  Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/Copubah/flask-hello-eb
cd flask-eb-app




2. Set Up the Environment
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

3. Run Locally
python application.py and then visit http://localhost:5000


4. Deploy to Elastic Beanstalk
Install the EB CLI
pip install awsebcli --upgrade

- Configure AWS and Initialize EB
aws configure
eb init -p python-3.8 flask-eb-app


Create and Deploy
- eb create flask-env
eb open

## License
This project is licensed under the MIT License








