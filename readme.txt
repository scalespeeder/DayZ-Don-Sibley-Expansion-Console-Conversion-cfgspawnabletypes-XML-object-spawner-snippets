Readme Instructions Containing Example cfggameplay.json objectSpawnersArr Code Snippets To Install Don Sibleys DayZ Expansion Conversion On Console Nitrado Servers, Detailing Files You Could Use

MANY THANKS TO DON SIBLEY AND THE EXPANSION TEAM!

Dons Video: https://youtu.be/yViVeVaGa-Q

Dons Github with the files required: https://github.com/DonSibleyGames/DayZ_Expansion_Console

PC Expansion On Steam: https://steamcommunity.com/workshop/filedetails/?id=2116151222

THESE INSTRUCTIONS ARE NOT AFFILIATED WITH DON SIBLEY OR THE EXPANSION PC MOD IN ANY WAY.

Please report bugs & errors with the below code to scalespeeder@gmail.com with screenshots.

-------------------------------------------------------------

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml / json files and instructions could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

I always recomend you validate your files at: https://www.xmlvalidation.com/ and https://jsonformatter.curiousconcept.com/

-------------------------------------------------------------

WITH UPDATE 1.21 SOME CUSTOM SPAWNED ITEMS REQUIRE AN OFFSET TO THEIR COORDINATES. THESE ARE THE FILES YOU SEE BELOW.
IF THIS HAS BEEN UPDATED WHEN YOU READ THESE INSTRUCTIONS, JUMP TO THE BOTTOM OF THIS DOCUMENT FOR THE FILE-NAMES WITHOUT OFFSETS.

All Chernarus Offset Exteriors AND All Interiors (Not recommended for any console, may work on PC Servers):

"objectSpawnersArr": ["custom/Berezino_With_Offsets.json","custom/Chernogorsk_Enhancement1_With_OffSets.json","custom/Chernogorsk_Enhancement2_With_OffSets.json","custom/Chernogorsk_Forrest_1_With_OffSets.json","custom/Chernogorsk_Forrest_2_With_OffSets.json","custom/ChernoGrass_1_With_Offsets.json","custom/ChernoGrass_2_With_Offsets.json","custom/ChernoHighSchool.json","custom/Elektrozavodsk_With_OffSets.json","custom/Evacuation_With_OffSets.json","custom/factory.json","custom/Gorka_With_OffSets.json","custom/GrassCoastRoad.json","custom/Kamenka_With_OffSets.json","custom/Kamyshovo_With_OffSets.json","custom/Krutoy_Cap_With_OffSets.json","custom/Myshkino_With_OffSets.json","custom/Nadezhdino_With_OffSets.json","custom/RandomStuff_With_OffSets.json","custom/Roads_With_OffSets.json","custom/Sea_Platform.json","custom/Solnechniy_With_OffSets.json","custom/Staroye_With_OffSets.json","custom/Svetloyarsk_1_With_OffSets.json","custom/Svetloyarsk_2_With_OffSets.json","custom/Tisy_With_OffSets.json","custom/Land_Barn_Brick2_Chernarus_Interior.json","custom/Land_Barn_Metal_Big_Chernarus_Interior.json","custom/Land_Barn_Wood2_Chernarus_Interior.json","custom/Land_City_Hospital_Chernarus_Interior.json","custom/Land_Garage_Big_Chernarus_Interior.json","custom/Land_Garage_Row_Big_Chernarus_Interior.json","custom/Land_House_1W01_Chernarus_Interior.json","custom/Land_House_1W02_Chernarus_Interior.json","custom/Land_House_1W03_Chernarus_Interior.json","custom/Land_House_1W04_Chernarus_Interior.json","custom/Land_House_1W05_Chernarus_Interior.json","custom/Land_House_1W06_Chernarus_Interior.json","custom/Land_House_1W07_Chernarus_Interior.json","custom/Land_House_1W08_Chernarus_Interior.json","custom/Land_House_1W09_Chernarus_Interior.json","custom/Land_House_1W10_Chernarus_Interior.json","custom/Land_House_1W11_Chernarus_Interior.json","custom/Land_House_1W12_Chernarus_Interior.json","custom/Land_House_2B01_Chernarus_Interior.json","custom/Land_House_2B02_Chernarus_Interior.json","custom/Land_House_2B03_Chernarus_Interior.json","custom/Land_House_2B04_Chernarus_Interior.json","custom/Land_House_2W01_Chernarus_Interior.json","custom/Land_House_2W02_Chernarus_Interior.json","custom/Land_House_2W03_Chernarus_Interior.json","custom/Land_House_2W04_Chernarus_Interior.json","custom/Land_Rail_Station_Big_Chernarus_Interior.json","custom/Land_Shed_Closed_Chernarus_Interior.json"],

