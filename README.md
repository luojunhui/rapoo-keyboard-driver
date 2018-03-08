# rapoo-keyboard-driver
Some bugfix for rapoo keyboard where some keys are invalid.

# Quick Usage
Compile the driver module with make, make install and run ./install-rapoo-keyboard-driver.sh.

Job done! Then enjoy typing!

# Notice
After installing new kernel(contains compile and install kernel),
you must reinstall hid-rapoo module again by "make install".

解决有些键盘在Linux下alt和Ctrl都输出为Shift，
出现报错请尝试使用root or sudo
