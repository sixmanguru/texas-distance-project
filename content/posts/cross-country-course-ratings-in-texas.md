---
title: "Cross Country Course Ratings in Texas"
date: 2025-10-04T01:00:50
slug: "cross-country-course-ratings-in-texas"
description: "Over the past year or so I have collected data from cross country races across the state. By setting a single meet at a distance I was almost 100% confident about (not 5000m), I have written a program to estimate an equivalent distance for every meet across the state. I do not list all of"
categories: ["articles"]
tags: ["Athletic dot Net", "cross country", "high school", "middle distance", "Milesplit", "ratings", "running", "Texas", "UIL", "XC"]
draft: false
---

Over the past year or so I have collected data from cross country races across the state. By setting a single meet at a distance I was almost 100% confident about (not 5000m), I have written a program to estimate an equivalent distance for every meet across the state. I do not list all of the meets here. I started with the top runners across Texas and made sure I had most if not all of their meets. I used a also very good sampling of meets from the various regions across Texas (and Woodbridge).  
  
You are by now probably asking why I think I can do this and what were my methods? Well, I have an advanced degree in Analytics and taught statistics in the business school at a flagship university in the state. I have been building models with sports data for over 30 years. I won't go into my methods other than what I stated above but I use the top-X runners (there's a min and max) and compare them across meets and iterate through the data as many times as needed.

None of this was meant to give an exact distance, but rather an estimate of how someone would be able compare various times from meets across the state. I also have a program to compare times to a 'perfect 100′ course. This is a bit of like Tully, but I am not worried about a speed rating.. and yes, I have read Andy Beyers', "Beyer on Speed" where Tully got his formula. Beyer is a brilliant person and his insight on how he developed what he did is interesting. I feel as though Tully does a good job, but since he only covers few meets outside of NY, his ratings (when you reverse engineer them) are off and inconsistent.

It is not an exact science. There are definitely weaknesses, but for the most part I have found them to be solid. I hope you find them entertaining.

You can also ignore the Confidence scores. Those are just a simple number that really doesn't mean much.

