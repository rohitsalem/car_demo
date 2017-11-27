file(GLOB files "*.material" "*.compositor" "*.program")

install(FILES ${files} DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/media/materials/scripts)
