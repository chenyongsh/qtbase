# Generated from qgridlayout.pro.

#####################################################################
## tst_qgridlayout Test:
#####################################################################

add_qt_test(tst_qgridlayout
    SOURCES
        sortdialog.ui
        tst_qgridlayout.cpp
    PUBLIC_LIBRARIES
        Qt::CorePrivate
        Qt::Gui
        Qt::GuiPrivate
        Qt::TestPrivate
        Qt::Widgets
        Qt::WidgetsPrivate
    ENABLE_AUTOGEN_TOOLS
        uic
)
