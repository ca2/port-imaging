cmake_minimum_required(VERSION 3.16)
project(imaging)



if(${USE_PORT_FREEIMAGE})

    add_subdirectory(port_webp)
    add_subdirectory(port_tiff4)
    add_subdirectory(port_rawlite)
    add_subdirectory(port_png)
    add_subdirectory(port_openjpeg)
    add_subdirectory(port_openexr)
    add_subdirectory(port_jxr)
    add_subdirectory(port_jpeg)
    add_subdirectory(port_freeimage)

endif()