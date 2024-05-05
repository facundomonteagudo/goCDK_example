build:
	@set GOOS=linux
	@set GOARCH=amd64
	@go build -o bootstrap
	@powershell Compress-Archive .\bootstrap .\function