FROM node
RUN apt-get update
RUN mkdir api
COPY . /api
EXPOSE 3000
EXPOSE 3001
EXPOSE 3002
CMD ["node", "api/server"]
