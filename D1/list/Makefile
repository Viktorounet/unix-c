CC = gcc 
CFLAGS = -Wall -Werror -Wextra -std=c99 -g

SRC = main.c list.c
OBJ = $(SRC:.c=.o)
BIN = main

$(BIN): $(OBJ)

all: $(BIN)

clean: 
	${RM} ${OBJ} ${BIN}
