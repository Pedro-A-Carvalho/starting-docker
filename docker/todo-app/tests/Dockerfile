FROM betrybe/puppetter:1.0
WORKDIR /app/tests
ADD node_modules.tar.gz /app/tests/
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "test" ]
