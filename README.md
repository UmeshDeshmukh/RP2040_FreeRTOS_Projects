# RP2040_FreeRTOS_Projects
.
Links for info. on how to setup env. on wsl2 vscode.
(*)For make build issue with clock synch issues
sudo hwclock -s
(*)Accessing usb device from wsl2 side
https://blog.golioth.io/program-mcu-from-wsl2-with-usb-support/
(*)Accessing usb device from wsl2 side(Error: unable to find a matching CMSIS-DAP device)
https://forums.raspberrypi.com/viewtopic.php?t=348600
(*)Extend disk prtition with recovery partition in-between
https://www.technewstoday.com/extend-volume-greyed-out/
(*)
https://learnembeddedsystems.co.uk/133-2
https://mcuoneclipse.com/2022/09/17/picoprobe-using-the-raspberry-pi-pico-as-debug-probe/

(*)Access openOCD from wsl2 vscode
https://www.rustyelectrons.com/posts/3-rp2040-development-with-wsl/
src/openocd -f interface/cmsis-dap.cfg -f target/rp2040.cfg -s tcl -c "bindto 0.0.0.0"

(*)vscode setting for zephyr pico debug
https://www.mrgreensworkshop.com/posts/2022-06-10-raspberry-pi-pico-zephyr-os-part-2
Note- change in launch.json->configfiles-> /interface/cmsis-dap.cfg
