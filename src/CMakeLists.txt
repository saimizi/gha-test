SET(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O0 -g")

SET(SRC_FIlES
	main.c
)

message("SRC_FIlES: ${SRC_FIlES}")
add_executable(gha_test ${SRC_FIlES})
install(TARGETS gha_test DESTINATION ${CMAKE_INSTALL_BINDIR})
