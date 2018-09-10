# flask-rest-setup
Notes on Flask REST API and tutorial

[Flask RESTful Documentation](http://flask-restful.readthedocs.io/en/latest/)
[Flask-CORS](https://flask-cors.readthedocs.io/en/latest/)
___

## Setup

`pip install flask-restful`

Run the Flask API locally for testing. Go to directory with app.py.
python app.py

In a new terminal window, use HTTPie to make a GET request at the URL of the API.
http http://127.0.0.1:5000/ query=="That was pretty entertaining"

3. Example of successful output.
![image01](https://github.com/eddiecityu/Sentiment-Classifier-as-REST-API/blob/master/image/flask-rest-setup_output2.JPG) 

4. Another example of query "that movie was boring"
![image02](https://github.com/eddiecityu/Sentiment-Classifier-as-REST-API/blob/master/image/flask-rest-setup_output.JPG) 

Deploying the Flask app on an EC2 instance.

Appendix
Virtual Environment

1. Create new virtual environment
cd ~/.virtualenvs
virtualenv name-of-env

2. Activate virtual environment
source env/bin/activate

3. Go to app.py directory where requirements.txt is also located
Install required packages from requirements.txt
4. pip install -r requirements.txt
You will only have to install the requirements.txt when working with a new virtual environment.
