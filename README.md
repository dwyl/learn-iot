# learn-raspberry-pi-iot
Learn how to build Internet of Things (IoT) Apps using Raspberry Pi and JavaScript!

<img src="https://www.raspberrypi.org/wp-content/uploads/2012/03/raspberry-pi-logo.png" width="40%" style="display: block; margin: 0 auto;">

## *Why*?

A **[Raspberry Pi](https://vimeo.com/90103691)** (Raspberry Pi) is a 'mini computer' that was created to help people learn about the basics of computers. They are _great_ for resource to get started on learning about hardware as they consist of the basic components of a computer. Raspberry Pi can run on an OS, which means that we can talk to the computer with higher level languages like Javascript!

## *What*?
**Internet Of Things (IoT)** describes the [internetworking of physical devices](https://en.wikipedia.org/wiki/Internet_of_things)... that basically means that multiple systems (e.g. computers and microprocessors) can talk to each other to do _awesome_ things.

<img src="https://pbs.twimg.com/media/Bl7pVeHCEAAXJxl.jpg" width="80%" style="display: block; margin: 0 auto;">

An example is a 'Smart Home' which might consist of a thermometer, microprocessor, a server and a mobile. The thermometer might _measure_ the temperature of a room; the microprocessor might _read_ the temperature every 5 minutes and _send_ those results to a computer. This computer might then _save_ each measurement and send them to the Home Owner, displaying the measurements in the form of a _graph_ so that they can easily see their energy consumption.

**Raspberry Pi** runs on a Linux OS, called Raspbian.

#### Background links:
* [Introduction to Raspberry Pi](https://www.raspberrypi.org/help/faqs/#introWhatIs)

## *How*?
A detailed set of instructions on how to install NodeJS onto Raspberry Pi can be found [here](http://thisdavej.com/beginners-guide-to-installing-node-js-on-a-raspberry-pi/). In addition to simple installation, the instructions in this link also covers getting WiFi on Raspberry Pi 2, setting up Remote Desktop and Windows File Share.

In summary we need to know:
(1) Equipment
(2) Get Raspbian OS
(3) Boot Raspberry Pi
(4) Install NodeJS

##### (1) Equipment:
- Laptop with Windows/Linux/OS X
- microSD card (8GB or more)
- microSD - SD card adapter
- Micro USB power supply
- HDMI cable
- Keyboard (USB)
- Mouse (USB)
- Raspberry Pi 2 + USB WiFi adapter OR Raspberry Pi 3

##### (2) Get Raspbian OS:
To do this, you'll need to download two things; _Raspbian OS_ (Raspberry Pi's official operating system) and _Etcher_.

(1) Download the latest Raspbian OS: go to https://www.raspberrypi.org/downloads/raspbian/ and you'll get two options; click 'Download ZIP' of "Raspbian Jessie With Pixel" <img src="https://cloud.githubusercontent.com/assets/13470325/24296813/847e0872-1098-11e7-80bb-96a3e3e246c7.png" width="80%" style="display: block; margin: 0 auto;">

(2) Download Etcher: go to https://etcher.io/ and click 'Download'
<img src="https://cloud.githubusercontent.com/assets/13470325/24297158/9a6f1e90-1099-11e7-86ef-ca8acddaae3c.png" width="80%" style="display: block; margin: 0 auto;">

(3) Put your microSD card into your SD card adapter, and insert into your laptop.

(4) Once Raspbian OS and Etcher have downloaded, open Etcher. You'll see something like the following open: .

- Click 'Select image', and select the Raspbian OS file (.zip) that you just downloaded.
- Click 'Select drive', and select your microSD/SD card.
- (Make sure you've selected the right options above! Then) Click 'Flash!'; this will write the OS to the microSD. (Takes ~10mins)
- Once this is complete, remove the microSD/SD from your laptop.

(5) Take the microSD card out of the adapter, and put it into the Raspberry Pi. Connect the Keyboard and Mouse by USB. Connect the Raspberry Pi to a monitor (or TV) with an HDMI cable
