# ---------------------------------------------------------------
#     einfaches Makefile zum Uebersetzen und Linken von
#     STM8S Programmen mittels SDCC
# ---------------------------------------------------------------

# hier den Namen der Quelldatei ohne Endung ".c" angeben
SRC_NAME     =  n5510_tempwatch

# hier alle Dateien angeben, die hinzugelinkt werden sollen
# Objektdateien enden im Gegensatz zu GCC / AVR-GCC / ARM-NONE-EABI-GCC nicht mit .o sondern mit .rel
SRCS      = ../src/stm8_init.rel
SRCS     += ../src/stm8_systimer.rel
SRCS     += ../src/uart.rel
SRCS     += ../src/stm8_glcd_nokia.rel
SRCS     += ../src/spi.rel
SRCS     += ../src/my_printf.rel

FLASHERPROG = 1

include ../makefile.mk
