add_library(libs STATIC "")

target_sources(libs
  PRIVATE
    print.cpp
  )

target_include_directories(libs
  PUBLIC
    ${CMAKE_CURRENT_LIST_DIR}
  )
