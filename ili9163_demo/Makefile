# ---------------------------------------------------------------
#     einfaches Makefile zum Uebersetzen und Linken von
#     STM8S Programmen mittels SDCC
# ---------------------------------------------------------------

# hier den Namen der Quelldatei ohne Endung ".c" angeben
SRC_NAME     =  ili9163_demo

# hier alle Dateien angeben, die hinzugelinkt werden sollen
# Objektdateien enden im Gegensatz zu GCC / AVR-GCC / ARM-NONE-EABI-GCC nicht mit .o sondern mit .rel
SRCS      = ../src/stm8_init.rel
SRCS     += ../src/spi.rel
SRCS     += ../src/tftdisplay.rel

FLASHERPROG  = 1

include ../makefile.mk
