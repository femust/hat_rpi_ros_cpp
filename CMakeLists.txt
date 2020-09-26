cmake_minimum_required(VERSION 2.4)

project(hello_world)

add_executable(main main.cpp source/adafruitdcmotor.cpp source/adafruitmotorhat.cpp source/i2cdevice.cpp source/pwm.cpp)
