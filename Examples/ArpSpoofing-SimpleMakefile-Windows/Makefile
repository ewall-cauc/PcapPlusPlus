-include ../../Dist/mk/platform.mk
-include ../../Dist/mk/PcapPlusPlus.mk

# All Target
all:
	g++.exe $(PCAPPP_INCLUDES) -c -o main.o main.cpp
	g++.exe $(PCAPPP_LIBS_DIR) -static-libgcc -static-libstdc++ -o ArpSpoofing.exe main.o $(PCAPPP_LIBS)

# Clean Target
clean:
	del main.o
	del ArpSpoofing.exe
