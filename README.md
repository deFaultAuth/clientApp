# Signup and login using flask

**To Clone The Repository**
```
$ git clone https://github.com/suyogdahal/flask-signup-login.git
```

**Installation**

Install with pip:

```
$ pip install -r requirements.txt

```
**To run the app**
```
 First change app config "IMAGE_UPLOADS" at app.py to your local folder name
 This is because by using standard Flask stuff, there's no way to avoid saving a temporary file if the uploaded file size is > 500kb. 

$ python app.py 

```

**Sample responce returned by Face++ detectFace API**
```
<FileStorage: 'IMG_4843.jpg' ('image/jpeg')>
the result is:
{'faces': [{'face_rectangle': {'top': 530, 'height': 384, 'width': 384, 'left': 305}, 'attributes': {'gender': {'value': 'Male'}, 'beauty': {'male_score': 76.568, 'female_score': 73.439}, 'age': {'value': 30}, 'smile': {'value': 0.027, 'threshold': 50.0}}, 'face_token': 'dd54e8e5a644ef59b00947d31e13182f'}], 'image_id': 'APB9a/HlFFDDtIH2Trjw7w==', 'time_used': 185, 'request_id': '1597110637,7b97e2e3-4d72-4a90-8dab-292ea97f0d30', 'face_num': 1}
```
