BINARY = blink
LDSCRIPT = ../stm32f103.ld
SCRIPT_DIR=..

default: $(BINARY).bin

flash: $(BINARY).bin
	@st-flash write $(BINARY).bin 0x08000000

include ../Makefile.include
