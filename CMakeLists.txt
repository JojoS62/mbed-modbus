add_library(mbed-modbus INTERFACE)

target_sources(mbed-modbus
    INTERFACE
        mb.cpp
        mbcrc.cpp
        mbfunccoils.cpp
        mbfuncdiag.cpp
        mbfuncdisc.cpp
        mbfuncholding.cpp
        mbfuncinput.cpp
        mbfuncother.cpp
        mbrtu.cpp
        mbutils.cpp
        portevent.cpp
        portserial.cpp
        porttimer.cpp
)

target_include_directories(mbed-modbus
    INTERFACE
        .
)
