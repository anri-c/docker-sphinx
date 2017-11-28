FROM python

RUN apt-get update -y && apt-get install -y python-imaging fonts-ipafont && apt-get -y clean
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

