# DS.2 RC Helicopter Build Manual

## Introduction:

The DS.2 is the second helicopter of the DS.X RC Heli Project. The helicopter was designed with the flowing goals: 
- Make a fully 3D capable RC helicopter.
- The helicopter must be in the 550 to 600 class.
- Be as light as possible.
- Use the minimum number of metallic parts.
- Be 3D printable.
- Use as many parts as possible that are available ion the market (not helicopter specific).
- Be able to use parts from multiple other helicopter brands where needed (metallic parts).

These would make the helicopter essentially an ‘open source’ type of project since builders can make the parts locally and cheaply. The very low count of metallic parts guarantees that this helicopter will never run out of spares either!

The design started in December 2023 and settled to a 570 size and was completed in 2024. It has flown very well and has proven reliable and robust in moderate 3D flight, including a few crashes!
A few parts underwent small modifications and this is the final version (v2.1) of the helicopter. 

Since each build will be unique, each builder must treat this as a semi-prototype helicopter.

Enjoy the build!

*Apostolos Tsimogiannis*


If you want to ask anything contact me at:
apostolos.tsimogiannis@gmail.com 

or send a friend request to “DS.X RC Heli Project” on FB and message me.

You can see videos of the DS.2 and other projects at https://www.youtube.com/@apostolosnt.

<br>
<br>

> ## Licensing:
> This work is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International.
To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/
<br>

> ## Disclaimer:
> Remote Control (RC) Helicopters can cause harm or death to people and animals and damage to property. By following the information shared in this repository, downloading the part files, and building the helicopters, or using the parts in other ways, the user agrees that all responsibility lies with them. The designer is not liable for any harm or damages arising from the use or these parts and cannot guarantee in any way the operation of the components or the helicopter as a whole. Using the parts, assembling the helicopter and using it, is at the users own risk and they hold all resposnibility and liability. Operate all RC vehicles in accordance with safety guidelines and local law requirements.
<br>

## General information about the build:

The DS.2 is a RC helicopter intended for hobbyists with advanced knowledge of assembling helicopters and tool skills to build or adapt parts. This manual is not a exhaustive presentation of the build process and good assembly practices and knowledge of RC helicopter assembly are prerequisites for this build.

The builder must be capable and have the tools to:

- Drill precision holes in hardened shafts.
- Cut hardened shafts.
- Use drills or other tools to drill or clean holes and bearing seats.


The model is built using the following materials:
- Carbon sheet
- MJF (MultiJet Fusion) 3D printed parts
- FDM 3D printed parts
- Existing parts of commercially available RC helicopters
- Bearings, screws, belts widely available in the market.

The usual materials and tools are required:
- Thread lock
- Epoxy glue
- Lubricating oil
- Soldering iron
- Hex, torx and other drivers, depending on the screws used.

Many of the parts needed are common among various RC helicotpter models available in the market such as Mikado Logo 600 series, Goosky RS5 or RS6, Align etc. so parts from those helis may be available to the builder from other projects.
All parts, except from the shafts (main, spindle, 1st Stage, tail, tail spindle) can be found in the market. It is recommended the shafts are bought from existing models unless the builder has access to machining and case hardening.

<ins>Use thread locking compound in all metal to metal contacts except when a lock nut is used.</ins>

For metal thread screws into MJF plastics thread locker is not needed but the thread forming must not go through the entire thread depth. Allow some section for the screw to cut its own thread and ‘lock’ with the mating piece. These screws will not come off. Be careful of how much you tighten such screws. They must not be tightened like in metal.
Regardless of where a bolt threads into, remember you are tightening M2, M2.5, M3 screws. Do not treat them like M30!

All metal thread bolts used must be high strength.

When using screws specifically made for plastic, no thread tool is needed. The screw will form its own thread and can be tightened more than metal screws in plastic. These screws are not very good at being removable and over-tightening them will reduce further the number of times they can be loosened and tightened.

