zephyr_include_directories(src)

zephyr_library()

zephyr_library_sources_ifdef(CONFIG_PMW3610 src/pmw3610.c)
zephyr_library_sources_ifdef(CONFIG_PMW3610 src/pmw3610_priv.c)
