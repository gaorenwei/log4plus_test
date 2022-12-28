log4cplus_add_test(fileappender_test  main.cxx)
target_link_libraries(fileappender_test PRIVATE log4cplus::log4cplus)