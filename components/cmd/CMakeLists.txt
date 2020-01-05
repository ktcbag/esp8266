set(COMPONENT_SRCS 	"cmd_system.c"
					"cmd_wifi.c")

set(COMPONENT_ADD_INCLUDEDIRS .)

set(COMPONENT_REQUIRES console spi_flash)

register_component()
