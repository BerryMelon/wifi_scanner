# wifi_scanner
Scans nearby wifi using airodump and shows devices connected to the network.

## Usage
```
-i : interface to scan. default is "wlan1mon"
-c : channel to scan. If omitted will scan through channels from 1-12
-t : time scanning for each channel. default is 20 seconds
```

## Example
```
./scan -i wlan0mon -c 11 -t 20
```
will scan nearby networks with interface wlan0mon at channel 11 for 20 seconds.

## Return Value
The result will be saved in a formatted txt file. It will only show the Networks that have atleast one device connected.
