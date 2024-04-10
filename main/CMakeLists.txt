idf_component_register(SRCS "sync_write.c"
                    INCLUDE_DIRS "." REQUIRES dynamixel_sdk_esp)

target_compile_options(${COMPONENT_LIB} PRIVATE -Wno-error=format)
