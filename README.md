# meshviewer_hwpics
Hardware Pictures for meshviewer

The source of the pictures is:

    https://github.com/Moorviper/Freifunk-Router-Anleitungen

The hashes are generated with:

    https://meshdata.shivering-isles.com 

just paste the name of the router and click generate ...

As example: 

    TP-Link TL-WDR4300 v1

you will get:

    1367720599



### Usage:

Clone it to yout meshviewer/hopglass build folder and


add:


    "hwImg": [
    	{
    		"thumbnail": "nodes/{MODELHASH}.svg",
    		"caption": "Knoten {MODELHASH}"
    	}
    ]

to your config.json for meshviewer

### or
use it directly via cdn:

    "hwImg": [
        { "thumbnail": "https://cdn.rawgit.com/Moorviper/meshviewer_hwpics/master/nodes/{MODELHASH}.svg",
          "caption": "Knoten {MODELHASH}"
        }
      ]
      
 or directly without cdn:
 
     "hwImg": [
            { "thumbnail": "https://rawgit.com/Moorviper/meshviewer_hwpics/master/nodes/{MODELHASH}.svg",
              "caption": "Knoten {MODELHASH}"
            }
          ]
          
# License

The files are only copies of: https://github.com/Moorviper/Freifunk-Router-Anleitungen
named to match the hash function in Meshviever/HopGlass

All new drawn pictures except these for the virtual-maschines, the intel and AMD - Logos, and the raspberry-pi graphic (they are from other sources),
are released as:

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Namensnennung - Nicht-kommerziell - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>.
