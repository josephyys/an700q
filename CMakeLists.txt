cmake_minimum_required(VERSION 3.20.0)
set(BOARD an7002q_db5340)

find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(my_combo_wifi_ble_project)
target_sources(app PRIVATE src/main.c)