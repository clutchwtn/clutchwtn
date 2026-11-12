# Hi, I'm Jalel

Third-year Computer Engineering student at the Faculté des Sciences de Tunis (FST), specializing in **Embedded Systems and IoT**. I like building things end to end: the hardware, the firmware, and the server it talks to.

**Looking for a final-year internship (PFE) in IoT or embedded systems, starting February 2027.**

## Projects

### [UniSmartPay](https://github.com/clutchwtn/UniSmartPay): RFID and barcode campus payment system

A team project that lets students pay at the university restaurant and cafeteria with their student card. [Demo video](https://youtu.be/cDfxOyyTLME)

- I designed the concept and overall architecture: an RFID terminal, a web platform with admin, student and terminal roles, and a PHP/MySQL backend.
- I built the ESP32 firmware in C++ with AI tools: it reads card UIDs from an RC522 reader over SPI, checks the card with the server, and sends payment requests as JSON over HTTP with a per-terminal token.
- Two terminal modes (fixed-price restaurant ticket, cafeteria order built by scanning barcodes), LED feedback, a double-scan cooldown, and remote logging to a web serial monitor.

### [iwlwifi-5ghz-ap](https://github.com/clutchwtn/iwlwifi-5ghz-ap): 5 GHz hotspot on Intel Wi-Fi under Linux

A 14-line patch to the Linux `iwlwifi` driver so an Intel card can run a 5 GHz hotspot on channels 36-48 while staying connected to Wi-Fi, as Windows allows. I built it with AI tools and tested it on my own hardware. It lifts the "no IR" restriction only on channels the firmware itself marks as usable next to a station link, and never on radar (DFS) channels. Build and install scripts load the patched module alongside the stock one. Tested on an Intel AX211.

## What I work with

- **Embedded and IoT:** ESP32, C++ (Arduino framework), SPI, RFID (MFRC522), GPIO, HTTP/JSON
- **Languages:** C, C++, Java, Python, SQL, PHP, JavaScript
- **Tools:** Linux, Git, Docker, MySQL, Cisco Packet Tracer, Nmap

## Contact

- Email: jalel.fayache@gmail.com
- [LinkedIn](https://www.linkedin.com/in/jalel-fayache-78a40941b/)
- Member of the IEEE FST Student Branch, Robotics and Automation Society chapter
