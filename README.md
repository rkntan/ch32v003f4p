
# ch32v003f4p

collection of firmware projects for the wch ch32v003f4p6 risc-v microcontroller.

the **ch32v003 series** is programmed using the proprietary **wch-linke** programmer. this is a **low-cost, single-wire programming interface** that also supports **single-wire debugging** (swd). the official programmer additionally includes a **usb-to-ttl serial interface**, which can be used to monitor **debug output**.

https://www.mounriver.com/download

used: **mounriverstudio_linux_x64_v240**


## projects
* **ch32v003f4p-usart**: serial communication routine that receives data and sends back the bitwise inverted value.

## environment
* **os**: ubuntu 24.04 lts (noble)
* **ide**: mounriver studio (mrs)
* **toolchain**: risc-v embedded gcc (integrated in mrs)
* **hardware**: ch32v003f4p6-evt-r0 + wch-linke debugger

## setup notes

## references

### articles
* [low-cost microcontrollers using a ch32v003 risc-v device — element14 community](https://community.element14.com/technologies/embedded/b/blog/posts/low-cost-microcontrollers-using-a-ch32v003-risc-v-device)

### docs
* [ch32v003 datasheet](docs/CH32V003-datasheet.pdf)
* [ch32v003 reference manual](docs/CH32V003-reference-manual.pdf)
* [wch-link user manual](docs/WCH-LinkUserManual.pdf)
