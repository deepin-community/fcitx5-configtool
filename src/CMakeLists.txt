if (ENABLE_KCM)
    add_subdirectory(kcm)
endif()
add_subdirectory(lib)

if (ENABLE_CONFIG_QT)
    add_subdirectory(configtool)
endif()

add_subdirectory(migrator)

if (ENABLE_KCM)
    add_subdirectory(plasmathemegenerator)
endif()
