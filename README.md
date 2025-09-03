# bed sunrise wakeup light
Wemos D1 Mini clone with HC-SR501 PIR sensor, running a ~3 meter long WS2811-based LED adressable strip.

Physically prototyped on 40x60 mm veroboard and mounted in lasercut-case with cutout for PIR sensor. LED strip to be mounted on wooden strip, half the length of the LED strip, then mounted up underneath bed and centered to distribute light uniformly.

Onhape document for enclosure: https://cad.onshape.com/documents/6aec106bbac822df499c7207/w/79236c54a81cc9ab38dafb96/e/e9a079ac3f882e2efd92dde7

Script lerps the strip between muted, deep red to bright golden-hour for a configurable period before alarm-time. 
Alarm time is hardcoded and invoked through NTP. If Home Assitant is available, next alarm could be fetched from phone companion app or other means, easy with 'manual' iOS alarms, yet annoying to fetch next 'scheduled' iOS alarm. Let me know if you have good method.

PIR sensor functions as nightlight upon detection. 
