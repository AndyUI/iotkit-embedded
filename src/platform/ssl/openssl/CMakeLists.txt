file(GLOB C_SOURCES "*.c")
include_directories(AFTER /usr/local/ssl/include)
add_library(platform_openssl OBJECT ${C_SOURCES})
