FROM node:16-alpine
RUN apk add --update python3 make g++
WORKDIR /api

COPY . .

RUN make

CMD ["node", "build/index.js"]
