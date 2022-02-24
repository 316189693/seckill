1. 解决问题 go get
问题：
go get: module github.com/jmoiron/sqlx: Get "https://proxy.golang.org/github.com/jmoiron/sqlx/@v/list": dial tcp 142.250.157.141:443: connectex: A connection attempt failed because the connected party did not properly respond after a period of time, or established connection failed because connected host has failed to respond.
解决办法：
go env -w GOPROXY=https://goproxy.cn
