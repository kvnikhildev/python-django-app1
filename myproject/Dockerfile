# base iamge
FROM python:3

#workdir
WORKDIR /app

#copy requirements 
COPY requirements.txt ./

#install requirements
RUN pip install -r requirements.txt


#copy all files
COPY . .

#run app
CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000" ]





