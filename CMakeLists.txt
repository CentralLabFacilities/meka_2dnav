cmake_minimum_required(VERSION 2.8.3)
project(meka_2dnav)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED)

find_package(catkin REQUIRED 
	COMPONENTS 
)

catkin_package(
	CATKIN_DEPENDS 
)

install(DIRECTORY ./
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
