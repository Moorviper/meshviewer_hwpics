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



== Usage: ==

Clone it to yout meshviewer build folder and


add:


    "hwImg": [
    	{
    		"thumbnail": "nodes/{MODELHASH}.svg",
    		"caption": "Knoten {MODELHASH}"
    	}
    ]

to your config.json for meshviewer