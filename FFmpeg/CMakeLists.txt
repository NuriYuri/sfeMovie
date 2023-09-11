# Use user's FFmpeg libraries
find_package(FFMPEG REQUIRED)
if ("${FFMPEG_FOUND}" STREQUAL "NO")
    message(FATAL_ERROR "Could not find a full FFmpeg installation")
endif()
