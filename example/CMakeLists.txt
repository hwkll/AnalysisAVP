cmake_minimum_required(VERSION 3.15)

# 获取当前文件夹名
STRING(REGEX REPLACE ".*/(.*)" "\\1" CURRENT_FOLDER ${CMAKE_CURRENT_SOURCE_DIR})

project(${CURRENT_FOLDER})

# 添加子项目
#add_subdirectory(libwebp)
#add_subdirectory(libde265)
#add_subdirectory(x265)
add_subdirectory(libopus)
#add_subdirectory(ffmpeg)
#add_subdirectory(zlmediakit)
