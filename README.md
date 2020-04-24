sudo apt install python3-pip
cd Downloads/weather_detector
python3 -m venv venv
source venv/bin/activate
pip install flask
pip install flask_sqlalchemy
pip install requests
export FLASK_APP=app.py
flask run 
