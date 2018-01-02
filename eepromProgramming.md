Edit eprom_settings.txt

./eepmake eeprom_settings.txt myhat.eep

sudo sh eepflash.sh -w -f=myhat.eep -t=24c256

sudo hexdump /sys/class/i2c-adapter/i2c-3/3-0050/eeprom

paste results into http://www.rapidtables.com/convert/number/hex-to-ascii.htm
