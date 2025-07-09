FROM node:20-alpine

WORKDIR /workspace
COPY . .

RUN npm install -g vite && npm ci

CMD ["npm", "run", "dev"]