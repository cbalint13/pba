
ADD_EXECUTABLE(pba_driver driver.cpp)

TARGET_LINK_LIBRARIES(pba_driver pba ${CMAKE_THREAD_LIBS_INIT})

INSTALL(TARGETS pba_driver DESTINATION "/usr/bin/")

