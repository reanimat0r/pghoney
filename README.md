# pghoney

A simple Postgres honey pot inspired by [Elastichoney](https://github.com/jordan-wright/elastichoney)

### Getting Started

To install dependencies
`go get ./...`

To run pghoney (default is 127.0.0.1:5432)
`go run *.go`

To see the cli help output:
`go run *.go -h`

### Initial Release TODO:
- [ ] Create deploy script within fflemming's fork of mhn

### TODO's
- [ ] Support SSL
- [ ] Write integration tests using nmap + psql
- [ ] Write integration tests using github.com/lib/pq
- [ ] Support proper error for "cancelling" a query (12345678, very similar to SSL request)
- [ ] Don't hardcode the md5 salt
- [ ] Support mechanism for saving passwords in a seperate database.
