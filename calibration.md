https://espeasy.readthedocs.io/en/latest/Plugin/P002.html

Although the values of the voltages will be different for an ESP32, the same principle will apply. You must find what the maximum and minimum voltages for your ADC input are, then set the mid-point or bias voltage to be half-way between the two. For an Arduino, those voltages are 5.0 V and 0 V, and half-way is 2.5 V. For our emonTx, the voltages are 3.3 V and 0 V and the mid-point is 1.65 V.

https://community.openenergymonitor.org/t/emonlib-esp32-how-to-calibrate/11465/10


https://esp32tutorials.com/esp32-pwm-esp-idf-led-brightness-control/

https://github.com/danpeig/ESP32EnergyMonitor



https://embarcados.com.br/esp32-adc-interno/

https://embarcados.com.br/esp32-adc-interno/
