APPNAME = isis2raw

include $(ISISROOT)/make/isismake.tsts

commands:
	$(APPNAME) from=$(INPUT)/isisTruth.cub+2 \
	to=$(OUTPUT)/isis2rawTruth5.raw \
	storageorder=bip \
	bittype= 8BIT \
	stretch= none > /dev/null;
