# Makefile for os_crypto shared
# Daniel B. Cid <dcid@sourcefire.com>||<daniel@underlinux.com.br>

PT=../../
NAME=shared

include ../../Config.Make

SRCS = *.c
OBJS = *.o


shared:
		$(CC) $(CFLAGS) -c $(SRCS)
		ar cru shared.a $(OBJS)
		ranlib shared.a
clean:
		${CLEAN}
