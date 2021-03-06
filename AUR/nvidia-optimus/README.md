
<p align="center">
  <img src="https://i.imgur.com/gkdq7EZ.jpg " alt="nvidiatuxlogo"/>
</p>

##<p align="center">Bumblebee, DKMS, Primus, NVIDIA Drivers and extras <br/>PKGBUILDs for Arch Linux <br/></p>

<hr/>

**WARNING: PKGBUILDs are designed mostly for x86_64 based system.<br/>**
**Don't try installing these packages on Manjaro caused due MHWD restrictions! You have been warned.<br/>**
**DKMS based sources are ready for stable Linux Kernel.**

### CONTENTS ###

| **PACKAGE**             	| **VERSION**           	| **DESCRIPTION**                                                                                                                                                                                              	|
|-------------------------	|-----------------------	|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| `acpi_call-dkms`              | `1.1.0-4`                     | Kernel module that enables calls to ACPI methods through `/proc/acpi/call`. **DKMS version**.                                                                                                                 |
| `bbswitch-dkms`               | `0.8-49`                      | Kernel module allowing to switch dedicated graphics card on Optimus laptops. **DKMS version**.                                                                                                                |
| `bumblebee-git`             	| `1:20160512-1`                | NVIDIA Optimus support for Linux through VirtualGL. Forked. Included patches for unloading nvidia modules via libkmod2 [pull762](https://github.com/Bumblebee-Project/Bumblebee/pull/762) , fixes for [bug573](https://github.com/Bumblebee-Project/Bumblebee/issues/573).|
| `bumblebeed-resume-git` 	| `20160528-1`                  | Simple systemd service for restart bumblebeed service after resume                                                                                                                                            |
| `dkms`                  	| `2.2.0.3+git151023-10`        | Dynamic Kernel Modules System                                                                                                                                                                                	|
| `lib32-libglvnd`        	| `0.1.0.20160411-1`            | The GL Vendor-Neutral Dispatch library **(32-bit)**                                                                                                                                                           |
| `lib32-mesa`        	        | `11.2.1-1`    	        | An open-source implementation of the OpenGL specification **(32-bit)**                                                                                                                                        |
| `lib32-nvidia-utils`    	| `367.18-1`            	| NVIDIA drivers utilities **(32-bit)**                                                                                                                                                                       	|
| `lib32-primus`          	| `20151110-3`          	| Faster OpenGL offloading for Bumblebee **(32-bit)**                                                                                                                                                       	|
| `lib32-virtualgl`       	| `2.5-2`               	| **32-bit** serverside components for 64-bit VirtualGL servers                                                                                                                                                	|
| `libglvnd`              	| `0.1.0.20160411-1`    	| The GL Vendor-Neutral Dispatch library                                                                                                                                                                      	|
| `mesa`        	        | `11.2.1-1`                    | An open-source implementation of the OpenGL specification                                                                                                                                                     |
| `nvidia-dkms`           	| `367.18-1`            	| NVIDIA driver sources for Linux. **DKMS version**.                                                                                                                                                            |
| `nvidia-settings`       	| `364.19-1`            	| Tool for configuring the NVIDIA graphics driver                                                                                                                                                              	|
| `nvidia-utils`          	| `367.18-1`            	| NVIDIA drivers utilities                                                                                                                                                                                     	|
| `primus`                	| `20151110-5`          	| Faster OpenGL offloading for Bumblebee                                                                                                                                                                       	|
| `virtualgl`             	| `2.5-2`               	| Redirects 3D commands from an OpenGL application onto a server-side 3D graphics card                                                                                                                         	|

<hr/>

All trademarks are the property of their respective owners.
