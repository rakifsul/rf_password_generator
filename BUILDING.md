cd rf_password_generator

python -m venv venv

venv/Scripts/activate

pip install -r requirements.txt

pip install pyinstaller

python App.py

pyinstaller --noconsole --icon=.\icon.ico --name=rf_password_generator App.py
