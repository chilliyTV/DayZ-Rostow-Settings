here i added two spooky Areas around the Big Castles on the DayZ Map Rostow.

add this into your:

\mpmissions\Offline.rostow\cfgEffectArea.json


		{ 	"AreaName": "MievaCastle",    
		"Type": "ContaminatedArea_Static", 
		"TriggerType": "effecttrigger",
		"Data": { 
			"Pos": [ 2888, 0, 5642 ], 
			"Radius": 150,
			"PosHeight": 50,
			"NegHeight": 15,
			"InnerRingCount": 2,
			"InnerPartDist": 50,
			"OuterRingToggle": 1, 
			"OuterPartDist": 50, 
			"OuterOffset": 0, 
			"VerticalLayers": 0,
			"VerticalOffset": 0,
			"ParticleName": "graphics/particles/spooky_mist"
			},
		"PlayerData": {
			"AroundPartName": "graphics/particles/",
			"TinyPartName": "graphics/particles/",
			"PPERequesterType": ""
		}
	},

	{ 	"AreaName": "OrschkaCastle",    
	"Type": "ContaminatedArea_Static", 
	"TriggerType": "effecttrigger",
	"Data": { 
		"Pos": [ 7109, 0, 12401], 
		"Radius": 150,
		"PosHeight": 50,
		"NegHeight": 15,
		"InnerRingCount": 2,
		"InnerPartDist": 50,
		"OuterRingToggle": 1, 
		"OuterPartDist": 50, 
		"OuterOffset": 0, 
		"VerticalLayers": 0,
		"VerticalOffset": 0,
		"ParticleName": "graphics/particles/spooky_mist"
		},
	"PlayerData": {
		"AroundPartName": "graphics/particles/",
		"TinyPartName": "graphics/particles/",
		"PPERequesterType": ""
	}
}
