# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?avoid=highways&mode=bicycling&origin=Sydney+Harbour+Bridge,+Sydney+NSW,+Australia&waypoints=Sydney+Opera+House,+Sydney+NSW,+Australia|via:Royal+Botanic+Garden+Sydney,+Mrs+Macquaries+Road,+Sydney+NSW,+Australia&destination=Australian+National+Maritime+Museum,+Murray+Street,+Sydney+NSW,+Australia&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "partial_match" : true,
         "place_id" : "ChIJ49XqJV2uEmsRPsTAF7eOlGg",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "partial_match" : true,
         "place_id" : "ChIJ3S-JXmauEmsRUcIaWtf4MzE",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "partial_match" : true,
         "place_id" : "ChIJWaTdYGuuEmsRoOfx-Wh9AQ8",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJTze93zmuEmsRhvE6T4Y9DhU",
         "types" : [ "establishment", "museum", "point_of_interest", "tourist_attraction" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : -33.8587798,
               "lng" : 151.2136691
            },
            "southwest" : {
               "lat" : -33.8708537,
               "lng" : 151.1980737
            }
         },
         "copyrights" : "Map data ©2023",
         "legs" : [
            {
               "distance" : {
                  "text" : "1.4 km",
                  "value" : 1378
               },
               "duration" : {
                  "text" : "5 mins",
                  "value" : 314
               },
               "end_address" : "Bennelong Point, Sydney NSW 2000, Australia",
               "end_location" : {
                  "lat" : -33.8587986,
                  "lng" : 151.2135295
               },
               "start_address" : "Sydney Harbour Bridge, Sydney Harbour Bridge, Sydney NSW, Australia",
               "start_location" : {
                  "lat" : -33.8589114,
                  "lng" : 151.2067996
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "48 m",
                        "value" : 48
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : -33.8592148,
                        "lng" : 151.2070345
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e toward \u003cb\u003eCumberland St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eTake the stairs\u003c/div\u003e",
                     "polyline" : {
                        "points" : "datmEoq{y[B@@C?ADQDO@A@A@?B?F@@?B?@?B?@?@A@?DC"
                     },
                     "start_location" : {
                        "lat" : -33.8589114,
                        "lng" : 151.2067996
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 291
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : -33.8616724,
                        "lng" : 151.2059642
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCumberland St\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "`ctmE}r{y[VFn@Rp@T\\LB?hA\\ZJXJRHZJ^Lj@RrAf@"
                     },
                     "start_location" : {
                        "lat" : -33.8592148,
                        "lng" : 151.2070345
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 171
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : -33.8622503,
                        "lng" : 151.207684
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eEssex St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "lrtmEgl{y[T}@FQHYb@iBXsALo@"
                     },
                     "start_location" : {
                        "lat" : -33.8616724,
                        "lng" : 151.2059642
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 122
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : -33.8612724,
                        "lng" : 151.2082788
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGeorge St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "`vtmE_w{y[]Sq@[MIcAi@a@S"
                     },
                     "start_location" : {
                        "lat" : -33.8622503,
                        "lng" : 151.207684
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "85 m",
                        "value" : 85
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : -33.8613771,
                        "lng" : 151.209187
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAlfred St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "|otmEwz{y[HqAD{@Dg@"
                     },
                     "start_location" : {
                        "lat" : -33.8612724,
                        "lng" : 151.2082788
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "70 m",
                        "value" : 70
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : -33.8608811,
                        "lng" : 151.2095573
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at \u003cb\u003ePitt St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "rptmEm`|y[UAc@Ei@aA"
                     },
                     "start_location" : {
                        "lat" : -33.8613771,
                        "lng" : 151.209187
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 521
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 103
                     },
                     "end_location" : {
                        "lat" : -33.8590807,
                        "lng" : 151.2129842
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "nmtmEwb|y[RMDEDK@KLaC@GDoA@IDuA@QN_C?C?O?ECIEKGIEGGIIIGGIGMGECICKCOAk@G_@A_@CGA_AIg@Ec@Gg@EMCME"
                     },
                     "start_location" : {
                        "lat" : -33.8608811,
                        "lng" : 151.2095573
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "25 m",
                        "value" : 25
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : -33.8589618,
                        "lng" : 151.2131498
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eMacquarie St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "fbtmEcx|y[@I?A@??A?A?AAAAAICMG"
                     },
                     "start_location" : {
                        "lat" : -33.8590807,
                        "lng" : 151.2129842
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "45 m",
                        "value" : 45
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : -33.8587986,
                        "lng" : 151.2135295
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMacquarie St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "natmEey|y[CAGEIGAAACACCICYAC@A?ABE"
                     },
                     "start_location" : {
                        "lat" : -33.8589618,
                        "lng" : 151.2131498
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "3.0 km",
                  "value" : 3031
               },
               "duration" : {
                  "text" : "12 mins",
                  "value" : 746
               },
               "end_address" : "2 Murray St, Sydney NSW 2000, Australia",
               "end_location" : {
                  "lat" : -33.869503,
                  "lng" : 151.1982169
               },
               "start_address" : "Bennelong Point, Sydney NSW 2000, Australia",
               "start_location" : {
                  "lat" : -33.8587986,
                  "lng" : 151.2135296
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "6 m",
                        "value" : 6
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : -33.8587971,
                        "lng" : 151.2135962
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eMacquarie St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "n`tmEq{|y[?A?AA??A?A?A@??A?A"
                     },
                     "start_location" : {
                        "lat" : -33.8587986,
                        "lng" : 151.2135296
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "29 m",
                        "value" : 29
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : -33.858967,
                        "lng" : 151.2135422
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eMacquarie St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "n`tmE_||y[?A?A@??A?A@??A@?@A@??A@?@?@?@?@??@@?@??@@??@@??@@??@?@@??@?@?@@??@?@?@?@"
                     },
                     "start_location" : {
                        "lat" : -33.8587971,
                        "lng" : 151.2135962
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "20 m",
                        "value" : 20
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : -33.8591381,
                        "lng" : 151.2134732
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eMacquarie St\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "patmEs{|y[FBHBB?JD"
                     },
                     "start_location" : {
                        "lat" : -33.858967,
                        "lng" : 151.2135422
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 829
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 288
                     },
                     "end_location" : {
                        "lat" : -33.8665413,
                        "lng" : 151.2124279
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eMacquarie St\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "rbtmEe{|y[r@Hx@HJ@b@DpALP@V@TBtBJf@FP?^BT@RDJ@f@D@@`CLZBd@DZ@p@B\\B|@F|@HH@x@F^BhAFdAJVBF?z@HZBH@f@D\\B"
                     },
                     "start_location" : {
                        "lat" : -33.8591381,
                        "lng" : 151.2134732
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 366
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 68
                     },
                     "end_location" : {
                        "lat" : -33.8656175,
                        "lng" : 151.2086708
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHunter St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "zpumEut|y[KbBW`BATIfAEl@En@?FCVALGh@OfAENc@fAc@jAOh@"
                     },
                     "start_location" : {
                        "lat" : -33.8665413,
                        "lng" : 151.2124279
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "43 m",
                        "value" : 43
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : -33.8652298,
                        "lng" : 151.208711
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePitt St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "bkumEe}{y[G?CAaAE"
                     },
                     "start_location" : {
                        "lat" : -33.8656175,
                        "lng" : 151.2086708
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 132
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : -33.8650685,
                        "lng" : 151.2073234
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCurtin Pl\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "thumEm}{y[E|AAVC|@Ch@Ab@MR"
                     },
                     "start_location" : {
                        "lat" : -33.8652298,
                        "lng" : 151.208711
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 292
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 94
                     },
                     "end_location" : {
                        "lat" : -33.8650981,
                        "lng" : 151.2041716
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eMargaret St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "tgumEwt{y[Cf@?`@E|AAjA?~AHrCFlC"
                     },
                     "start_location" : {
                        "lat" : -33.8650685,
                        "lng" : 151.2073234
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 411
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : -33.8687758,
                        "lng" : 151.204607
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eKent St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "zgumEaa{y[FANAdAId@C~@G|@Ev@EhEShBKz@Gt@I"
                     },
                     "start_location" : {
                        "lat" : -33.8650981,
                        "lng" : 151.2041716
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 104
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : -33.8687144,
                        "lng" : 151.2034815
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKing St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eParts of this road may be closed at certain times or days\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "z~umEyc{y[KbEA\\"
                     },
                     "start_location" : {
                        "lat" : -33.8687758,
                        "lng" : 151.204607
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 295
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 46
                     },
                     "end_location" : {
                        "lat" : -33.870817,
                        "lng" : 151.2024485
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "l~umEw|zy[@@@JBJDJ@BJTTXHHJHLHPFHBFBJ?hBBB?`@?D?t@@P?bA@@@@@?B?@?FADCd@"
                     },
                     "start_location" : {
                        "lat" : -33.8687144,
                        "lng" : 151.2034815
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 415
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 80
                     },
                     "end_location" : {
                        "lat" : -33.8699762,
                        "lng" : 151.1980751
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003ePyrmont Bridge\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "rkvmEivzy[CNALEZMhAAHE`@?DGh@MlAMrAEZ?@O`BU~BALCLIdACHIj@Ib@ABGVCN"
                     },
                     "start_location" : {
                        "lat" : -33.870817,
                        "lng" : 151.2024485
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12 m",
                        "value" : 12
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : -33.8698663,
                        "lng" : 151.1980737
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "jfvmE_{yy[U@"
                     },
                     "start_location" : {
                        "lat" : -33.8699762,
                        "lng" : 151.1980751
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "19 m",
                        "value" : 19
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : -33.8699318,
                        "lng" : 151.1982596
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "tevmE}zyy[Je@"
                     },
                     "start_location" : {
                        "lat" : -33.8698663,
                        "lng" : 151.1980737
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "58 m",
                        "value" : 58
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : -33.869503,
                        "lng" : 151.1982169
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "`fvmEc|yy[IC?@EJADABA@A@A@A?A@C?CAEAA?ICSIIA"
                     },
                     "start_location" : {
                        "lat" : -33.8699318,
                        "lng" : 151.1982596
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : [
                  {
                     "location" : {
                        "lat" : -33.8640057,
                        "lng" : 151.212796
                     },
                     "step_index" : 3,
                     "step_interpolation" : 0.6574732906217435
                  }
               ]
            }
         ],
         "overview_polyline" : {
            "points" : "datmEoq{y[B@@CDSFQZ?JExBp@pFfB~Bz@\\oAl@cCf@cCaDcBa@SHqAJcBy@Gi@aARMJQNmCNwDPeDCOMU_@c@g@W[EkAIoCUkAM[IBMAEKEc@WISCa@@K@GDIHCHBDJ@FTH~@NdAJfCTl@DtBJf@Fp@Bh@FvDV`AHlADbDVxAJnCRvBPp@F\\BKbBYvBOtBK|AWpBi@vAs@tBKAaAEE|AEtAElAMRCf@E~BAjDP`HVChF[`GYdDSt@IKbE?^Lf@`@n@TR^PPFzCBpCBBFEt@YbCq@zGk@|FMnASnAIZCNU@Je@ICELGLEBOC]MIA"
         },
         "summary" : "Cumberland St",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
