# Dockerimage
1)
   Install all required dependencies 
   Python and its dependencies 
apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb

2)
  Install and configure web server
  
  pip install flask
  pip install flask-mysql
  
copy app.py or download it from source repository 
configure database credentials and parameters

3)
  Start Web Server
  
  FLASK_APP:app.py flask run --host=0.0.0.0
  
 4)
  Test
  Open a browser and go to URL
  http://5000                          => Welcome
  
  http://<ip>:5000/how%20are%20you     => I am good, how about you?
  
  
  
