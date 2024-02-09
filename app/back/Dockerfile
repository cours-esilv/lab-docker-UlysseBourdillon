FROM python:3.10
COPY . /back
WORKDIR /back
RUN pip install -r requirements.txt
ENV CURRENT_ENVIRONMENT=production
CMD ["python3" , "-m" ,"flask", "run", "--host=0.0.0.0"]

