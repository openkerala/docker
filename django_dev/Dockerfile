FROM mcheriyath/django_base
MAINTAINER mithun@openkerala.com

RUN mkdir /application

VOLUME ["/application"]

EXPOSE 8000

WORKDIR /application

CMD ["/usr/bin/python", "manage.py","runserver","0.0.0.0:8000"]
