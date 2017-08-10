FROM python:3.6.2
COPY ProxyPool /app/ProxyPool/
COPY pip.conf /root/.pip/
WORKDIR /app/ProxyPool
RUN pip install -r requirements.txt
ENTRYPOINT ["python3"]
CMD ["run.py"]
