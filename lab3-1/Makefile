# 编译器
CC = g++

# 编译选项
CFLAGS = -lwsock32 -fexec-charset=gbk

# 目标文件
TARGETS = server client

all : $(TARGETS)

server : server.cpp
	$(CC) $^ -o $@ $(CFLAGS)

client : client.cpp
	$(CC) $^ -o $@ $(CFLAGS)

clean :
	del /F /Q $(TARGETS)