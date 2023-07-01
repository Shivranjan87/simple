# my-simple-webapp
my-simple-webapp is a web application build using python - flask framework.

# installing python on your local ubuntu machine first check if the apt-get command line tool is updated or else run the below command
apt-get update

# now install python package on local ubuntu machine
apt-get install -y python

# now install pip package on local ubuntu machine
apt-get install -y python-pip
or
apt-get install -y pip

# create a local directory named in your local ubuntu machine and change the current working directory to new created directory
root@username:/# mkdir my-simple-webapp
root@SHIVRANJAN:/# cd my-simple-webapp

# create a app.py file in local directory and copy it to desired location
root@username:/my-simple-webapp# cat> app.py
root@username:/my-simple-webapp# cp app.py /opt/app.py

# Starting a web server (now you have installed all the required packages its time to check whether application is running
FLASK-APP=/opt/app.py flask run --host==0.0.0.0

# to test/check whether image is running, open your browser. It will show the message in browser window as mentioned below
http://<IP>:5000                      => Welcome
http://<IP>:5000/how%20are%20you      => I am good, what about you?
