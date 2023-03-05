set(COMPONENT_ADD_INCLUDEDIRS "./include")

register_component()

add_prebuilt_library(hello_world "${CMAKE_CURRENT_SOURCE_DIR}/lib/libhello_world.a")

target_compile_options(${COMPONENT_TARGET} INTERFACE -Wno-implicit-fallthrough -Wno-unused-const-variable)

target_link_libraries(${COMPONENT_TARGET} INTERFACE hello_world)