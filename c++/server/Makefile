CFLAGS = -Wall -O3 `pkg-config --cflags --libs libndn-cxx`

ndnperfserver: server.cpp concurrentqueue.h blockingconcurrentqueue.h
	g++ -o $@ $< -std=c++14 $(CFLAGS)
