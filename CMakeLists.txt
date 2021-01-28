cmake_minimum_required(VERSION 3.17)
project(ndislwf C)

set(CMAKE_C_STANDARD 11)

include_directories(src/60)

add_executable(ndislwf
        src/60/arp.c
        src/60/arp.h
        src/60/device.c
        src/60/ethernet.c
        src/60/ethernet.h
        src/60/filter.c
        src/60/filter.h
        src/60/filteruser.h
        src/60/flt_dbg.c
        src/60/flt_dbg.h
        src/60/icmp.c
        src/60/icmp.h
        src/60/ip.c
        src/60/ip.h
        src/60/precomp.h
        src/60/tcp.c
        src/60/tcp.h
        src/60/udp.c
        src/60/udp.h
        src/60/utilities.h)
