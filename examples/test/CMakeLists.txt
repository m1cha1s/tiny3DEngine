project(test)

add_executable(test
    main.c
)

target_link_libraries(test PUBLIC t3DE)