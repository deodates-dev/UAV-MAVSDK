include_directories(
    ${PROJECT_SOURCE_DIR}/core
    SYSTEM  ${PROJECT_SOURCE_DIR}/third_party/mavlink/include
)

add_subdirectory(action)
add_subdirectory(calibration)
add_subdirectory(camera)
add_subdirectory(failure)
add_subdirectory(follow_me)
add_subdirectory(ftp)
add_subdirectory(geofence)
add_subdirectory(gimbal)
add_subdirectory(info)
add_subdirectory(log_files)
add_subdirectory(manual_control)
add_subdirectory(mavlink_passthrough)
add_subdirectory(mission)
add_subdirectory(mission_raw)
add_subdirectory(mocap)
add_subdirectory(offboard)
add_subdirectory(param)
add_subdirectory(shell)
add_subdirectory(telemetry)
add_subdirectory(tracking_server)
add_subdirectory(tune)

set(UNIT_TEST_SOURCES ${UNIT_TEST_SOURCES} PARENT_SCOPE)
