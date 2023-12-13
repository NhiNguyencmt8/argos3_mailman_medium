add_library(kheperaiv_obstacleavoidance MODULE kheperaiv_obstacleavoidance.h kheperaiv_obstacleavoidance.cpp)
target_link_libraries(kheperaiv_obstacleavoidance
        argos3core_simulator
        argos3plugin_simulator_kheperaiv
        argos3plugin_simulator_genericrobot)