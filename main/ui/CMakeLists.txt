SET(SOURCES screens/ui_Screen1.c
    ui.c
    ui_helpers.c
    images/ui_img_bilibili_png.c
    images/ui_img_bilibiliname_png.c
    fonts/ui_font_PHFont16.c
    fonts/ui_font_PHFont18.c
    fonts/ui_font_PHFont20.c
    fonts/ui_font_PHFont22.c
    fonts/ui_font_PHFont24.c
    fonts/ui_font_PHFont26.c
    fonts/ui_font_PHFont30.c)

add_library(ui ${SOURCES})
