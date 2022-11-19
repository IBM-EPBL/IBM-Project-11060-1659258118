FROM python

WORKDIR /inventory

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

EXPOSE 8080

CMD ["python", "-m" , "flask", "run", "--host=0.0.0.0"]
#WORKDIR /inventory


#RUN apt-get update
#RUN mkdir /app
#WORKDIR /app
#COPY . /app
#RUN pip install -r requirements.txt
#EXPOSE 5000
#ENTRYPOINT [ "python" ]
#CMD [ "app.py" ]
##COPY requirements.txt requirements.txt
##RUN pip install -r requirements.txt
##
##COPY . .
##
##EXPOSE 8080
##
##CMD ["python", "-m" , "flask", "run", "--host=0.0.0.0"]

