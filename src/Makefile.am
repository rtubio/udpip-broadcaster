# flags for the compiler and for the linker
CFLAGS = --pedantic -std=gnu99 -Wall -O0 -g3
LDFLAGS = -lev
# binaries to be produced
bin_PROGRAMS = udpipbroadcaster
udpipbroadcaster_SOURCES = configuration.c main.c udpev/__NEC__gnbtpapi_udp_msg.c udpev/cb_udp_events.c udpev/udp_events.c udpev/udp_socket.c