All bearing seats must be cleaned with a tool that has a square edge. Some screwdrivers will do or square tip exacto knives. The seat must be cleaned form the nylon powder and the edges pressed. This will make the bearing seat better. All nylon parts have a small surface roughness which allows for some give, so bearings fit with a moderate transition fit, perfect for the use.

MJF 3D printed parts are only accurate to more than 0.1mm which is not machining accuracy, therefore some part assembly may require part cleaning. The work on the pieces should not require material removal and parts should fit as expected. If this is not the case then discuss with your MJF parts manufacturer.

It is recommended that SLS is not used as a process. Depending on the implementation parts may be more brittle that expected. Discuss with your 3D print shop and maybe test one or two pieces for flexibility.
<br>
<br>

## Mechanical Parts Needed:
<details> 
  
<summary> Open Chapter </summary>

|Description|Qty|Use|Remarks|
|---|---|---|---|
|8x16x5 bearing|	4|	Grip	|   |
|8x16x5 thrust bearing|	2|	Grip	|F8-16M|
|10x19x5 flanged bearing|	5| Main and Stage 1| shaft	|F6800-ZZ|
|6x13x5 bearing|	1|	Motor support	| |
|3x7x3 bearing|	10|	Tail belt guides, tail arm, stage 1 belt idler, stage 2 belt idler|	683ZZ|
|5x13x4 flanged bearing|	2|	Tail case for 5mm tail shaft|	F695|
|6x10x2.5 bearing|	2|	Tail slider|	MR106 W2.5|
|4x8x3 bearing|	2|	Tail grip|	MR84ZZ|
|4x8x3.5 thrust|	2|	Tail grip|	F4x8S|
|4x8x2 bearing|	2|	Tail grip|	MR84|
|3x8x4 bearing|	??|	Stage 2 belt idler ??|	693ZZ|
|Belt HTD 3M 234mm/10mm (L/W)|	1|	Stage 1 belt|	Prefer flexible belts|
|Belt HTD 3M 234mm/15mm (L/W)|	1|	Stage 2| belt|	Prefer flexible belts|
|Belt HTD 3M 1680-1698mm/6mm| 	1|	Tail belt|	Use any length available. Adjust tail boom length accordingly.|
|  |  |  |  |			
|Washer| | | |			
|Washer| | | |
|Washer| | | |
|washer| | | |
|2.9x6mm screws for plastic|	4|	frame| |
|  |  |  |  |		
|Stage 1 shaft, 10mm dia, 57mm length|	1|	Stage 1 shaft|	See drawing for hole position and size.|
|Main shaft, 10mm dia, 184mm length|	1|	Main shaft|	See drawing for hole positions and size.|
Spindle, 8mm dia, 108mm length|	1|	Spindle	Mikado Logo 600 compatible.| Adaptations to fit other spindles is possible but depending on length the helicopter response and flying characteristics will change.|
|Tail shaft and spindle|	1|	Tail|	Tail shafts and the corresponding spindles can be used: Mikado Logo 600/550 series,	Goosky RS5, other models will fit as long as they are 5mm or 6mm diameter. Some modification to the control mechanism may be required to get the required CW/CCW throws.|
|Swash|	1|	Head|	Any swash that is designed for a 10mm shaft can be used. The original design head geometry requires the two front ball links to be 62mm to 63mm center distance. Using any swash in the market, a set of ball links can be found to fit this requirement. Other distance will alter the linearity of the head.			Swash plate from Align, Mikado, Steam etc will work. See more details further in the manual.|
|One Way Bearing (OWB) and Hub|	1|	Main shaft transmission|	A suitable main shaft OWB is required. The main pulley is designed for the Mikado Logo 600 OWB and hub but it can be adapted to other hubs in the market. The file is in STEP format so it can be adapted. With users adapting it to other hubs the file download will be expanded to include parts ready to accept other OWB hubs.|
|17T HTD 3M motor pulley|	1|	Stage 1 transmission|	An alu pulley is needed at the motor. These are readily available in the market (usually AF type for 10mm belt).|
|Dowel pins 3mm|	3|	Tail belt tensioners|	2x19mm, 1x28mm|
|Dowel pins 2mm|	1|	Tail pulley	|
|  |  |  |  |		
|  |  |  |  |		
|  |  |  |  |		