All Interiors (Works on XBox Series S when used by themselves, Not Tested On Other Consoles):

"objectSpawnersArr": ["custom/Land_Barn_Brick2_Chernarus_Interior.json","custom/Land_Barn_Metal_Big_Chernarus_Interior.json","custom/Land_Barn_Wood2_Chernarus_Interior.json","custom/Land_City_Hospital_Chernarus_Interior.json","custom/Land_Garage_Big_Chernarus_Interior.json","custom/Land_Garage_Row_Big_Chernarus_Interior.json","custom/Land_House_1W01_Chernarus_Interior.json","custom/Land_House_1W02_Chernarus_Interior.json","custom/Land_House_1W03_Chernarus_Interior.json","custom/Land_House_1W04_Chernarus_Interior.json","custom/Land_House_1W05_Chernarus_Interior.json","custom/Land_House_1W06_Chernarus_Interior.json","custom/Land_House_1W07_Chernarus_Interior.json","custom/Land_House_1W08_Chernarus_Interior.json","custom/Land_House_1W09_Chernarus_Interior.json","custom/Land_House_1W10_Chernarus_Interior.json","custom/Land_House_1W11_Chernarus_Interior.json","custom/Land_House_1W12_Chernarus_Interior.json","custom/Land_House_2B01_Chernarus_Interior.json","custom/Land_House_2B02_Chernarus_Interior.json","custom/Land_House_2B03_Chernarus_Interior.json","custom/Land_House_2B04_Chernarus_Interior.json","custom/Land_House_2W01_Chernarus_Interior.json","custom/Land_House_2W02_Chernarus_Interior.json","custom/Land_House_2W03_Chernarus_Interior.json","custom/Land_House_2W04_Chernarus_Interior.json","custom/Land_Rail_Station_Big_Chernarus_Interior.json","custom/Land_Shed_Closed_Chernarus_Interior.json"],

Vertical Format:

"objectSpawnersArr": [
"custom/Land_Barn_Brick2_Chernarus_Interior.json",
"custom/Land_Barn_Metal_Big_Chernarus_Interior.json",
"custom/Land_Barn_Wood2_Chernarus_Interior.json",
"custom/Land_City_Hospital_Chernarus_Interior.json",
"custom/Land_Garage_Big_Chernarus_Interior.json",
"custom/Land_Garage_Row_Big_Chernarus_Interior.json",
"custom/Land_House_1W01_Chernarus_Interior.json",
"custom/Land_House_1W02_Chernarus_Interior.json",
"custom/Land_House_1W03_Chernarus_Interior.json",
"custom/Land_House_1W04_Chernarus_Interior.json",
"custom/Land_House_1W05_Chernarus_Interior.json",
"custom/Land_House_1W06_Chernarus_Interior.json",
"custom/Land_House_1W07_Chernarus_Interior.json",
"custom/Land_House_1W08_Chernarus_Interior.json",
"custom/Land_House_1W09_Chernarus_Interior.json",
"custom/Land_House_1W10_Chernarus_Interior.json",
"custom/Land_House_1W11_Chernarus_Interior.json",
"custom/Land_House_1W12_Chernarus_Interior.json",
"custom/Land_House_2B01_Chernarus_Interior.json",
"custom/Land_House_2B02_Chernarus_Interior.json",
"custom/Land_House_2B03_Chernarus_Interior.json",
"custom/Land_House_2B04_Chernarus_Interior.json",
"custom/Land_House_2W01_Chernarus_Interior.json",
"custom/Land_House_2W02_Chernarus_Interior.json",
"custom/Land_House_2W03_Chernarus_Interior.json",
"custom/Land_House_2W04_Chernarus_Interior.json",
"custom/Land_Rail_Station_Big_Chernarus_Interior.json",
"custom/Land_Shed_Closed_Chernarus_Interior.json"],

-------------------------------------------------------------

All Chernarus Offset Exteriors (Works on PC & Xbox Series S, Probably Xbox Series X & PS5)::

