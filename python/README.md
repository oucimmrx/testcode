# python3
https://www.python3.org/

# requires
pip3  
https://pip3.pypa.io/en/stable/

# To run the code
open the terminal and execute the following commands
> python3 -m venv env  
source env/bin/activate  
python3 -m pip install --upgrade pip  
which python3  
which pip3  
python3 --version  
pip3 --version  
pip3 install -r requirements.txt  
rm -fr config
rm -f manage.py  
django-admin startproject config .  
python3 manage.py runserver  

sample output
> October 21, 2020 - 22:58:39  
Django version 2.1, using settings 'config.settings'  
Starting development server at http://127.0.0.1:8000/  
Quit the server with CONTROL-C.  

browse to the url listed in the output and you should see the django web page  
  
to exit your virtual environment execute this on the terminal
> deactivate  