</details>
<br>

## Manufactured Parts:
<details>
<summary> Open Chapter </summary>

|Part ID|Part Name|Process/Material|Quantity|
|---|---|---|---|
|02-001-10|front shaft|CNC hardened steel|1|
|02-002-10|main shaft|CNC hardened steel|1|
|02-003-20|3M 56T Stage 1 pulley|MJF/SLS nylon|1|
|02-004-10|3M 22T|MJF/SLS nylon|1|
|02-005-10|3M 67T|MJF/SLS nylon|1|
|02-006-10|3M 56T OWB pulley|MJF/SLS nylon|1|
|02-007-21|lower plate|3K carbon sheet|1|
|02-008-21|middle plate|3K carbon sheet|1|
|02-009-20|top plate|3K carbon sheet|1|
|02-010-21|side plate (Right and Left editions)|3K carbon sheet|2|
|02-011-10|rear bow support|3K carbon sheet|2|
|02-012-12|front bow support|3K carbon sheet|2|
|02-013-10|head plate|3K carbon sheet|2|
|02-014-20|main grip plate|3K carbon sheet|4|
|02-015-10|tail fin|3K carbon sheet|1|
|02-016-10|front landing bow|FDM, PLA/PETG/other|1|
|02-017-10|rear landing bow|FDM, PLA/PETG/other|1|
|02-018-10|landing skid (Right and Left editions)|FDM, PLA/PETG/other|2|
|02-019-10|motor plate|MJF/SLS nylon|1|
|02-020-10|lower motor plate|MJF/SLS nylon|1|
|02-021-10|front battery mount|MJF/SLS nylon|1|
|02-022-20|rear battery mount|MJF/SLS nylon|1|
|02-023-10|front canopy support (Right and Left editions)|FDM, PLA/PETG/other|2|
|02-024-10|rear canopy support (Right and Left editions)|FDM, PLA/PETG/other|2|
|02-025-20|frame cross member|MJF/SLS nylon|3|
|02-026-10|top plate front suppport for 15mm servo|MJF/SLS nylon|1|
|02-027-10|top plate rear suppport for 15mm servo|MJF/SLS nylon|1|
|02-028-10|front servo suppport for 15mm servo|MJF/SLS nylon|1|
|02-029-10|rear servo support for 15mm servo|MJF/SLS nylon|1|
|02-030-10|rear tray servo mount for 15mm servo|MJF/SLS nylon or FDM PLA/PETG/other|1|
|02-031-10|rear lower tray|FDM, PLA/PETG/other|1|
|02-032-20|head block damped|MJF/SLS nylon|1|
|02-033-20|main grip|MJF/SLS nylon|2|
|02-034-20|frame lateral member|MJF/SLS nylon|1|
|02-035-10|carbon plate single support|MJF/SLS nylon|4|
|02-036-20|fixed swash driver|MJF/SLS nylon|2|
|02-037-10|main grip top|MJF/SLS nylon or FDM PLA/PETG/other|4|
|02-038-10|tail belt roller|MJF/SLS nylon|2|
|02-039-10|tail belt roller support|MJF/SLS nylon|2|
|02-040-10|tail belt arm support|MJF/SLS nylon|1|
|02-041-10|tail belt arm support bottom|MJF/SLS nylon|1|
|02-042-10|tail belt tensioner arm|MJF/SLS nylon|1|
|02-043-10|tail belt spring support|MJF/SLS nylon|1|
|02-044-10|tail boom bracket|MJF/SLS nylon|2|
|02-045-20|1st stage roller|MJF/SLS nylon|1|
|02-046-10|2nd stage roller|MJF/SLS nylon|1|
|02-047-10|stage 2 roller support|MJF/SLS nylon|1|
|02-048-10|main grip link tube|MJF/SLS nylon|2|
|02-049-10|tail rod guide|MJF/SLS nylon or FDM PLA/PETG/other|1|
|02-050-20|tail case|MJF/SLS nylon|1|
|02-051-10|3M-15T tail pulley|MJF/SLS nylon|1|
|02-052-10|tail arm|MJF/SLS nylon|1|
|02-053-10|tail control housing|MJF/SLS nylon|1|
|02-054-10|tail control fork|MJF/SLS nylon|1|
|02-055-10|tail link|MJF/SLS nylon|2|
|02-056-10|tail grip|MJF/SLS nylon|2|
|02-057-10|head damper|FDM, TPU80|2|
|02-058-10|tail control fork 6mm shaft|MJF/SLS nylon|1|
|02-059-10|tail control housing 6mm shaft|MJF/SLS nylon|1|
|02-060-10|tail arm 6mm shaft|MJF/SLS nylon|1|
|02-061-10|tail damper|FDM, TPU80|2|
|02-062-10|top plate front support for 20mm servo|MJF/SLS nylon|1|
|02-063-10|top plate rear support for 20mm servo|MJF/SLS nylon|1|
|02-064-10|front servo support for 20mm servo|MJF/SLS nylon|1|
|02-065-10|rear servo support for 20mm servo|MJF/SLS nylon|1|
|02-066-10|rear tray servo mount for 20mm servo angled|MJF/SLS nylon|1|
|02-067-10|rear tray servo mount for 20mm servo|MJF/SLS nylon or FDM PLA/PETG/other|1|
|02-068-10|rear servo support for 15mm head 20mm tail servo|MJF/SLS nylon or FDM PLA/PETG/other|1|
|02-069-10|front cable channel|FDM, PLA/PETG/other|1|
|02-070-10|canopy|FDM, PLA/PETG/other|1|
|02-071-10|canopy support|FDM, PLA/PETG/other|2|
|02-072-10|tail boom 680x25mm|Carbon tube|1|
|02-073-10|tail control rod 660x4mm|Carbon tube|1|
|02-074-10|2nd stage roller insert|FDM, PLA/PETG/other|1|
|02-075-10|main grip insert|MJF/SLS nylon|2|
|02-076-10|tail boom bracket plain|MJF/SLS nylon|1|
|02-077-10|tail boom bracket|MJF/SLS nylon|1|
|02-078-10|tail boom bracket insert|MJF/SLS nylon|1|
|02-079-10|tail grip for 6mm tail shaft|MJF/SLS nylon|2|
|02-080-10|3M-14T tail pulley for 6mm shaft|MJF/SLS nylon|1|


  
</details>
<br>

