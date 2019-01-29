# w600 usage
1. unzip the w600-arduino-InnerIDE-0.2.0.zip,put the /w600 under the $ARDUINO_INSTALL_DIR\Arduino\hardware\ directory.
2. open arduino IDE,click Tools -> Boards,you can see the "Generic W600 board" board option at right sidebar.
3. Install python version 3.4 or above.
4. Install dependency python package:
	pip install pyserial
	pip install pyprind
	pip install xmodem
	pip install enum34
	pip install PyInstaller
5. Now you can compile example and upload firmware,The examples located in w600\w600-arduino-0.2.0\examples.during uploading,you have to reset the board according to the prompt message.