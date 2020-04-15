cmake_minimum_required (VERSION 3.14.5)
project (ios-sample C)

set(SOURCES
  helloworld.c
)

add_library (ios-sample SHARED ${SOURCES} ${HEADERS})