## Making the Main and Stage 1 Shafts:
<details> 
<summary> Open Chapter </summary>

The main shaft can be manufactured from different shafts in the market. Mikado 199mm shaft is convenient as it has the top hole at the right position. The 1st stage shaft can be made from any 10mm shaft on the market. <br>
Since the shafts are hardened, it is recommended that the position of the drilling is lightly flattened with a Dremel disk so the case hardening is removed and it becomes easier to drill. Use a low speed drill. <br>
Some dimensions do not need to be exactly as shown below. Shaft length can be up to +2mm. Hole positioning can be within 1mm or more of the shown dimension, but consider the following: <br>
The relative distance between the too holes on the Stagge 1 shaft needs to be accurate for parts to fit, and for links to have the dimensions shown in this manual, the relative distance between the two holes on the main shaft needs to be accurate. 
<br>
NOTE: drilled holes are shown as 3.1mm. The drill bit used should be 3.0mm.


<img width="1162" height="323" alt="image" src="https://github.com/user-attachments/assets/777369b3-8d40-4a06-a6a7-db2123ed8b58" />


  
</details>
<br>

## Stage 1 Shaft Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:
Use a 10mm diameter drill bit to clean out the shaft hole of the printed pulleys. Do not use a normal high speed drill. If you do not have a low speed drill press, use a choke and drill bit, and drive it through by hand, turning as you go. Go back and forth s few times to clean out any surface debris form the printing process.
Use the 2nd M3 thread tool to tap the smaller diameter hole side. This is were the positioning bolt will thread into. <br>
Assemble as shown below.

