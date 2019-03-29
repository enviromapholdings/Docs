Requirements & Download Links
==============================

The following contains the requirements for the various applications that make up EnviroMap. If you have any questions please contact support@enviromap.com.  

**In this article:**
	- `EnviroMap Application Requirements`_
	- `Printer Requirements`_
	- `EnviroMap Local Printer Application Requirements`_
	- `Zebra Browser Print Requirements`_
	- `Calibration Instructions`_
	- `Printer Firmware Update Instructions`_

EnviroMap Application Requirements
-----------------------------------
1. Windows 10
2. Google Chrome

Printer Requirements
---------------------
1. EnviroMap Local Printer Application or Zebra Browser Print installed
2. ZPL compatible printer attached to local computer via USB or by Ethernet to the LAN

.. _EnviroMap Local Printer Application Requirements:
.. _Zebra Test Form Application:

EnviroMap Local Printer Application Requirements
-------------------------------------------------
.. attention::

	EnviroMap Local Printer Application must be installed for each user on each PC that will need to print

1. Server with at least Microsoft Windows Server 2008 R2 installed or PC with at least Microsoft Windows 7 installed (Windows 8.x and 10 work as well)
2. EnviroMap Local Printer Application Installation Walkthrough downloaded (http://print.managementsolutionsofva.com/downloads/HowtoInstallEnviroMapLocalPrintClientUSB.pdf)
3. Zebra Setup Utilities downloaded and installed (http://print.managementsolutionsofva.com/downloads/zsu-1191204.exe)
4. Choose either A or B below depending on the model of your Zebra printer
	A. Zebra GX420d - EnviroMap Local Printer Application* downloaded and installed (http://print.managementsolutionsofva.com/downloads/zebraprinter.zip)
	B. Zebra ZD410 - EnviroMap Local Printer Application* downloaded and installed (http://print.managementsolutionsofva.com/downloads/zebraprinternew.zip)
5. If remote support is necessary, TeamViewer 10 Host downloaded and installed (http://get.teamviewer.com/enviromap) or TeamViewer 10 QuickSupport downloaded and running (http://download.teamviewer.com/download/version_10x/TeamViewerQS.exe). The 9-digit TeamViewer ID and password must also be provided to support@enviromap.com

*Utilizes Zebra Test Form Application (©2016 ZIH Corp)

.. _Zebra Browser Print Requirements

Zebra Browser Print Requirements
-------------------------------------------------
.. attention::

	Zebra Browser Print Application must be installed for each user on each PC that will need to print.

1. Download & install the Zebra Browser print application (https://www.zebra.com/us/en/products/software/barcode-printers/link-os/browser-print.html)

.. attention:: 
	Steps to install Zebra Browser Print:
		1. Check that Chrome is the Default Browser
		2. In Chrome, navitgate to chrome://flags/#allow-insecure-localhost and select Enable
		3. Restart Chrome
		4. Set up printer
			1. Plug in printer to power and computer
			2. Make sure roll of labels is in correctly
			3. Turn on the printer
			4. Hold pause and cancel buttons down simultaneously for 2 seconds to activate the printer's auto-calibration.
		5. Download the Browser Print application found `here <https://www.zebra.com/us/en/products/software/barcode-printers/link-os/browser-print.html>`_.
		6. Follow the installation instructions for Browser Print found `here <https://www.zebra.com/content/dam/zebra_new_ia/en-us/solutions-verticals/product/Software/Printer%20Software/Link-OS/browser-print/software-browser-print-user-guide-en-us.pdf>`_.
			1. If the text shown in step 10 does not appear in the browser, you may have to click on the "lock" icon found to the left of the web address to add the certificate
			2. Again, an unlikely scenario, but you can follow the instructions found in the answer `here <https://superuser.com/questions/104146/add-permanent-ssl-certificate-exception-in-chrome-linux>`_, which may help grant access to the browser print certificate.
		7. Open browser print as shown in the installation instructions page 8.
		8. If the printer is not shown in the default devices, follow the instructions on pages 8 and 9 to add the printer.
			1. note: the printer must be plugged in and turned on for the Browser Print application to detect it.
		9.The printer should now be installed and detected by Browser print. you can test Enviromap functionality by going to any collection and selecting Print -> Print Labels. If the printer is the default device in browser print, it should show up in the print labels blade.
2. The following printers are supported:
    - QLn series
    - ZT200™ series
    - ZT400™ series
    - ZD500™ series
    - ZD400™ series
    - LP2824+
    - GK420
    - GX420

2. The following types of connectivity are supported:
    - USB
    - Network

3. The application supports the following Operating Systems & Browsers:
    - Windows 7, Windows 10 and Mac OSX
    - Chrome v51 or later

.. _Calibration Instructions:

Calibration Instructions
-------------------------
1. If you are using the EnviroMap Local Printer Application, download and unzip the calibration label, double-click the label, and a calibration label will print. (http://print.managementsolutionsofva.com/downloads/CalibrationLabel.zip)

.. _Printer Firmware Update Instructions:

Printer Firmware Update Instructions
-------------------------
1. Verify the model of your Zebra printer and download the latest firmware version below:
	A. Zebra GX420d: http://print.managementsolutionsofva.com/downloads/v56-17-17z.exe
	B. Zebra ZD410: http://print.managementsolutionsofva.com/downloads/v77-20-01z.exe
2. Follow the detailed instructions for your printer:
	A. Zebra GX420d: http://print.managementsolutionsofva.com/downloads/HowtoUpdateZebraGX420dFirmware.pdf
	B. Zebra ZD410: http://print.managementsolutionsofva.com/downloads/HowtoUpdateZebraZD410Firmware.pdf
