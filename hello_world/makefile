GO = go

.PHONY: build clean

build: bin
	@${GO} fmt ./...
	@${GO} build -o bin
clean:
	@rm -r bin

bin:
	@mkdir -p bin
