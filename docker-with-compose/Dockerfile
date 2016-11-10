FROM docker:latest

RUN apk add --no-cache \
                py-pip

RUN pip install docker-compose \
        && docker-compose -v

ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["sh"]
