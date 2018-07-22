The [ESP32](http://esp32.net/) is an excellent little SoC device that I use frequently in embedded projects when WiFi connectivity is integral. While there's an Arduino core for the device, I prefer to work closer to the silicon with the [ESP-IDF]() framework. This is a directory of components for the device. Some of these I've developed or adapted. Others here are the work of other developers.

## Components

My [fork](https://github.com/NSBum/esp-idf-lib) of the ESP-IDF component library.

| Component      | Description                                                             | License | Thread safety
|----------------|-------------------------------------------------------------------------|---------|---------------
| **i2cdev**     | [I2C utilites](https://github.com/NSBum/i2cdev)                         | MIT     | Yes
| **ds1307**     | Driver for DS1307 RTC module                                            | BSD     | Yes
| **ds3231**     | [Driver for DS3231 RTC module](https://github.com/NSBum/esp32-ds3231)   | MIT     | Yes
| **hmc5883l**   | Driver for HMC5883L 3-axis digital compass                              | BSD     | Yes
| **onewire**    | Bit-banging one wire driver                                             | MIT*    | No
| **ds18x20**    | Driver for DS18B20/DS18S20 families of one-wire temperature sensor ICs  | BSD     | No
| **dht**        | Driver for DHT11/DHT22 temperature and humidity sensors                 | BSD     | No
| **bmp180**     | Driver for BMP180 digital pressure sensor                               | MIT     | Yes
| **bmp280**     | Driver for BMP280/BME280 digital pressure sensor                        | MIT     | Yes
| **bh1750**     | Driver for BH1750 light sensor                                          | BSD     | Yes
| **ultrasonic** | Driver for ultrasonic range meters, e.g. HC-SR04, HY-SRF05              | BSD     | No
| **pcf8574**    | Driver for PCF8574 remote 8-bit I/O expander for I2C-bus                | MIT     | Yes
| **hd44780**    | Universal driver for HD44780 LCD display                                | BSD     | No
| **pca9685**    | Driver for 16-channel, 12-bit PWM PCA9685                               | BSD     | Yes
| **ms5611**     | Driver for barometic pressure sensor MS5611-01BA03                      | BSD     | Yes
| **ads111x**    | Driver for ADS1113/ADS1114/ADS1115 I2C ADC                              | BSD     | Yes
| **pcf8591**    | Driver for 8-bit ADC and an 8-bit DAC PCF8591                           | BSD     | Yes
| **tsl2561**    | Driver for light-to-digital converter TSL2561                           | BSD     | Yes
| **max7219**    | Driver for 8-Digit LED display drivers, MAX7219/MAX7221                 | BSD     | Yes

⚠️ Work in progress