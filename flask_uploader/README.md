# flask-uploader

Run with "flask run"
or 
"gunicorn -w 4 -b 127.0.0.1:4000 flask_uploader:app"

via https://flask.palletsprojects.com/en/1.1.x/patterns/fileuploads/
and https://www.roytuts.com/python-flask-rest-api-file-upload/

See also: https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-16-04

Upload via curl:
curl --form "file=@filename.png" localhost:8080/file-upload
