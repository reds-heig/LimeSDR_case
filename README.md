# LimeSDR_case

Here you will find the LimeSDR case developed at the [REDS institute](https://reds.heig-vd.ch/). This case was designed using SolidWorks for 3D printing.

## BOM

The BOM contains a list of properly-sized heatsinks with order links, as well as adhesive foil, a 12VDC fan and SMA pigtails. You will have to acquire the screws by yourself.

## Mounting

After ordering all the parts, use the adhesive foil to mount the heatsinks on the corresponding chips. Use the *Remark* column in the BOM and the [PCB layout](https://github.com/myriadrf/LimeSDR-USB/blob/master/hardware/plug/1v4/Project%20Outputs%20for%20LimeSDR-USB_1v4_LMS031pad/LimeSDR-USB_1v4_PCB_Drawings.PDF) in order to know what goes where. The DC fan has to be soldered between J21 GND (black) and J21 VCC EXT (red). This way, it will be on whenever an external power supply is applied. The fan will work with 9VDC supplies as well, albeit at a lower speed.

## More information

A thermal analysis is available on [our blog](http://blog.reds.ch/?p=207).
