GOPATH := ${PWD}
export GOPATH

build:
	go build -v isubata

vet:
	go vet ./src/isubata/...

deps:
	cd ./src/isubata; dep ensure
