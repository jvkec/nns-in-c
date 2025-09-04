# set compiler to gcc
CC = gcc

# first flag tells compiler to look for ./include,
# second flag enables all compiler warnings, third turns on optimization level 2
CFLAGS = -Iinclude -Wall -O2

SRC = $(wildcard src/*.c)
TARGET = mnist

all: $(TARGET)

$(TARGET): $(SRC)
    $(CC) $(CFLAGS) $(SRC) -o $(TARGET)

clean:
    rm -f $(TARGET)