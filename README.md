# MSE TSM MobCom
## Hands-on of lesson 6
For slides and example code, see [lesson 6](../../../mse-tsm-mobcom/blob/master/06/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) HRM BLE peripheral, 10'
* Build and run the previous nRF52840 BLE example.
* Use the .ino link on the page to get the example code.
* Explore the HRM example using a smartphone app<sup>*</sup>.
* Try to enable notifications to get value updates.

<sup>*</sup>Try [nRF Connect for Android](https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp) or [iOS](https://apps.apple.com/us/app/nrf-connect/id1054362403).

### b) HRM BLE central, 10'
* Build and run the previous nRF52840 BLE example.
* Use the .ino link on the page to get the example code.
* Open the Arduino serial monitor to enter a message.
* Use a second nRF52840<sup>*</sup> as a HRM peripheral.

<sup>*</sup>Or your smartphone as a [peripheral simulator](https://play.google.com/store/search?q=BLE%20peripheral%20simulator&c=apps&hl=en_US&gl=US).

### c) UART BLE peripheral, 10'
* Build and run the previous nRF52840 BLE example.
* Use the .ino link on the page to get the example code.
* Write bytes to RX with a generic BLE explorer app.
* Check the serial monitor to see the received bytes<sup>*</sup>.

<sup>*</sup>Why do some bytes not show up?

### d) UART BLE central, 10'
* Build and run the previous nRF52840 BLE example.
* Use the .ino link on the page to get the example code.
* Open the Arduino serial monitor to enter a message.
* Use a second nRF52840 as a UART peripheral.

### e) Scanner BLE central, 10'
* Build and run the previous nRF52840 BLE examples.
* Use the .ino link on the page to get the example code.
* Test the scanner with a (simulated) HRM peripheral.
* Adapt the scanner to scan for the beacon observable.
* Bonus: Scan for Covid-19 apps as described [here](https://steigerlegal.ch/2020/07/06/swisscovid-app-bluetooth/).