**MEET**| **COURSE RATING**| **EQUIV METERS**| **EQUIV MILES**| **CONFIDENCE**  
---|---|---|---|---  
2025 Crandall Pirate XC Invitational| 110.65| 5532| 3.44| 80  
Galveston Island Beach Run| 108.66| 5432| 3.38| 68  
21St Annual Guymon Rattlesnake Run| 108.05| 5402| 3.36| 64  
Commerce High School Invitational| 107.73| 5386| 3.35| 45  
Azle XC Invitational| 107.56| 5377| 3.34| 77  
2025 Pebble Hills Invitational Xc| 106.43| 5321| 3.31| 82  
VFP XC Invitational| 105.55| 5277| 3.28| 76  
UT-Tyler XC Season Opener| 105.21| 5260| 3.27| 84  
Aledo Tri Meet| 104.91| 5245| 3.26| 82  
Brazos XC Invitational| 104.62| 5230| 3.25| 74  
Boomtown Nix Means Law CC Jamboree| 104.62| 5230| 3.25| 63  
Endurance House XC High School Stampede| 104.37| 5218| 3.24| 77  
Tcs Cross Country Invitational| 104.11| 5205| 3.23| 86  
TCU John Mckenzie Invitational| 104.02| 5201| 3.23| 84  
Scuc Invitational Xc| 103.25| 5162| 3.21| 93  
Del Valle Midnight Madness| 103.12| 5155| 3.2| 38  
Kevin Napier Invitational| 102.72| 5136| 3.19| 84  
Hereford Cross Country Invitational| 102.69| 5134| 3.19| 74  
Run The Wild Hs Meet| 102.66| 5133| 3.19| 87  
Cowboy Jamboree| 102.48| 5123| 3.18| 92  
2025 Islander Splash| 102.46| 5122| 3.18| 94  
Vista Ridge Cross Country Invitational| 102.32| 5115| 3.18| 93  
James Smith HS Invitational| 102.27| 5113| 3.18| 64  
Coronado / Franklin XC Invitational| 102.05| 5102| 3.17| 85  
Ryan Gingerbread Jamboree| 102| 5100| 3.17| 72  
23rd Annual SA Patriots CC Invitational| 101.79| 5089| 3.16| 89  
McAllen Rowe Warrior Invitational| 101.67| 5083| 3.16| 75  
Weslaco XC Invitational| 101.5| 5074| 3.15| 70  
Fossil Ridge Run Of The Panther| 101.5| 5074| 3.15| 88  
Edinburg High Invitational| 101.47| 5073| 3.15| 92  
2025 Barbers Hill Soaring Eagle Invitational| 101.45| 5072| 3.15| 78  
Hoka McNeil Invitational| 101.4| 5070| 3.15| 100  
Burleson Centennial "Green Monster" Spartan Invite| 101.36| 5067| 3.15| 64  
Metroplex Invitational| 101.22| 5060| 3.14| 56  
RGV Cross Country Classic| 101.17| 5058| 3.14| 88  
Huntsville CC Meet| 101.11| 5055| 3.14| 82  
Macen Holderman Cleveland Invite| 101.01| 5050| 3.14| 55  
Burleson Elk Run XXV| 100.99| 5049| 3.14| 92  
UIL Region II & Region 3 1A Preview XC & MS Meet| 100.98| 5049| 3.14| 91  
Sharyland Pioneer Cross Country Invitational| 100.83| 5041| 3.13| 65  
Central Catholic Cross Country Invitational| 100.83| 5041| 3.13| 83  
Austin ISD/Bowie Cross Country Invitational| 100.6| 5029| 3.12| 93  
Long Creek HS Invitational XC| 100.56| 5027| 3.12| 92  
Flower Mound Invitational| 100.51| 5025| 3.12| 86  
Kaufman Run With The Lions 5A-6A| 100.46| 5023| 3.12| 70  
9Thh Annual Sylvia H Torres Memorial Cross-Country Invitational| 100.39| 5019| 3.12| 47  
Runnin' Rattler Invitational| 100.33| 5016| 3.12| 87  
Cardinal Invitational| 100.3| 5015| 3.12| 80  
Canutillo XC Invitational| 100.26| 5013| 3.11| 46  
Cedar Park XC Invitational| 100.24| 5011| 3.11| 92  
Floresville XC Invitational| 100.23| 5011| 3.11| 91  
Castleberry Invitational (HS & MS Divisions)| 100.21| 5010| 3.11| 88  
Clint/Riverside @ Clint| 100.19| 5009| 3.11| 78  
Bradon Lynch Memorial| 100.14| 5007| 3.11| 83  
Harlingen CISD XC Invitational| 100.12| 5005| 3.11| 91  
Donna ISD Cross Country Invitational| 100.09| 5004| 3.11| 94  
Border Olympics| 100.06| 5003| 3.11| 93  
SAISD Invitational| 99.96| 4997| 3.1| 76  
Pine Tree Mike Darby Invitational| 99.94| 4997| 3.1| 89  
Clear Springs Charger XC Invitational| 99.93| 4996| 3.1| 84  
Lubbock ISD CC Invitational| 99.83| 4991| 3.1| 80  
Lewisville Rick Neill Memorial| 99.78| 4989| 3.1| 85  
Zapata South Texas Stampede| 99.76| 4988| 3.1| 64  
Westlake Chaparral Invitational| 99.67| 4983| 3.1| 93  
Tyler Legacy XC Invitational| 99.5| 4974| 3.09| 89  
St. Andrews Invitational| 99.38| 4969| 3.09| 55  
UIL Region III Preview| 99.24| 4961| 3.08| 93  
McAllen Memorial Mustang Stampede| 99.21| 4960| 3.08| 67  
FW Boswell XC Invitational| 99.15| 4957| 3.08| 71  
Max Blansit XC Invitational| 99.15| 4957| 3.08| 64  
Texas A&M Invitational| 99.07| 4953| 3.08| 91  
McAllen Bulldogs Invitational 2025| 99.03| 4951| 3.08| 92  
McKinney Boyd Bronco Stampede| 98.97| 4948| 3.07| 93  
37Th Annual Yellow Jacket XC Invitational| 98.93| 4946| 3.07| 83  
Denison Invitational| 98.87| 4943| 3.07| 71  
Seven Lakes Showcase XC Invitational| 98.84| 4941| 3.07| 84  
Coach T - Marcus Invitational| 98.73| 4936| 3.07| 93  
20th Annual Molina Garey Horner XC Invitational| 98.7| 4934| 3.07| 56  
Nike South| 98.69| 4934| 3.07| 91  
32Nd Joe I. Vigil Open High School And Middle School| 98.68| 4934| 3.07| 71  
Wylie Dustin Rodriguez XC Inv.| 98.67| 4933| 3.07| 89  
Alvin ISD Freedom Run Invitational| 98.65| 4932| 3.06| 58  
Hallsville Invitational| 98.64| 4932| 3.06| 86  
Ken Gaston "Race At The Lake" Invitational Cross-Country Meet| 98.58| 4928| 3.06| 88  
Hillsboro Invitational| 98.53| 4926| 3.06| 87  
Hays CISD XC Invitational| 98.52| 4925| 3.06| 90  
Tall City Invitational| 98.49| 4924| 3.06| 86  
Mercedes 30Th Annual Invitational| 98.47| 4923| 3.06| 73  
Eastwood Stars & Strides Jim Omohondro Twilight XC| 98.46| 4922| 3.06| 61  
Lovejoy XC Fall Festival| 98.25| 4912| 3.05| 93  
Klein ISD XC Invitational| 98.12| 4906| 3.05| 87  
10Th Annual Boyd Yellowjacket Invitational| 98.12| 4906| 3.05| 87  
Brenham Hillacious| 98.1| 4905| 3.05| 87  
La Porte Bulldog Invitational| 98.05| 4902| 3.05| 78  
2025 Seguin Matador XC Invitational| 98| 4899| 3.04| 94  
Lake Belton Bronco Invitational| 97.88| 4893| 3.04| 89  
W.H. Adamson XC Invitational| 97.64| 4881| 3.03| 59  
Dubeast XC Invitational (9-6A Preview)| 97.59| 4879| 3.03| 84  
Strake Jesuit XC Invitational| 97.47| 4873| 3.03| 77  
Jim Ned Warpath Invitational| 97.45| 4872| 3.03| 88  
LCISD Round-Up| 97.2| 4859| 3.02| 87  
Canyon Invitational| 97.18| 4858| 3.02| 87  
Abilene Invite| 97.12| 4855| 3.02| 72  
SA Friday Night Lights XC| 97.11| 4855| 3.02| 90  
36Th Dayton Bronco Invitational| 97.09| 4854| 3.02| 88  
Van Vleck XC Invitational| 96.92| 4846| 3.01| 76  
Giddings Camp Tejas Invitational| 96.74| 4836| 3| 88  
Sulphur Springs Wildcat Invitational| 96.68| 4834| 3| 61  
Lake Ridge XC Invitational| 96.63| 4831| 3| 89  
Texas High Tiger XC Invitational| 96.53| 4826| 3| 67  
3rd Annual Coach Brannan Ram Run| 96.33| 4816| 2.99| 52  
Southlake 5K XC Invite| 96.24| 4812| 2.99| 92  
The Reunion Run| 96.04| 4801| 2.98| 86  
Dobie Longhorn Stampede| 95.88| 4793| 2.98| 80  
El Paso High XC Invitational| 95.79| 4789| 2.98| 65  
Braswell Little D Invitational| 95.77| 4788| 2.98| 87  
Life Waxahachie Mustang Stampede| 95.51| 4775| 2.97| 83  
5th Annual Vickey Llanes La Maquina Invite| 95.41| 4770| 2.96| 82  
Cathedral/Loretto Invitational| 95.22| 4760| 2.96| 86  
Waxahachie Woodhouse Invitational| 95.2| 4759| 2.96| 91  
Spring Branch ISD Invitational| 94.99| 4749| 2.95| 89  
Valley View Mark Davidson Invitational| 94.96| 4748| 2.95| 80  
Mission XC Invitational| 94.4| 4719| 2.93| 73  
Mansfield Legacy Bill Eaton Invitational| 94.27| 4713| 2.93| 78  
32nd Annual Bellville Booster Club XC Invitational| 94.2| 4710| 2.93| 89  
Leo Manzano / Rick Edwards Memorial XC Invitational| 93.84| 4692| 2.92| 91  
Phyllis Pappas Pacer (Wichita Falls ISD)| 93.78| 4689| 2.91| 85  
Littlefield XC Invitational| 93.33| 4666| 2.9| 77  
Stockdale Brahma Invitational| 92.8| 4640| 2.88| 61  
44Th Annual Woodbridge Cross Country Classic| 92.46| 4622| 2.87| 74  
Amarillo ISD Invitational Cross Country Meet 2025| 92.36| 4617| 2.87| 84
