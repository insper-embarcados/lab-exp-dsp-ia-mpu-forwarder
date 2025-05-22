project(pico_emb)

add_executable(pico_emb
        main.c
)


target_link_libraries(pico_emb pico_stdlib hardware_i2c freertos)

pico_add_extra_outputs(pico_emb)
