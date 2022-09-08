# go-stac-api-postgres  
### a STAC api written in go with fiber, gorm and postgres   
-------
### PROGRESS:  
- Sep.4/2022 - only collection CRUD routes are working at this time   
- Sep.5/2022 - item CRUD routes added 
- added item collection route/logic (still needs better formatting) 
- added /search route and search collections
- Sep.7/2022 - import env variables

### TODO: 
- Search route functionality, geospatial queries
- add swagger docs  
- add tests!  
  
### RUN LOCALLY (localhost:6002):  
- Public postman collection docs available here: https://documenter.getpostman.com/view/12888943/VVBXwQnu

```$ make database```  
```$ go build```  
```$ go run app.go```  
   