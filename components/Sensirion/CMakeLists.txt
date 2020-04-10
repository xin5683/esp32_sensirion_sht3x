set(COMPONENT_SRCS  "sht3x.c" 
                    "sensirion_common.c")
set(COMPONENT_ADD_INCLUDEDIRS ". include")
set(COMPONENT_PRIV_INCLUDEDIRS ". priv_include")

set(COMPONENT_REQUIRES i2c_bus)
register_component()



