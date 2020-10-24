cmake_minimum_required(VERSION 3.10)

project( libaiff )

add_library( aiff aifx.c float32.c iff.c lpcm.c extended.c g711.c libaiff.c pascal.c )

target_include_directories( aiff PUBLIC .  )
