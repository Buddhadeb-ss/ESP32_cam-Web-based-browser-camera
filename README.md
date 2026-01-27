# ESP32_cam-Web-based-browser-camera
It is a ESP32 cam module application repo. This is for education and learning purposes. Components used in the projects are ESP32 cam module, ESP32 MB board for programming the board, Micro USB B cable for connection and power.
# esp32-dashboard

a simple, standalone web server for the esp32-cam. i made this because the standard examples are too complicated or require python scripts. this one runs entirely on the chip.

## features
* **software trigger:** click a button on the website to take a photo (no physical wiring or GPIO 0 issues).
* **built-in flash:** auto-triggers the onboard led when capturing.
* **dashboard ui:** dark mode interface with a 2-column grid to stack your photos.
* **review mode:** preview and rotate images (90° left/right) before adding them to your gallery.
* **no external dependency:** you don't need a python server or an app. just a browser.

## how to use
1.  edit the `ssid` and `password` in the code.
2.  upload to esp32-cam (AI-Thinker model).
3.  open the serial monitor to get the ip address.
4.  open that ip in your browser and start snapping.

## hardware
* ESP32-CAM (AI-Thinker)
* 5V power supply
* (that's it, no buttons needed)
