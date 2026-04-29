FROM node

RUN mkdir arFrontend
WORKDIR /arFrontend

COPY . .

RUN npm install --legacy-peer-deps
RUN npm install @fortawesome/fontawesome-svg-core @fortawesome/react-fontawesome --save

CMD ["npm", "run", "dev", "--", "--host"]