"objectSpawnersArr": ["custom/Berezino_With_Offsets.json","custom/Chernogorsk_Enhancement1_With_OffSets.json","custom/Chernogorsk_Enhancement2_With_OffSets.json","custom/Chernogorsk_Forrest_1_With_OffSets.json","custom/Chernogorsk_Forrest_2_With_OffSets.json","custom/ChernoGrass_1_With_Offsets.json","custom/ChernoGrass_2_With_Offsets.json","custom/ChernoHighSchool.json","custom/Elektrozavodsk_With_OffSets.json","custom/Evacuation_With_OffSets.json","custom/factory.json","custom/Gorka_With_OffSets.json","custom/GrassCoastRoad.json","custom/Kamenka_With_OffSets.json","custom/Kamyshovo_With_OffSets.json","custom/Krutoy_Cap_With_OffSets.json","custom/Myshkino_With_OffSets.json","custom/Nadezhdino_With_OffSets.json","custom/RandomStuff_With_OffSets.json","custom/Roads_With_OffSets.json","custom/Sea_Platform.json","custom/Solnechniy_With_OffSets.json","custom/Staroye_With_OffSets.json","custom/Svetloyarsk_1_With_OffSets.json","custom/Svetloyarsk_2_With_OffSets.json","custom/Tisy_With_OffSets.json"],

Vertical Format:

"objectSpawnersArr": [
"custom/Berezino_With_Offsets.json",
"custom/Chernogorsk_Enhancement1_With_OffSets.json",
"custom/Chernogorsk_Enhancement2_With_OffSets.json",
"custom/Chernogorsk_Forrest_1_With_OffSets.json",
"custom/Chernogorsk_Forrest_2_With_OffSets.json",
"custom/ChernoGrass_1_With_Offsets.json",
"custom/ChernoGrass_2_With_Offsets.json",
"custom/ChernoHighSchool.json",
"custom/Elektrozavodsk_With_OffSets.json",
"custom/Evacuation_With_OffSets.json",
"custom/factory.json",
"custom/Gorka_With_OffSets.json",
"custom/GrassCoastRoad.json",
"custom/Kamenka_With_OffSets.json",
"custom/Kamyshovo_With_OffSets.json",
"custom/Krutoy_Cap_With_OffSets.json",
"custom/Myshkino_With_OffSets.json",
"custom/Nadezhdino_With_OffSets.json",
"custom/RandomStuff_With_OffSets.json",
"custom/Roads_With_OffSets.json",
"custom/Sea_Platform.json",
"custom/Solnechniy_With_OffSets.json",
"custom/Staroye_With_OffSets.json",
"custom/Svetloyarsk_1_With_OffSets.json",
"custom/Svetloyarsk_2_With_OffSets.json",
"custom/Tisy_With_OffSets.json"],

-------------------------------------------------------------

ALL Offsets, with smallest files first (Works on PC & Xbox Series S, Probably Xbox Series X & PS5):

"objectSpawnersArr": [
"custom/factory.json",
"custom/Sea_Platform.json",
"custom/ChernoHighSchool.json",
"custom/Krutoy_Cap_With_OffSets.json",
"custom/RandomStuff_With_OffSets.json",
"custom/Kamenka_With_OffSets.json",
"custom/Gorka_With_OffSets.json",
"custom/Tisy_With_OffSets.json",
"custom/Staroye_With_OffSets.json",
"custom/Solnechniy_With_OffSets.json",
"custom/Nadezhdino_With_OffSets.json",
"custom/Myshkino_With_OffSets.json",
"custom/Chernogorsk_Forrest_2_With_OffSets.json",
"custom/Chernogorsk_Forrest_1_With_OffSets.json",
"custom/Evacuation_With_OffSets.json",
"custom/Chernogorsk_Enhancement2_With_OffSets.json",
"custom/GrassCoastRoad.json",
"custom/Roads_With_OffSets.json",
"custom/Berezino_With_Offsets.json",
"custom/Chernogorsk_Enhancement1_With_OffSets.json",
"custom/Kamyshovo_With_OffSets.json",
"custom/ChernoGrass_2_With_Offsets.json",
"custom/Elektrozavodsk_With_OffSets.json",
"custom/ChernoGrass_1_With_Offsets.json",
"custom/Svetloyarsk_1_With_OffSets.json",
"custom/Svetloyarsk_2_With_OffSets.json"],

-------------------------------------------------------------

Working Offsets, with smallest files first, works on PS4 (& Perhaps Xbox One Varients) (3580kb of files NOT assets):

