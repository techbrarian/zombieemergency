##########Bengtson-Fu 13 3 |\| ( ][ 5 () |\| - |= |_|!!!!!!###############

###created by Jason Bengtson, MLIS, AHIP : Available under Creative Commons non-commercial share alike open source license###


##built for the Robert M Bird Health Sciences Library- Go Sooners!###
###Bengtson-Fu is the best Kung Fu!!!###

# zombieemergency
A web based game designed to teach basic lessons about judging source authority with medical sources. 
Use case- raising visibility of libraries at public venues. Others very possible.

This game uses a number of random number generators to provide a uniqiue gameplay experience each time. The map
is powered with an HTML 5 canvas element. News stories are javascript objects. New ones may be created by editing
the infopanelcontents.js file.The first articles shown have type "Start". Others have type "Main". Articles must
display only when conditions make them relevant (i.e.- if barrier nursing is more effective than quarantine, the pro
barrier nursing artilces appear). This is controlled with the "id">number attribute for treatments (1 for anti-virals
 2 for vaccines, 3 for interferon, all threee for articles relevant to mitigation rather than treatment) and the 
 "stop">number attribute for mitigation strategies (1 for quarantine, 2 for barrier nursing, both for articles where
 it doesn't matter)
 
 The game has lots of comments in the source code; pay attention to them. It uses jQuery UI for the ui appliances.
 It is not responsively designed and it built for normal to semi-wide screens.
 Infected zones are built dynamically as javascript objects and redrawn each turn along with the map.
 Winning or losing is tested by counting the red pixels on the map at the end of each turn.
 
