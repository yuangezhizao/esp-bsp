idf_component_register(
    SRCS "esp_sparkbot_45coll.c" "esp_sparkbot_45coll_idf5.c"
    INCLUDE_DIRS "include" "include/bsp"
    PRIV_INCLUDE_DIRS "priv_include"
    REQUIRES driver spiffs touch_element
    PRIV_REQUIRES fatfs esp_lcd 
    # REQUIRES esp_driver_gpio esp_driver_sdmmc spiffs esp_driver_i2c fatfs
    # PRIV_REQUIRES esp_lcd esp_driver_ledc esp_driver_spi esp_psram
)
