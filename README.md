# BinaryPlant.com ARP Defender

This tool just helps you to keep apr-record of your default gateway static.
BarpDef monitors arp-cache and logs any news records inside table.
It runs only on Windows 7/8/10 for now.

## How to install for Windows as exe-file
You can just download prebuilded MSI installation file at binaryplant.com/arp-defender/
Run .msi file and install it to some directory. Start.

That's all!

![ARP Defender](http://binaryplant.com/media/screenshot-arp-defender.png)
------------------------------------------------------------------------------------


## How to run as python script with GUI 
This software written on Python wih PyQT framework. So you need these for run.
1) [Python](https://www.python.org/downloads/) v3 - download and install it.
2) [PyQt5](http://pyqt.sourceforge.net/Docs/PyQt5/installation.html) by command:
```
> pip install pyqt5
```

3) Sources. Download as zip or git clone from https://github.com/KMiNT21/bintaryplant-arp-defender/

Run file:
```
> python barpdef.py
```


#### Building exe from sources
You need cx_Freeze lib.
```
> pip install cx_Freeze
```

Now you can make exe (by rules in setup.py)

For folder with all filese:
```
> python setup.py build
```

Generating solid MSI installation file:
```
> python.exe setup.py bdist_msi
```