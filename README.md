# foscam-config
Single file HTML/jQuery app to configure a local Foscam webcam using its public API.

I have found that some Foscam webcams (e.g. FosBaby) have a web control panel that requires browser plugins to be installed, and won't even let you configure the networking settings or account passwords without them. Worse, these plugins are blocked by modern browsers.

This simple HTML page allows you to configure the basics on such a Foscam camera to make it usable via third party software (e.g. Motion).

Installation: download the HTML file.  Open it in a web browser :-)

I have added all the basic features I needed.  Others could be added quite easily by referring to the code and the [Foscam IPCamera CGI User Guide](https://www.foscam.es/descarga/Foscam-IPCamera-CGI-User-Guide-AllPlatforms-2015.11.06.pdf) to see which APIs you need.

# Screenshots

![Connections and credentials](https://raw.githubusercontent.com/richardloxley/foscam-config/master/foscam-config-example1.png)

![WiFi](https://raw.githubusercontent.com/richardloxley/foscam-config/master/foscam-config-example2.png)

![Device configuration](https://raw.githubusercontent.com/richardloxley/foscam-config/master/foscam-config-example3.png)
