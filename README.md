# docker-typescript
Typescript learning project

## Setup
Run next commands:
```
docker-compose build
docker-compose up -d
```
* Configure typescript:
```
npx tsc --init
```
* Compile code:
```
npm run build, OR
docker exec -it typescript npm run build
```

* Run the server (DEV):
```
npm run dev, OR 
docker exec -it typescript npm run dev
```
