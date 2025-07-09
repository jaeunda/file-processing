CC = gcc
SRCS = src/fdevicedriver.c src/ftlmgr.c
TARGET = a.out
FLASH = flashmemory

all : $(TARGET)

$(TARGET) : $(SRCS)
	$(CC) -o $(TARGET) $(SRCS)

clean:
	rm -r $(TARGET) $(FLASH)
