# Generated from qtextedit.pro.

#####################################################################
## tst_qtextedit Test:
#####################################################################

# Collect test data
list(APPEND test_data "fullWidthSelection")

add_qt_test(tst_qtextedit
    SOURCES
        tst_qtextedit.cpp
    PUBLIC_LIBRARIES
        Qt::CorePrivate
        Qt::Gui
        Qt::GuiPrivate
        Qt::Widgets
        Qt::WidgetsPrivate
    TESTDATA ${test_data}
)

## Scopes:
#####################################################################

extend_target(tst_qtextedit CONDITION APPLE_OSX
    PUBLIC_LIBRARIES
        ${FWAppKit}
)
