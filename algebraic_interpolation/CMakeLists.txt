add_executable(algebraic_interpolation main.cpp)
target_compile_features(algebraic_interpolation PRIVATE cxx_std_17)
target_link_libraries(algebraic_interpolation PRIVATE interpolation)