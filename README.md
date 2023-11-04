# forSDCC
https://hackaday.io/project/167952-semyon/log/169905-blink-with-sdas

build:
	sdas8051 -los NAME.asm
	sdld -i NAME
	packihx NAME.ihx > NAME.hex
