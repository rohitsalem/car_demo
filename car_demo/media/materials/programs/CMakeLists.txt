file(GLOB files "*.glsl")

install(FILES ${files} DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/media/materials/programs)