<img width="815" height="418" alt="image" src="https://github.com/user-attachments/assets/5ff265e1-d63b-4b34-b300-803a7e546475" />



  
</details>
<br>

## Main Shaft and Stage 2 Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:
Clean all surfaces and the 10mm shaft hole of the tail pulley as in the previous section. <br><br>
Assemble as shown below.<br>
Use 2x0.5mm washers between the OWB and the tail pulley.<br>
For a Mikado OWB hub (shown below) use 5x0.5mm washers below the OWB.<br>
Use 1x0.5mm washer above the tail pulley.<br>

<img width="1103" height="368" alt="image" src="https://github.com/user-attachments/assets/65be31b9-cac0-4b09-af67-9eea89e80000" />


  
</details>
<br>

## Lower Plate Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:
Clean all surfaces of the 3D printed parts with a small screwdriver. Make sure there is no nylon powder residue on the surface. You can use air gun if you have one.<br>
Prepare a small amount of two-part epoxy. <br> <br>
Use epoxy at all areas marked with the orange arrow in the drawing. Make sure you do not use too much and it overspills. Especially the bearings need a small amount only, to function as a retainer. CA glue can also be used for the bearings. Press the 3D printed parts onto the carbon plate so they are flush with the edges and do not protrude. This is important for the fit in the assembled frame later.<br>
The 4 screws are plastic-specific screws 2.9x6mm. If you cannot find self tapping flat tip ones, and you use pointed screws it’s suggested you cut the tip and do not allow it to protrude.

<img width="1165" height="402" alt="image" src="https://github.com/user-attachments/assets/ff8112d0-02d8-4b82-9de7-74dffedf3c74" />



</details>
<br>

## Mid Plate Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:
Clean all surfaces of the 3D printed parts with a small screwdriver. Make sure there is no nylon powder residue on the surface. You can use air gun if you have one.<br>
Prepare a small amount of two-part epoxy. <br><br>
Use epoxy at all areas marked with the orange arrow in the drawing. Make sure you do not use too much and it overspills. Especially the bearings need a small amount only, to function as a retainer. CA glue can also be used for the bearings. Press the 3D printed parts onto the carbon plate so they are flush with the edges and do not protrude. This is important for the fit in the assembled frame later.

<img width="1144" height="454" alt="image" src="https://github.com/user-attachments/assets/a495630d-203f-4434-8a63-1fd46794fbb5" />


</details>
<br>

## Top Plate Assembly:
<details> 
<summary> Open Chapter </summary>
### Preparation:
Clean all surfaces of the 3D printed parts with a small screwdriver. Make sure there is no nylon powder residue on the surface. You can use air gun if you have one.<br>
Prepare a small amount of two-part epoxy for the bearing only. In this instance the 3D printed parts are fitted without glue so they can easily be replaced. <br><br>
Use epoxy at the areas marked with the orange arrow in the drawing. Make sure you do not use too much and it overspills. Especially the bearings need a small amount only, to function as a retainer. CA glue can also be used for the bearings. <br> <br>


<img width="1146" height="511" alt="image" src="https://github.com/user-attachments/assets/ad04c430-eab1-4816-b4a9-28f0ddc56e90" />



</details>
<br>

## Main Grip Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:

Clean the bearings seats inside the grip with a small screwdriver and a square tip tool. Make sure there is no nylon powder residue on the surface and especially in the bearing seat.
Tap the grip arm ball link bolt hole with M3 tap tool. Do not bottom out the tool. Clean the four M3 holes and make sure the M3x30 bolts go through.
<br>
<br>
Per grip you will need:<br>
1x M3x16<br>
1x M3 washer<br>
4x M3x30<br>
4x M3 lock nuts<br>
1x M4x35<br>
1x M4 lock  nut <br>
2x 8x16x5 bearings<br>
1x 8x16x5 thrust bearing<br>
1x Ø10 washer (0.5, 0.2, 0.1 as needed)<br>
1x 8x0.5 washer<br>
<br>
Grease the thrust bearing as needed and position it with the small diameter to the outside.
<br>

Use the inner Ø10 washers as needed to allow
minimal play of each grip when assembled (~0.2mm total gap).

