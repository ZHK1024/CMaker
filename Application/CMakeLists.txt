project(Application)

file(GLOB H_FILES ${PROJECT_SOURCE_DIR}/*.h)
file(GLOB CPP_FILES ${PROJECT_SOURCE_DIR}/*.cpp)

add_executable(Application
        ${H_FILES}
        ${CPP_FILES}
        )