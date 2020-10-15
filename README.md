# Inventory REST API

##Requirements
Python : 3+ version\
Flask\
Flask-RESTful\
Flask-SQLAlchemy\
Flask-SQLAlchemy\
maya==0.6.1\
pymysql\
Python-dotenv\
marshmallow\
pytz\
flask-Uploads

##Implementation
this REST API is implemented using Flask and Flask_SQLALchemy.this API is inventory management api.in this inserting,updating,deleting and fetching operation are available.

Note:install requirements.txt using pip install -r requirements.txt command.\
if ImportError: from werkzeug import secure_filename, FileStorage. occurred\
then do following changes\
in flask_uploads.py change from werkzeug.utils import secure_name and\
from werkzeug.datastructures import FileStorage 

