CFLAGS = -Wall -O3 `pkg-config --cflags --libs libndn-cxx`

ndnperf: client.cpp main.cpp client.h module.h
	g++ -o $@ client.cpp main.cpp -std=c++14 $(CFLAGS)
