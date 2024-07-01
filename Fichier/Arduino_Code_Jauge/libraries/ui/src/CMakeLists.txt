SET(SOURCES screens/ui_Screen1.c
    screens/ui_Screen2.c
    screens/ui_Screen3.c
    screens/ui_Screen4.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    images/ui_img_2065062798.c
    images/ui_img_jauge_rpm_png.c
    images/ui_img_home_png.c
    images/ui_img_amesisproject_png.c
    images/ui_img_background1_png.c
    images/ui_img_led_png.c
    images/ui_img_boutton_png.c
    images/ui_img_gauge_png.c
    images/ui_img_turbo_png.c
    images/ui_img_afr_png.c
    images/ui_img_monlogo240_png.c
    images/ui_img_1703503159.c
    fonts/ui_font_Digit.c
    fonts/ui_font_Font1.c)

add_library(ui ${SOURCES})
