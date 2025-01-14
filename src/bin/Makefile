#
#
#
SRCS  = demod.c
SRCS += split.c
SRCS += uart.c
SRCS += uart_deglitch.c
SRCS += uart_to_timed_octetts.c
SRCS += uart_uart.c
SRCS += uart_uart_split.c

TARGETS = $(SRCS:.c=)

CC = gcc

CFLAGS = -std=gnu11
CFLAGS += -O2
CFLAGS += -Wall
CFLAGS += -g

all:	$(TARGETS)

clean:
	-rm *.o $(TARGETS)


