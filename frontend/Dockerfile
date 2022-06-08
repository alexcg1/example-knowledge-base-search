FROM jinaai/jina:3.4.11-py39-standard

COPY . /workspace
WORKDIR /workspace

RUN pip install -r requirements.txt

EXPOSE 8701

ENTRYPOINT ["streamlit", "run"]
CMD ["frontend.py"]