"objectSpawnersArr": [
"custom/factory.json",
"custom/Sea_Platform.json",
"custom/ChernoHighSchool.json",
"custom/Krutoy_Cap_With_OffSets.json",
"custom/RandomStuff_With_OffSets.json",
"custom/Kamenka_With_OffSets.json",
"custom/Gorka_With_OffSets.json",
"custom/Tisy_With_OffSets.json",
"custom/Staroye_With_OffSets.json",
"custom/Solnechniy_With_OffSets.json",
"custom/Nadezhdino_With_OffSets.json",
"custom/Myshkino_With_OffSets.json",
"custom/Elektrozavodsk_With_OffSets.json"],

-------------------------------------------------------------

Files With Size, in kb, for choosing which files to spawn in server, with PS4 Memory Budget of 3580kb.
(PLEASE NOTE THAT THIS IS A VERY ROUGH ESTIMATE OF THE MEMORY BUDGET AND PROBABLY NOT ACCURATE.)

factory.json 								            12
Sea_Platform.json 						        	30
ChernoHighSchool.json 					      	41
Krutoy_Cap_With_OffSets.json 			    	42
RandomStuff_With_OffSets.json 			  	155
Kamenka_With_OffSets.json 					    157
Gorka_With_OffSets.json 					      212
Tisy_With_OffSets.json 						      233
Staroye_With_OffSets.json 					    261
Solnechniy_With_OffSets.json 				    329
Nadezhdino_With_OffSets.json 				    394
Myshkino_With_OffSets.json 					    417
Chernogorsk_Forrest_2_With_OffSets.json		439
Chernogorsk_Forrest_1_With_OffSets.json 	500
Evacuation_With_OffSets.json 			      	525
Chernogorsk_Enhancement2_With_OffSets.json 	579
GrassCoastRoad.json 						          596
Roads_With_OffSets.json 				        	737
Berezino_With_Offsets.json 				      	758
Chernogorsk_Enhancement1_With_OffSets.json 	911
Kamyshovo_With_OffSets.json 			      	1027
ChernoGrass_2_With_Offsets.json 		    	1052
Elektrozavodsk_With_OffSets.json 		    	1290
ChernoGrass_1_With_Offsets.json 		    	1358
Svetloyarsk_1_With_OffSets.json 			    1754
Svetloyarsk_2_With_OffSets.json 			    1809

-------------------------------------------------------------
-------------------------------------------------------------

WITH UPDATE 1.21 SOME CUSTOM SPAWNED ITEMS REQUIRE AN OFFSET TO THEIR COORDINATES. IF THIS HAS BEEN UPDATED
WHEN YOU READ THESE INSTRUCTIONS, USE THE BELOW FILESNAMES WITH THE APPROPRIATE FILES FROM DONS GITHUB:

https://github.com/DonSibleyGames/DayZ_Expansion_Console

All Chernarus NON-Offset Exteriors (Works on PC & Xbox Series S, Probably Xbox Series X & PS5)::

"objectSpawnersArr": ["custom/Berezino_WithOut_Offsets.json","custom/Chernogorsk_Enhancement1_WithOut_Offsets.json","custom/Chernogorsk_Enhancement2_WithOut_Offsets.json","custom/Chernogorsk_Forrest_1_WithOut_Offsets.json","custom/Chernogorsk_Forrest_2_WithOut_Offsets.json","custom/ChernoGrass_1_WithOut_Offsets.json","custom/ChernoGrass_2_WithOut_Offsets.json","custom/ChernoHighSchool.json","custom/Elektrozavodsk_WithOut_Offsets.json","custom/Evacuation_WithOut_Offsets.json","custom/factory.json","custom/Gorka_WithOut_Offsets.json","custom/GrassCoastRoad.json","custom/Kamenka_WithOut_Offsets.json","custom/Kamyshovo_WithOut_Offsets.json","custom/Krutoy_Cap_WithOut_Offsets.json","custom/Myshkino_WithOut_Offsets.json","custom/Nadezhdino_WithOut_Offsets.json","custom/RandomStuff_WithOut_Offsets.json","custom/Roads_WithOut_Offsets.json","custom/Sea_Platform.json","custom/Solnechniy_WithOut_Offsets.json","custom/Staroye_WithOut_Offsets.json","custom/Svetloyarsk_1_WithOut_Offsets.json","custom/Svetloyarsk_2_WithOut_Offsets.json","custom/Tisy_WithOut_Offsets.json"],

