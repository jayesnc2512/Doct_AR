FROM node

RUN mkdir frontend
WORKDIR /frontend

COPY . .

RUN npm install --legacy-peer-deps

CMD [ "npm","start" ]

