```bash
env GOOS=windows GOARCH=386 go build -o windows/server.exe windows/server.go
env GOOS=darwin GOARCH=amd64 go build -o macos/server macos/server.go
env GOOS=linux GOARCH=amd64 go build -o linux/server linux/server.go
```

