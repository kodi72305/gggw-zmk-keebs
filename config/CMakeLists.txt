if(EXISTS "${CMAKE_CURRENT_SOURCE_DIR}/src")
  file(GLOB app_local_sources CONFIGURE_DEPENDS "${CMAKE_CURRENT_SOURCE_DIR}/src/*.c")
  target_sources(app PRIVATE ${app_local_sources})
endif()

