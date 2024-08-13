# bluecat-bulkmac-import

This imports a list of MAC addresses to a pool in BlueCat Address Manager.

- Install UI.Vision's browser extension https://ui.vision/
- Import the file bluecat-bulkmac-import in UI.Vision's browser extension.
- Import maclist.csv in the CSV tab.  Format is one MAC address per line.
- Close all browser windows, close the extension's window.
- Open a browser and navigate to the MAC adding page in Proteus.
- Open the UI.Vision browser extension, choose bulkmac, then click Play Macro.

Note: script timeout on line 1 of bulkmac is set to 20 minutes/1200 seconds, which should be fine for several hundred MACs.
