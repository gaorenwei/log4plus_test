log4cplus_add_test(appender_test main.cxx)
target_link_libraries(appender_test PRIVATE log4cplus::log4cplus)