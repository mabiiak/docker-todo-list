FROM node:14-alpine
WORKDIR /usr/src
EXPOSE 3001
COPY . .
ADD ./node_modules.tar.gz ./
CMD ["npm", "start"]
