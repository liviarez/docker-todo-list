FROM node:16-alpine

WORKDIR /app/front-end

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

ENV PORT=3000

ENTRYPOINT [ "npm" ]

CMD [ "start"]
