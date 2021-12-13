# go-grpc

compile proto: protoc --go_out=. *.proto
run: 
	run service-garage: go run services/service-garage/main.go 
	run service-user: go run services/service-user/main.go 
	run client: go run client/main.go 
src: [Novalagung](https://dasarpemrogramangolang.novalagung.com/C-30-golang-grpc-protobuf.html)
