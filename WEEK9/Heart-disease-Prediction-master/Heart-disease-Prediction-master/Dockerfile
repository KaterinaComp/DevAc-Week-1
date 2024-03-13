FROM python:3.8-slim


WORKDIR /heart_model

COPY . /heart_model/


RUN pip install -r requirements.txt

## expose our container to ...
## default port for streamlit is 8501

EXPOSE 8501


CMD ["streamlit","run","heart_model.py"]


## docker build -t heart_pred


