# DS.2 RC Helicopter Build Manual

## Introduction:

The DS.2 is the second helicopter of the DS.Z RC Heli Project. The helicopter was designed with the flowing goals: 
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

Use thread locking compound in all metal to metal contacts except is a retainer nut is used.

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
Spindle, 8mm dia, 109mm length|	1|	Spindle	Mikado Logo 600 compatible.| Adaptations to fit other spindles is possible but depending on length the helicopter response and flying characteristics will change.|
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

## Making the Main and Stage 1 Shafts:
<details> 
<summary> Open Chapter </summary>

The main shaft can be manufactured from different shafts in the market. Mikado 199mm shaft is convenient as it has the top hole at the right position. The 1st stage shaft can be made from any 10mm shaft on the market. <br>
Since the shafts are hardened, it is recommended that the position of the drilling is lightly flattened with a Dremel disk so the case hardening is removed and it becomes easier to drill. Use a low speed drill. <br>
Some dimensions do not need to be exactly as shown below. Shaft length can be up to +2mm. Hole positioning can be within 1mm or more of the shown dimension, but consider the following:The relative distance between the too holes on the Stagge 1 shaft needs to be accurate for parts to fit, and for links to have the dimensions shown in this manual, the relative distance between the two holes on the main shaft needs to be accurate. 

<img width="437" height="360" alt="image" src="https://github.com/user-attachments/assets/fea108eb-678d-465d-9822-78396d7c669a" />

<img width="1280" height="370" alt="image" src="https://github.com/user-attachments/assets/0dfadad3-0176-4c39-8caa-c235420aae5b" />

  
</details>
<br>

## Stage 1 Shaft Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:
Use a 10mm diameter drill bit to clean out the shaft hole of the printed pulleys. Do not use a normal high speed drill. If you do not have a low speed drill press, use a choke and drill bit, and drive it through by hand, turning as you go. Go back and forth s few times to clean out any surface debris form the printing process.
Use the 2nd M3 thread tool to tap the smaller diameter hole side. This is were the positioning bolt will thread into. <br>
Assemble as shown below.

<img width="413" height="660" alt="image" src="https://github.com/user-attachments/assets/7c68d83c-08ca-4446-916c-3249d4dcc54b" />

<img width="368" height="398" alt="image" src="https://github.com/user-attachments/assets/f2e23f2a-0c7f-441e-9eea-10f1ac36bec0" />
  
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

<img width="1280" height="408" alt="image" src="https://github.com/user-attachments/assets/a99ab3b2-1289-4a3e-903c-01bcb0cd8a03" />


<img width="331" height="444" alt="image" src="https://github.com/user-attachments/assets/bbf51d05-3f42-4d88-8f32-e6624dbb4bf6" />

  
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

<img width="730" height="413" alt="image" src="https://github.com/user-attachments/assets/4f12fbdd-1aed-47e5-8be4-4bdacd70b153" />

<img width="633" height="403" alt="image" src="https://github.com/user-attachments/assets/2a42df7e-98fe-457a-85dd-5f6713cb37ca" />


</details>
<br>

## Mid Plate Assembly:
<details> 
<summary> Open Chapter </summary>

### Preparation:
Clean all surfaces of the 3D printed parts with a small screwdriver. Make sure there is no nylon powder residue on the surface. You can use air gun if you have one.<br>
Prepare a small amount of two-part epoxy. <br><br>
Use epoxy at all areas marked with the orange arrow in the drawing. Make sure you do not use too much and it overspills. Especially the bearings need a small amount only, to function as a retainer. CA glue can also be used for the bearings. Press the 3D printed parts onto the carbon plate so they are flush with the edges and do not protrude. This is important for the fit in the assembled frame later.

<img width="667" height="460" alt="image" src="https://github.com/user-attachments/assets/726d1275-6599-4979-baa8-00fd7f9ec9ca" />

<img width="587" height="368" alt="image" src="https://github.com/user-attachments/assets/05292e70-39a3-4e43-a4af-dc61ef3306cb" />

</details>
<br>

## Top Plate Assembly:
<details> 
<summary> Open Chapter </summary>
### Preparation:
Clean all surfaces of the 3D printed parts with a small screwdriver. Make sure there is no nylon powder residue on the surface. You can use air gun if you have one.<br>
Prepare a small amount of two-part epoxy for the bearing only. In this instance the 3D printed parts are fitted without glue so they can easily be replaced. <br><br>
Use epoxy at the areas marked with the orange arrow in the drawing. Make sure you do not use too much and it overspills. Especially the bearings need a small amount only, to function as a retainer. CA glue can also be used for the bearings. <br> <br>


<img width="505" height="319" alt="image" src="https://github.com/user-attachments/assets/da06a9f7-9e8c-4000-8e8b-632c5af7616e" />

15mm servo supports shown <br>

<img width="515" height="355" alt="image" src="https://github.com/user-attachments/assets/bb24334e-8ee4-4b60-b9de-cd66f061894a" />

Assembled plate with 15mm servo support <br>

<img width="590" height="400" alt="image" src="https://github.com/user-attachments/assets/b5d8e06b-0077-497c-85f9-a80b17f9ad7e" />

Assembled plate with and 20mm servo supports <br>


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

<img width="1096" height="371" alt="image" src="https://github.com/user-attachments/assets/1ca3f094-87b1-4845-9912-ecaf7855d251" />

<img width="652" height="526" alt="image" src="https://github.com/user-attachments/assets/b28b872b-0f4a-4f95-8db3-ef2826d7fc8c" />


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

<img width="1014" height="720" alt="image" src="https://github.com/user-attachments/assets/92e63146-1983-41e2-909d-ef2ab2d27f84" />

<img width="627" height="475" alt="image" src="https://github.com/user-attachments/assets/4211668a-0e26-4ab3-95fc-6a52e59785a3" />

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


<img width="690" height="461" alt="image" src="https://github.com/user-attachments/assets/5324407b-83db-4af3-b2b7-43fa9b9bde89" />

<img width="357" height="301" alt="image" src="https://github.com/user-attachments/assets/b0be678a-4fc8-4dfc-ab44-9cd6f06a066a" />



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

## Main Frame Assembly:
<details> 
<summary> Open Chapter </summary>

Assemble all parts as shown below. It is important to get all belts on at this stage.

Use 5x 0.5mm Ø10 washers under the OWB if using a Mikado 600 OWB hub and one above the tail pulley.

Add one 0.5mm Ø10 washer at the top and bottom of the Stage 1 shaft.


<img width="1194" height="713" alt="image" src="https://github.com/user-attachments/assets/baff383a-639a-4bda-a78b-571868aceb4b" />

Assemble the side frames as shown below.
Use screws for plastic in all MJF parts.
Assemble both side frames to check any vetical play of the main and stage 1 shafts. Add or remove washers as needed to make sure the shaft is not compressed between the plates and that there is no play. Also check that the OWB pulley is not sitting too low and touches the frame.

<img width="1814" height="1125" alt="image" src="https://github.com/user-attachments/assets/76d5431a-8f2e-4012-9f99-9666fefc1e02" />

Other parts can be fitted now like the tail belt guide pulleys and all the servo supports. These can be removed and replaced at any point since they are easy to get to.
These are assembled using M2 bolts or 2mm screws for plastic. The latter are preferred. 

<img width="424" height="461" alt="image" src="https://github.com/user-attachments/assets/5646b458-cb6e-4347-8b8f-6778b8d398b9" />

<img width="470" height="448" alt="image" src="https://github.com/user-attachments/assets/4c163624-08a3-46cf-ae2f-f65f8a9f7e62" />




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





