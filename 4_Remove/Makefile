EXEC	= Remove

OBJS	= main.o globalvars.o \
	  readparam.o load.o \
	  save.o remove.o\
	  nrsrc/nrutil.o

INCL	= globalvars.h nrsrc/nrutil.h

CLFAGS	= -02 -wall

LIBS	= -lm

CC	= gcc

$(EXEC): $(OBJS)
	$(CC) $(CFLAGS) $(OBJS) -o $(EXEC) $(LIBS)

$(OBJS): $(INCL)

clean :
	rm -f *.o $(EXEC)
