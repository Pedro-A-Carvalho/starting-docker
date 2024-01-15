FROM node:16-alpine
EXPOSE 3001
WORKDIR /app/back-end
ADD node_modules.tar.gz /app/back-end/
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]