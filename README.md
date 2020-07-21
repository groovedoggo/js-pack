1. package.json
2. npm install
3. index.js

docker build --build-arg APP_DIR=var/app -t ankitjain28may/node-app:V1 .
docker run -p 8000:3000 -d --name node-app ankitjain28may/node-app:V1