The Ø8 washer must only contact the inner race of the outer bearing.

You can leave the ball link for later, as you need to add the grip arm link
before you insert the bolt into the grip (highlighted on the drawing).
The grip arm ball link can be from any helicopter as long as it fits an M3 bolt.
Mikado grip-arm ball links work well.

<img width="719" height="539" alt="image" src="https://github.com/user-attachments/assets/d07306b2-5b8d-4b0e-8e7e-8aab40558621" />


</details>
<br>

## Head Assembly:
<details> 
<summary> Open Chapter </summary>

## Damped Head:<br>

### Preparation:<br>

Clean all 3D printed parts of any nylon powder residue on the surface and especially in the damper seat.<br>
Make sure all M3 bolts can pass through the main head block.<br>

Per grip you will need:<br>
6x M3x25<br>
6x M3 lock nuts<br>

Assemble the main head block withe the dampers and the spindle first.<br>
The M3 bolts will pass through by lightly threading them (they will cut a thread
into the damper).

<img width="1151" height="460" alt="image" src="https://github.com/user-attachments/assets/c704469a-bc54-41c4-b143-d0126890dedb" />


## Undamped Head:

The assembly and preparation are identical. There are just no dampers!


</details>
<br>

## Tail Grip Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:

Clean the bearings seats inside the grip with a small screwdriver and/or a square tip tool. Make sure there is no nylon powder residue on the surface and especially in the bearing seat.


Tap the grip arm ball link bolt hole with M2.5 tap tool. Do not bottom out the tool.

Per grip you will need:<br>
1x M2.5x10<br>
1xM2.5x6<br>
1x M2.5 washer<br>
1x 4x8x3 bearing<br>
1x 4x8x2 bearing<br>
1x 4x8x3.5 thrust bearing<br>
1x 4x8x0.5 washer<br>


Grease the thrust bearing as needed and position it with the small diameter to the outside.


<img width="752" height="355" alt="image" src="https://github.com/user-attachments/assets/ff68c76e-3cd3-464d-a3fa-b24e415dbb1b" />




</details>
<br>

## Tail Spindle-Shaft Assembly:

<details> 
<summary> Open Chapter </summary>

## Damped:

### Preparation:

Clean all 3D printed parts of any nylon powder residue on the surface and especially in the damper seat.

When using the Goosky RS5 tail parts, drill a 2.1mm hole at the center of the flats on the shaft.

Use the TPU printed dampers.

Assemble as shown. 

<img width="605" height="343" alt="image" src="https://github.com/user-attachments/assets/88b01a2a-b315-45a6-bcf0-dadf4971ccc9" />

## Undamped:

Assemble parts using thread lock for the set screw. Mikado 550/600 tail parts can be used.

<img width="508" height="282" alt="image" src="https://github.com/user-attachments/assets/356a9246-000f-4dac-b64c-0c393342905c" />



</details>
<br>

## Motor Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:

Clean the bearings seat of the lower plate with a small screwdriver and/or a square tip tool. Make sure there is no nylon powder residue on the surface and especially in the bearing seat.

To mount the motor plates to the frame screws for plastic or bolts can be used. 
If using bolts, the holes must be tapped. Tap the 4x M3 holes of the top plate and the 4x M2.5 on the lower plate. Do not tap al the way through so the last few threads lock into the plastic.

Also tap the 1x M3 position on the lower frame, where the tensioner roller bolt will thread into.


Assemble the motor on the motor plates. The motor plate hole pattern is 2xM4 25mm and 2x M4 30mm.<br>
1x 6x13x5 bearing.<br>
2x M4x10 bolts (or other depending on the motor used).<br>
1x HTD 3M 17T pulley. Other sizes can be used. Belt length or tensioner diameter may need to be adjusted.<br>

<img width="661" height="440" alt="image" src="https://github.com/user-attachments/assets/585e6d4f-9b51-43d2-aa29-e03ce5768364" />


</details>
<br>


## Main Frame Assembly:
<details> 
<summary> Open Chapter </summary>

