project(test_fsa)

set (SRCS
  Machine.cpp
  main.cpp
  )

set (HEADERS
  Machine.hpp
  )

add_executable(test_fsa ${SRCS} ${HEADERS})
