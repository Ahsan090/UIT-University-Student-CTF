FROM ubuntu:22.04
RUN apt-get update && apt-get install -y python3-pip
RUN pip3 install transformers==4.30 torch --no-cache-dir
COPY bot.py /root/
ENTRYPOINT ["python3","/root/bot.py"]