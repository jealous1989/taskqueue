CMAKE_MINIMUM_REQUIRED(VERSION 2.6)

SET(BOOST_ROOT ${CMAKE_CURRENT_SOURCE_DIR}/..)
INCLUDE_DIRECTORIES(${BOOST_ROOT})

ADD_SUBDIRECTORY(system)
#ADD_SUBDIRECTORY(filesystem)
#ADD_SUBDIRECTORY(regex)
#ADD_SUBDIRECTORY(chrono)
ADD_SUBDIRECTORY(thread)
#ADD_SUBDIRECTORY(timer)


