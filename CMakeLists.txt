cmake_minimum_required(VERSION 3.0)

project(auroracoin)

add_definitions(-DCLIENT_VERSION_MAJOR=2019)
add_definitions(-DCLIENT_VERSION_MINOR=06)
add_definitions(-DCLIENT_VERSION_REVISION=1)
add_definitions(-DCLIENT_VERSION_BUILD=0)
add_definitions(-DCLIENT_VERSION_RC=0)
add_definitions(-DCLIENT_VERSION_IS_RELEASE=false)
add_definitions(-DCOPYRIGHT_YEAR=2019)
add_definitions(-DCOPYRIGHT_HOLDERS="[The %s developers]")
add_definitions(-DCOPYRIGHT_HOLDERS_SUBSTITUTION="[[Auroracoin]]")


ADD_SUBDIRECTORY(src)
