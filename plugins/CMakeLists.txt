add_subdirectory(multiserver)
if(BUILD_OPENCV_CAMERA_PLUGIN)
	add_subdirectory(opencv)
endif()
if(BUILD_VIDEOTRACKER_PLUGIN)
	add_subdirectory(my_videobasedtracker)
endif()
if(BUILD_ANALYSISPLUGINKIT)
	add_subdirectory(oneeurofilter)
	add_subdirectory(videoimufusion)
endif()
