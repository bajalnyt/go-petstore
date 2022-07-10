# Go-Petsore

Swagger generated code for the sample petstore app provided by swagger

### Run server
`go run main.go`


### Invoke API
(uses HTTPie)

`http POST http://localhost:8080/v2/pet Id=2 Category=3`

`http http://localhost:8080/v2/pet/1`

Logs:

```
(main*) $ go run main.go
2022/07/10 19:22:13 Server started
2022/07/10 19:22:54 GET /v2/ Index 19.375µs
2022/07/10 19:23:40 POST /v2/pet AddPet 1.084µs
2022/07/10 19:23:48 GET /v2/pet/1 GetPetById 1.209µs
2022/07/10 19:23:56 POST /v2/pet AddPet 1.125µs
2022/07/10 19:23:59 GET /v2/pet/2 GetPetById 1.375µs
2022/07/10 19:24:01 GET /v2/pet/4 GetPetById 1.292µs
```
