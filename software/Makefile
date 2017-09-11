all:
	@echo "Targets: "
	@echo "  compile    Compile software packages"
	@echo "  clean      Remove intermediate files"

clean:
	cd hal;          make clean; cd ..
	cd demode0nano;  make clean; cd ..
	cd demode1soc;   make clean; cd ..
	cd timerde1soc;  make clean; cd ..
	cd timerde0nano; make clean; cd ..

compile:
	cd hal;          make compile; cd ..
	cd demode0nano;  make compile; cd ..
	cd demode1soc;   make compile; cd ..
	cd timerde1soc;  make compile; cd ..
	cd timerde0nano; make compile; cd ..
