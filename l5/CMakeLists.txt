cmake_minimum_required(VERSION 3.10)

project(cpp-network-lesson-5)


if (UNIX)
# To build this lesson code on Windows, libraries must be installed manually.
    add_subdirectory("qt_broadcastsender")
    add_subdirectory("qt_broadcastreceiver")
    add_subdirectory("phistache-example")
    add_subdirectory("poco-examples")
    add_subdirectory("gio_client")
    add_subdirectory("gio_server")
endif()