Assemble all parts as shown below. It is important to get all belts on at this stage.

Use 5x 0.5mm Ø10 washers under the OWB if using a Mikado 600 OWB hub and one above the tail pulley.

Add one 0.5mm Ø10 washer at the top and bottom of the Stage 1 shaft.


<img width="1194" height="713" alt="image" src="https://github.com/user-attachments/assets/baff383a-639a-4bda-a78b-571868aceb4b" />
<br>
<br>


Assemble the side frames as shown below.
Use screws for plastic in all MJF parts 2.9x6 or 2.9x10 as needed. 
Assemble both side frames to check any vetical play of the main and stage 1 shafts. Add or remove washers as needed to make sure the shaft is not compressed between the plates and that there is no play. Also check that the OWB pulley is not sitting too low and touches the frame.
<br>
The front battery support and the lower plate front support must be tapped M3. See lower frame assembly.
<br>

<img width="794" height="531" alt="image" src="https://github.com/user-attachments/assets/ba3f8892-8fd0-4ba9-8b09-ed578bbbf822" />

<br>
<br>


Once the shafts are fitted with the right tolerance, other parts can be fitted now like the motor and tail belt guide pulleys and all the servo supports. 
<br>
<br>
The choice of plate/servo supports depends on the servo set used. Refer to the part list to identify parts numbers for 15mm, 20mm and mixed 15-20mm setups. 
<br>
<br>
The tail belt guide pulley assemblies can be removed and replaced at any point since they are easy to get to.
<br>
These are assembled using M2 bolts or 2mm screws for plastic. The latter are preferred.

<img width="900" height="409" alt="image" src="https://github.com/user-attachments/assets/d686933d-91ec-47c7-912b-a3a6f809b555" />
<br>
<br>


Add remaining compenets as shown below.
For the tail boom support brackets there are options how to set them up. A single tighening bracket can be used along with a plain one (shown below) or two tightening brackets can be used.
The top piece needs threads cut into it where the M3x25 will thread into.
All parts assembled with screws for plastic 2.9x10.

A locating screw must be added on the underside of the rear bracket.
This will be done later, after the tail has been assembled and the tail belt tensioned.
<br>

<img width="895" height="602" alt="image" src="https://github.com/user-attachments/assets/966e411b-a044-4e89-99b5-0a6f26c2a510" />




</details>
<br>

## Tail Assembly:
<details> 
<summary> Open Chapter </summary>


### Preparation:

Clean the bearings seat of the housing with a small screwdriver and/or a square tip tool. Make sure there is no nylon powder residue on the surface and especially in the bearing seat.
Clean the surface of the two links and the fork to make sure there is no roughness from the printing process that will prevent them from moving completely free and smooth between them.
Do not overtighten the M3 and the two M2 bolts. Make sure after assembly that everything runs absolutely smooth and free.
<br>
The holes on the arm are for M2 ball links. You do not need to tap the holes. Threading the ball link directly will cut its own thread and provide a good lock. If you do tap it, only tap the first few theards.
<br>
The fitting of the control fork onto the bronze slider is a tricky part of the assembly. If you have the correct tapping tool (M7 or M*, depending on using 5mm or 6mm tail shaft) make a start to the thread without going all the way through so the fork wioll lock by cutting the last few threards itself.
This can also be done by simply carefully threading the fork onto the slider and let it cut the threads. You need to be extra careful since the larger diameter of the slider with short thread pitch can easily misalign the parts and damage the fork. If you go this way you may want to have a second fork printed in case you damage the first.
<br>

<img width="1278" height="614" alt="image" src="https://github.com/user-attachments/assets/9fab9901-d37f-4087-b824-7f6eeacd5197" />
<br>
<br>
Press the two flanged tail shaft bearing into the tail case.
Then insert the tail boom and push it as far as possible without pressing against or damaging the tail belt rollers. <br>
Then bring the tail belt out the bottom from inside the tail case and insert the tail pulley. <br>
Push the tail pulley inside the tail case.
<br>

