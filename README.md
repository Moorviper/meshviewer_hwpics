# meshviewer_hwpics
Hardware Pictures for meshviewer

The source of the pictures is:

    https://github.com/Moorviper/Freifunk-Router-Anleitungen

The hashes are generated with:

    https://meshdata.shivering-isles.com 
    (actually not working :-/ / working on a alternative)

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