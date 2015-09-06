# Install go:
===============
add this to ~/.bashrc or ~/.profile
```
export GOROOT=$HOME/.local/go
export PATH=$PATH:$GOROOT/bin
```
execute this
```
wget https://storage.googleapis.com/golang/go1.5.linux-amd64.tar.gz
tar -C ~/.local -xzf go1.5.linux-amd64.tar.gz
rm go1.5.linux-amd64.tar.gz
source ~/.bashrc
go version
```
