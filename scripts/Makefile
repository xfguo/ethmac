rtl-tests:
	mkdir -p ../build/sim
	mkdir ../log
	iverilog -stb_ethernet -cicarus.scr -o ../build/sim/ethmac.elf
	vvp ../build/sim/ethmac.elf

