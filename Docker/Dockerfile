FROM continuumio/anaconda3:4.4.0
COPY ./all_folder /usr/local/python
EXPOSE 5000
WORKDIR /usr/local/python
RUN pip install -r requirements.txt
CMD python app3.py