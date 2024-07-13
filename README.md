## mgo

Mgo is based on the official library [mongo](https://github.com/mongodb/mongo-go-driver).

<br>

### Example of use

```go
import "github.com/hanwenbo/mgo"

// connect mongodb
db, err := mgo.Init("mongodb://root:123456@192.168.3.37:27017/account")

// close mongodb
defer Close(db)
```


### Publish

```bash
git tag v1.0.6
git push origin v1.0.5
```

### Install
```bash
go get github.com/hanwenbo/mgo@lastest
// update
go get -u github.com/hanwenbo/mgo@lastest

// or 
go get -u github.com/hanwenbo/mgo@v1.0.5
```