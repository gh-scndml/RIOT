NAME        = clk_conf
CC          = gcc
CFLAGS      = -std=c99 -Wall
SRC         = $(wildcard *.c)

.PHONY: all clean

all:
	$(CC) $(CFLAGS) -o $(NAME) $(SRC)

clean:
	rm -f $(NAME)
