vc_get_absolute_paths(SRC ${CMAKE_CURRENT_SOURCE_DIR}
  cmc.cpp
  )

target_sources(VCIGCDeps
  PRIVATE
    ${SRC}
  )
