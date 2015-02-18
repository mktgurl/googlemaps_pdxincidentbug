# googlemaps_pdxincidentbug
Been trying to figure out how to get persistent traffic incidents removed from Google Maps. 

2015-02-08: King County metro area incidents are showing up on the PDX metro area maps. 
Specifically, construction reported by WSDOT and accidents near Tacoma/Boeing have been
showing up on Interstate 5 between Vancouver, WA and Portland, OR mapping software. I
first saw this behavior in mid-January 2015 (see Issues log for screenshots).

If you navigate on Google Maps to "133 exit, Tacoma WA" and also to "Portland, OR" you'll 
see that this traffic alert shows up at both locations.

Looked at Bing Maps for comparison, and the closed road for Exit 133 in Tacoma, WA only
exists in Tacoma, WA.

Suspected inbound reporting sources: WA Dept of Transportation, Waze app, and however else
road incidents get published on Google Maps.
