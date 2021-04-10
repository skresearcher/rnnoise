file(GLOB SOURCES *.c)
file(GLOB HEADERS *.h)

add_library(rnnoise ${SOURCES} ${HEADERS})