# Lolin32-radio
This is another project like others out there: a web radio with ESP32.

New update: I put a bluetooth mode through an SPDT switch. Look in the RadioeBT folder.

The best update so far: it's possible to update your list of radio stations via a text file in GIST! See it on RadioWeb example. This is important because radio stations often change their URLs. In my case, as I make the radio sets as gifts to my friends, I won't need to get the sets back to update them. Although it is a good reason to visit them!


This radio uses Lolin32 Lite (with a PSRAM update), a 1.8'' SPI screen and I2S as audio output for two options:
1) PCM5102 + PAM8403

![image](https://github.com/renatoianhez/Lolin32-radio/assets/34423009/2f8a6b8d-9032-43c8-afa7-e9579d9a7465)


![image](https://github.com/renatoianhez/Lolin32-radio/assets/34423009/eca303cb-7ebb-4cda-8960-a2719170ab75)



2) 02 MAX98356

![image](https://user-images.githubusercontent.com/34423009/181618155-2ee50b2a-1f63-4c38-bc8b-b1c7e8097aa3.png)

The libraries used are:

ESP32-audioI2S: https://github.com/schreibfaul1/ESP32-audioI2S

TFT_eSPI: https://github.com/Bodmer/TFT_eSPI

Bluetooth: https://github.com/pschatzmann/ESP32-A2DP

Add the PSRAM:

![image](https://user-images.githubusercontent.com/34423009/181618815-bb8abaf5-4f57-484a-8c8b-20fcffd7e0ec.png)

https://blog.pagefault-limited.co.uk/lolin32-lite-esp32-8mb-psram-upgrade-mod

After audio library updates, it is possible to play HLS streams!
I'm assembling it in a wooden box.
![Imagem do WhatsApp de 2023-02-05 à(s) 17 16 38](https://user-images.githubusercontent.com/34423009/216842651-7298a861-359e-4c44-aa80-7afa5a5a34c8.jpg)


