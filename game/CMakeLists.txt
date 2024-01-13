add_executable(game app.cpp)

target_compile_features(game PRIVATE cxx_std_17)

target_link_libraries(game PUBLIC engine)

