# go-validator
gRPC based validator for Golang services

Supported validators
 -- 'required'
   -- applicable for Messages,string,integers
 -- min length, max length, allowed list
   -- applicable for string
 -- min value, max value
   -- applicable for integers

Support for other types and lists,enums,structs to be added.

generate go file from proto with below cmd
  protoc --go_out=plugins=grpc:. pb/valid.proto