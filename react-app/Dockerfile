FROM node

WORKDIR /app

COPY . .
RUN npm i

# EXPOSE [Port you mentioned in the vite.config file]
EXPOSE 5173

CMD ["npm", "run", "dev"]