Vertical Format:

"objectSpawnersArr": [
"custom/Berezino_WithOut_Offsets.json",
"custom/Chernogorsk_Enhancement1_WithOut_Offsets.json",
"custom/Chernogorsk_Enhancement2_WithOut_Offsets.json",
"custom/Chernogorsk_Forrest_1_WithOut_Offsets.json",
"custom/Chernogorsk_Forrest_2_WithOut_Offsets.json",
"custom/ChernoGrass_1_WithOut_Offsets.json",
"custom/ChernoGrass_2_WithOut_Offsets.json",
"custom/ChernoHighSchool.json",
"custom/Elektrozavodsk_WithOut_Offsets.json",
"custom/Evacuation_WithOut_Offsets.json",
"custom/factory.json",
"custom/Gorka_WithOut_Offsets.json",
"custom/GrassCoastRoad.json",
"custom/Kamenka_WithOut_Offsets.json",
"custom/Kamyshovo_WithOut_Offsets.json",
"custom/Krutoy_Cap_WithOut_Offsets.json",
"custom/Myshkino_WithOut_Offsets.json",
"custom/Nadezhdino_WithOut_Offsets.json",
"custom/RandomStuff_WithOut_Offsets.json",
"custom/Roads_WithOut_Offsets.json",
"custom/Sea_Platform.json",
"custom/Solnechniy_WithOut_Offsets.json",
"custom/Staroye_WithOut_Offsets.json",
"custom/Svetloyarsk_1_WithOut_Offsets.json",
"custom/Svetloyarsk_2_WithOut_Offsets.json",
"custom/Tisy_WithOut_Offsets.json"],

-------------------------------------------------------------

ALL NON-Offsets, with smallest files first (Works on PC & Xbox Series S, Probably Xbox Series X & PS5):

"objectSpawnersArr": [
"custom/factory.json",
"custom/Sea_Platform.json",
"custom/ChernoHighSchool.json",
"custom/Krutoy_Cap_WithOut_Offsets.json",
"custom/RandomStuff_WithOut_Offsets.json",
"custom/Kamenka_WithOut_Offsets.json",
"custom/Gorka_WithOut_Offsets.json",
"custom/Tisy_WithOut_Offsets.json",
"custom/Staroye_WithOut_Offsets.json",
"custom/Solnechniy_WithOut_Offsets.json",
"custom/Nadezhdino_WithOut_Offsets.json",
"custom/Myshkino_WithOut_Offsets.json",
"custom/Chernogorsk_Forrest_2_WithOut_Offsets.json",
"custom/Chernogorsk_Forrest_1_WithOut_Offsets.json",
"custom/Evacuation_WithOut_Offsets.json",
"custom/Chernogorsk_Enhancement2_WithOut_Offsets.json",
"custom/GrassCoastRoad.json",
"custom/Roads_WithOut_Offsets.json",
"custom/Berezino_WithOut_Offsets.json",
"custom/Chernogorsk_Enhancement1_WithOut_Offsets.json",
"custom/Kamyshovo_WithOut_Offsets.json",
"custom/ChernoGrass_2_WithOut_Offsets.json",
"custom/Elektrozavodsk_WithOut_Offsets.json",
"custom/ChernoGrass_1_WithOut_Offsets.json",
"custom/Svetloyarsk_1_WithOut_Offsets.json",
"custom/Svetloyarsk_2_WithOut_Offsets.json"],

-------------------------------------------------------------

Working NON-Offsets, with smallest files first, works on PS4 (& Perhaps Xbox One Varients) (3580kb of files NOT assets):

"objectSpawnersArr": [
"custom/factory.json",
"custom/Sea_Platform.json",
"custom/ChernoHighSchool.json",
"custom/Krutoy_Cap_WithOut_Offsets.json",
"custom/RandomStuff_WithOut_Offsets.json",
"custom/Kamenka_WithOut_Offsets.json",
"custom/Gorka_WithOut_Offsets.json",
"custom/Tisy_WithOut_Offsets.json",
"custom/Staroye_WithOut_Offsets.json",
"custom/Solnechniy_WithOut_Offsets.json",
"custom/Nadezhdino_WithOut_Offsets.json",
"custom/Myshkino_WithOut_Offsets.json",
"custom/Elektrozavodsk_WithOut_Offsets.json"],

-------------------------------------------------------------

Thanks, Rob.
