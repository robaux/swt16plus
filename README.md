# Robaux SWT16+

The [Robaux SWT16+](https://robaux.io/swt16plus) comes with a very extensive firmware. From time to time new features will be added or improved. A firmware update is not difficult, but the update process is a bit fumbling.

To transfer a firmware update you need a computer with a serial USB interface. Since the heart of the sequencer is an ATMega328, especially an [Arduino UNO](https://store.arduino.cc/arduino-uno-rev3) is excellent. But it also work with standard interfaces such as FT232 or similar.

You also need the transfer program [AVRDude](https://typeunsafe.wordpress.com/2011/07/22/programming-arduino-with-avrdude/) which comes with the [Arduino software](https://www.arduino.cc/en/main/software). AVRDude is a command line utility. But there are also graphical interfaces, for example [HexUploader](http://paulkaplan.me/HexUploader/).

The [Update](https://github.com/robaux/swt16plus/tree/master/update) folder contains the firmware hex files which you can transfer to the device. 

Select the version you want to transfer. Connect your Robaux SWT16+ to your serial port as shown in the pictures. 

Select your serial interface in AVRDude or a corresponding program as well as the HEX file and transfer it to the Robaux SWT16+. If you have any questions, please contact update@robaux.io

---

![Updating using a Arduino Uno](https://raw.githubusercontent.com/robaux/swt16plus/master/update/updatingArduinoUno.jpg?token=AGIDIEQGQYGG4JJSD7D5J4C5GMC5C)

---

![Updating using a FT232](https://raw.githubusercontent.com/robaux/swt16plus/master/update/updatingFT232.jpg?token=AGIDIEWGMRKW5GVSPPMDQ3S5GMDBQ)