CC = gcc
SRCS = src/main.c src/fdevicedriver.c src/ftlmgr.c 
TARGET = a.out
FLASH = flashmemory

all: $(TARGET)

$(TARGET): $(SRCS)
	$(CC) -o $(TARGET) $(SRCS)

clean:
	rm -f $(TARGET) $(FLASH)
