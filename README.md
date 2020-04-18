# Running locally
1. docker run --name tutorials-mongo -p 27017:27017 -d mongo:4.2.5
2. cd tutorials 
3. mvn spring-boot:run
4. cd vue-js-client-crud
5. npm run serve

## Frontend
http://localhost:8081/tutorials
## backend
http://localhost:8080/api/tutorials


# Backend
built following https://bezkoder.com/spring-boot-mongodb-crud/

# Frontend 
built following https://bezkoder.com/vue-js-crud-app/