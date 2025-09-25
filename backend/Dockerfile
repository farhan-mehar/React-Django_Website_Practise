FROM node:20
WORKDIR /app
COPY . .
RUN npm install
ENV PORT=5000
EXPOSE 5000
CMD ["node", "src/server.js"]
