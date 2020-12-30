# gotor_g8_a1284p_bootloader
atmel A1284P bootloader for arduino

1.Download the latest Arduino IDE
2.Download the Gotor G8 board definition(https://github.com/GotorOfficial/gotor_g8_a1284p)
or(https://github.com/GotorOfficial/gotor_g8_a1284p_bootloader)
3.Follow the readme (i.e. place it in My Documents\Arduino\hardware)
4.Download the latest Marlin 2.0 firmware(https://github.com/GotorOfficial/Marlin)
5.Extract the downloaded archive
6.Navigate to \config\examples\Anet\A8plus
7.Copy both files to \Marlin
8.Open \Marlin\Marlin.ino
9.Go to Tools > Board: “…” > Select gotor V1.0 (Optiboot) if this doesn’t show restart Arduino IDE.
10.Click “Verify/Build” (you might see some warnings)
11.If this throws an error like:
(1)u8glib.h: No such file or directory
Sketch > Include Library > Manage libraries
(2)Wait for download to finish
(3)In the “Filter your search” box, type “u8glib”.
(4)Scroll down until you see “U8glib by oliver”. Click on it.
(5)Click “Install”
(6)Wait for installation to finish
(7)Click “Close”
(8)Click “Verify/Build” again to retry
12.Connect the Anet A8 Plus to your computer
13.Click “Upload”
14.Voila your Anet A8 Plus is now equipped with Marlin 2.0
