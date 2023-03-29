FROM debian
RUN apt update
RUN apt install apache2 -y
RUN service apache2 start
EXPOSE 80
CMD service apache2 start && tail -F /var/log/apache2/error.log
