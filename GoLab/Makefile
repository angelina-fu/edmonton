

VER=1.17

GO_PKT=go${VER}.linux-armv6l.tar.gz
install:
	wget https://dl.google.com/go/${GO_PKT}
	sudo tar -C /usr/local -xzf ./${GO_PKT}


init:
	go env -w GOPROXY=https://goproxy.cn,direct
