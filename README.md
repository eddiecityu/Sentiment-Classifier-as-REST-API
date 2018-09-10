# flask-rest-setup
Notes on Flask REST API and tutorial

[Flask RESTful Documentation](http://flask-restful.readthedocs.io/en/latest/)
[Flask-CORS](https://flask-cors.readthedocs.io/en/latest/)
___

## Setup

- [x] `pip install flask-restful`

Run the Flask API locally for testing. Go to directory with app.py.
python app.py

In a new terminal window, use HTTPie to make a GET request at the URL of the API.
http http://127.0.0.1:5000/ query=="That was pretty entertaining"

3. Example of successful output.
HTTP/1.0 200 OK
Content-Length: 57
Content-Type: application/json
Date: Tue, 21 Aug 2018 19:04:04 GMT
Server: Werkzeug/0.14.1 Python/3.6.3

{
    "confidence": 0.78,
    "prediction": "Positive"
}
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
