# Gather all source files recursively from the current directory
file(GLOB_RECURSE SRC_FILES "Fusion/*.c" "Fusion/*.cpp")

idf_component_register(SRCS ${SRC_FILES}
                       INCLUDE_DIRS "Fusion"
                    )
