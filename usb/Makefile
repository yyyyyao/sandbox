TARGET = chktap
CC = gcc
CFLAGS = -g
CFLAGS += -I/usr/local/include
CFLAGS += -I/usr/local/include/libusb-1.0/
LDFLAGS = -L/usr/local/lib -lusb
#CFLAGS += `pkg-config --cflags libusb-1.0`
#LDFLAGS = `pkg-config --libs libusb-1.0`
LDFLAGS += -lusb

$(TARGET):
	$(CC) $(CFLAGS) $(LDFLAGS) -o $(TARGET) $(TARGET).c

run:
	./$(TARGET)

clean:
	rm -f ./$(TARGET)
