#Add sources from ui directory
file(GLOB_RECURSE SRC_UI ${CMAKE_SOURCE_DIR} "ui/*.c")

idf_component_register(SRCS "main.c" "app_wifi.c" ${SRC_UI}
                    INCLUDE_DIRS "." "ui")
                    # REQUIRES unity test_utils openai protocol_examples_common esp_netif nvs_flash esp_wifi)
