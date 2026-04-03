CC     = gcc
SRC    = $(wildcard *.c)
TARGET = $(basename $(SRC))
STD    = c2x
OUTPUT = output.txt

CFLAGS_COMMON  = -Wall -Wextra -pedantic-errors -std=$(STD)
CFLAGS_DEBUG   = -g -O0
CFLAGS_RELEASE = -O3

all: debug save run

debug: CFLAGS = $(CFLAGS_COMMON) $(CFLAGS_DEBUG)
debug: $(TARGET)

release: CFLAGS = $(CFLAGS_COMMON) $(CFLAGS_RELEASE)
release: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(TARGET)

run:
	./$(TARGET)

save:
	./$(TARGET) > $(OUTPUT)

format:
	clang-format -i --style=Google $(SRC)

clean:
	rm -f $(TARGET)

.PHONY: all debug release run save format clean
