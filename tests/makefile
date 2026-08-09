VERSION := $(shell git describe --tags --always --dirty)

build:
	go build -ldflags "-X main.version=$(VERSION)" -o app .
