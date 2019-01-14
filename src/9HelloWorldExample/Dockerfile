FROM python:3.5
RUN pip install Flask==0.11.1
RUN useradd -ms /bin/bash admin
USER admin
WORKDIR /app
COPY ../9/Containerize_a_Simple_Hello_World_Web_Application/dockerapp/app /app
CMD ["python", "app.py"] 
