# How to make a lib

https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-guides/build-system.html

```
add_prebuilt_library(target_name lib_path [REQUIRES req1 req2 ...] [PRIV_REQUIRES req1 req2 ...])

target_link_libraries(${COMPONENT_LIB} INTERFACE "-u reverse_ops")

```