FROM node:14-slim
WORKDIR /opt/node-server
# COPY app.js .
# COPY package* .
COPY . .
# packege.json içindeki dependencies' kur
RUN npm install  
CMD ["node","app.js"]
