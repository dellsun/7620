EXEC=watchdog  
SRC=watchdog.c resetd.c wps.c

all: $(EXEC)
watchdog: $(SRC)
	$(CC) $(CFLAGS) $(LDFLAGS) -o $@ $(SRC) $(LDLIBS)

clean:
	-rm -f $(EXEC) *.elf *.gdb *.o