<img width="941" height="616" alt="image" src="https://github.com/user-attachments/assets/c40b8753-6843-437c-ab62-b4f7b437b85e" />
<br>
<br>
Once the tail case is pressed all the way in, use a 1mm drill bit to put a hole in the tail boom. Then use a 2.2x6 or similar screw to locate the tail case. <br>
Then use a 2mm pin and drive it through the tail pulley and the 2mm hole opened on the flat spot of the tail shaft.
<br>
<br>
Install the tail arm assembly with an M3x16 bolt. 
<br>
Use the printed tail dampers or the original ones to instal the tail spindle.
<br>
<br>

<img width="1279" height="650" alt="image" src="https://github.com/user-attachments/assets/820b2671-c5f1-4ff5-a5a1-f41cbed83152" />

<br>
<br>
The tail grip links can be attached to the tail fork using 2mm pins or M2x12 and nut. In the case of the pin make sure the pin has enough resistance going into the nylon part to be stable under vibration but also not to prevent the tail form moving completely free. When using bolt and nut use thread lock and make sure the nut is not on tight to interfere with free movement.
<br>
The M2.5 that connect the grip links to the grips must be theaded in with care. Due to the printing process the parts may not be absolutely the correct dimensions and in this case this can produce some friction at hi blade angles. Make sure you test this and if required keep the M2.5 bolt slightly loose. Due to the natural locking in the nylon part it will not come out under vibration. Test everythign moves smoothly and freely.
<br>
Install the tail fin as shown.
<br>
<br>
<img width="1320" height="662" alt="image" src="https://github.com/user-attachments/assets/2df69352-8bcd-4d4a-a5fb-5ef438276f61" />


<br>



</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## Lower Frame Assembly:
<details> 
<summary> Open Chapter </summary>
Use screws for plastic (2.9x10) where the screws go into MJF parts. On the right side use longer screws for plastic on the tensioner spring support piece.
<br>
For FDM parts such as landing bows and rear bottom tray use M3 into the thread inserts. Use thread locking compound.
<br>
<br>

<img width="1369" height="656" alt="image" src="https://github.com/user-attachments/assets/5626ffcc-3fc5-4b31-b4e4-cabe7d9c99b2" />




</details>
<br>

## Final Head Assembly and Grip Links:
<details> 
<summary> Open Chapter </summary>
The grip links require 30-35mm threaded rods. Use 2.5mm so that the grip link tubes work. If you use 3mm you have to design your own grip link tubes.
The distance between the ball links is approx. 16.5mm (the length of the grip link tube).




</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## Canopy Assembly:
<details> 
<summary> Open Chapter </summary>
<br>
The canopy is printed in section sto facilitate printing on personnal FDM 3D printers. The main canopy and windshield pieces include a 2mm lip on the endges which will be welded. Use a soldering iron to melt the lip and weld the pieces together.
<br>
The main body of the canopy consists of 4 parts: <br>
  
- canopy front
- canopy rear
- windshield front
- windshield back
<br>
  
The recommended sequence of welding the pieces together is:<br>
  
  - front section of the canopy with the front section of the windshield
  - add the rear section of the windshield
  - add the rear section of the canopy

Cut the connecting material to free up the rear section of the canopy.
IMPORTANT: Depending on the layer adhesion you can achieve, the rear section of the canopy will have a varrying level of flexibility. Always be mindful of that and put the canopy on the heli when the blades are vertical to the body so the canopy doe not have to sterwetch much to clear the swash-grip links. See images at the end of this section.

<br>
Then there are the DS.2 lettering and the triangle which are printed as flat pieces and are then glued onto the canopy with CA glue.


<br>
Last are the two supports which are held in place by 2x 2.3mm screws for plastic for each support.

<img width="1485" height="778" alt="image" src="https://github.com/user-attachments/assets/7485204b-4713-43c4-9228-89128b433bc0" />


<img width="1090" height="709" alt="image" src="https://github.com/user-attachments/assets/075bacb3-801f-4150-98fa-1b9bd9afaa3b" />




</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>

## :
<details> 
<summary> Open Chapter </summary>


</details>
<br>







