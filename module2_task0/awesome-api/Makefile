build:
	go build
run:
	./awesome-api
stop:
	kill "$(pgrep awesome-api)"
clean:
	rm -rf ./awesome-api ./awesome.log
test:
	curl http://localhost:9999 http://localhost:9999/health
help:
	grep '##' ./Makefile  | sed 's/ ##/ /' |  head -n -1
