TARGET = chktap
CFLAGS=-g
LDFLAGS=-lusb

$(TARGET):
	gcc $(CFLAGS) $(LDFLAGS) -o $(TARGET) $(TARGET).c

run:
	./$(TARGET)

clean:
	rm -f ./$(TARGET)
