project(CHAKRA_RUNTIME)

include_directories(
    .
    ../Common
    ../Backend
    ../Parser
    ByteCode
    PlatformAgnostic
    Math
    )

add_subdirectory (Base)
add_subdirectory (PlatformAgnostic)
add_subdirectory (ByteCode)
add_subdirectory (Debug)
add_subdirectory (Language)
add_subdirectory (Library)
add_subdirectory (Math)
add_subdirectory (Types)
