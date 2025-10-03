FILE ?= main.s
BIN  = $(basename $(FILE))

build:
	clang -arch arm64 -o $(BIN) $(FILE)

run:
	./$(BIN)

forcerun: build
	./$(BIN)

clean:
	rm -f $(BIN)