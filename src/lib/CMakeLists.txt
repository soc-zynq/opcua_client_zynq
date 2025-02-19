# Create a library called "opcua_client_zynq"
add_library(opcua_client_zynq_lib opcua_client_zynq.cpp)

# Specify include directories for the library
target_include_directories(opcua_client_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
