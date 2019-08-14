FROM debian:10-slim

RUN apt-get update && apt-get install -y cron && rm -rf /var/lib/apt/lists/*

CMD ["/usr/sbin/cron", "-f"]
