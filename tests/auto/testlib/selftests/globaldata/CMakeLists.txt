# Generated from globaldata.pro.

#####################################################################
## globaldata Binary:
#####################################################################

add_qt_executable(globaldata
    NO_INSTALL # special case
    OUTPUT_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR} # special case
    SOURCES
        tst_globaldata.cpp
    PUBLIC_LIBRARIES
        Qt::Test
)

## Scopes:
#####################################################################

# special case begin
qt_apply_testlib_coverage_options(globaldata)
# special case end
