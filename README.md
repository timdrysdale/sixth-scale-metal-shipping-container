# sixth-scale-metal-shipping-container
Design and construction information for the 1/6th scale metal shipping containers

## Background

We needed a box that can be put in public spaces

- retains any fumes from melting insulation on wires
- minimal combustible load
- simplified cable routing

## Size

1007mm wide by 430mm high by 400mm deep plus corner castings

corner castings are  5mm thick in each lateral direction, 8mm vertically. The male / female lock is 8mm





## Bill of Materials

Main body: Aluminium 2000mm by 1000mm by 1.5mm thick aluminium sheet. 1050 Grade.
Trays:Aluminium 2500 by 1250 Sheet 1.5mm 1050 grade

Front panels - 2mm PETG (Brand lumex-G, which is fire-rated) 995mm by 420mm 
3D printed PETG corner castings (12 off pieces to make 8 corner castings)
3D printed spacers for the security screws (2 off)
12.7 by 1.5mm magnetic tape (polarised variety, from "first for magnets")
Full-colour vinyl wrap on four sides (Files supplied!) (TODO dimensions!)

4mm diameter by 8mm-long pop rivets, 20 off per box
clinch nuts to suit M3 for 1.5mm panel thickness (they come in different panel thickness varieties) (pronounched 'cinch', spelt 'clinch') 4 off per box (only one end)
TR25 M5 by 16mm 2 -off
Magnetic tape - approx 5660mm per box (6m in round terms)




## Construction method

Cutting, folding, and riveting

aluminium tape to seal the joins - TODO upgrade to reinforcement plates with polyurethane adhesive ("Sticks Like")

captive bolt for the front panel securement with 3D printed spacer to make up the 2 thicknesses of the magnetic strip.

## Aluminium

### Order
Order 2000 by 1000mm by 1.5mm thick aluminium sheet. 1050 Grade.


### Cutting

Cut the main body to 1304mm by 1000mm. Standard sheet guillotine for clean edge (must be precise).

You can use a sheet metal deburring tool at this point, or wait until assembled, just before stickering, and use a sanding block. With sanding block you can you round off the corners too.

The scrap is lasered into the two end caps using the flattened DXF (TODO link to file)

### Rivet holes

The body has holes lasered into it if possible for the rivets, or else a jig is clamped to it, and holes manually punched with a tool.

From the edge you cut off the sheet, is not the datum, instead use the 1000mm short edge from the mill (so mark that with an X to show it is the datum, that will become the centre of the bottom lip).

The jig is notched at one end to show that it is shorter than the width of the box - the laser that makes the jig can only take 1300mm so can't reliably cut 1304mm instead the jig is 1250mm and the straight edge is the reference for placing on the datum edge (TODO supply DXF for jig). 10 holes to punch per side. FLIP the jig to do other side, so the holes are approximately 11mm i.e. choose the jig orientation that puts the holes closest to the edge.

### Folding

There are four folds. First we get the box height done right. Then we can do the depth. Then the left over is the lip, so any inaccuacies get transferred to the lip where they will not affect the overall depth or height, thus allowing boxes to be stacked later.

#### Fold #1 Bottom rear corner

Datum edge against the backstop, the backstop is set at 445 mmm. Fold up 90 degrees. 

### Fold #2 Top rear corner

Set backstop to 428mm.

Reposition the work so that the new face (shorter side of fold) goes against the backstop, so left with the longer piece of material

### Fold 3 Front top corner

Set the backstop to 398mm from top leaf of the . Set back face against backstop, Fold lip 90 degrees up

### Fold 4 Front bottom corner

Same backstop, fold other lip.

Notes on getting this bit right:

Folding leaf to clamp distance should be material thickness 1.5mm to get the right radius (2mm outside radius). If you change the fold radius it changes the length of the flat parts of the material, which affects the fitting - the hole positions change for the rivets etc. So if your machine produces a different radius, either change it, or adjust the hole jig and flat material dimensions (easier to sort the fold radius to suit the designs done in the CAD!)

Note the holes on the end cap are not dependent on the end cap folds so they are the reference position you are aiming to get these main box holes to line up with (Within the limits of accuracy of the manual hole punch. Vigilence required.

Deburr any sharp edges, especially the top and bottom lip, and the outside edges which are exposed (end cap goes on the inside).

Main body is now cut, drilled, folded.

## End caps

Using the supplied DXF, these are lasered from scrap off the 2000mmm sheet. The backside of the cut on our laser can be a bit rough, so rather than use one DXF and just flip the cut parts to make the mirrored shape the opposite end, we mirror the DXF to keep the rougher back edge of the cut inside the box.

A commercial grade laser won't have this problem because it will have the necessary nitrogen pressure. That's a local consideration for equipment limitation that will not apply to commercially cut metal.

In addition the left side as seen from the front has extra plug holes (2x XLR).

Both end caps have rivet holes, square hole for the captive nut.

### Folding

Use the hydraulic press brake (We do), or a standard box and pan could be used, so long as the same 2mm outside radius is maintained (else will not fit the main body correctly, because the finished dimension will be different).

The finished dimension should be height 427mm to the outside faces. The depth 398.5mm to the outside faces.

For three folds 25.1mm from the edge (back, top and bottom flanges)

The front flange is 33.6mm from the edge. This is the edge with the square hole for the captive nut, so easily identified.

Pay attention that you are folding correct oriention, so the left hand endcap has the holes.

Check that the depth of the main body is 400mm outside face of front lip to back face +/- 0.5mm so that the corner castings will interlock. Might be ok fitting a 399mm box into a 401mm box but will be a tight fit.

### Clinch nuts

The DXF is based on the RS part number (TODO - RS Part number), however you need to check the nuts you are getting because sometimes they can change (The RS clinch nuts don't seem to be industry standard - have a larger hole - and we had mixed sizes in our order as well). We do not recommend riv nuts because they squash the material because there is not enough distance between the connector hole and the riv nut hole.

Suggest ordering the clinch nuts in advance and measuring them on arrival, then adjusting DXF to suit if required. Industry standard size would be smaller, leaving more material between this hole and mounting, i.e. less squashing / distortion and a better result.

They are pressed in using an in-house tool. You cannot hit them with a hammer because it is a cold-forming process.

We are on the alt size for now - 4.75mm hole. The standard size is 4.25mm. Suggest 4.25mm when choice available.

So we have the metal box body on the table, with two end caps ready to install.

## Riveting

Use a flat surface to avoid building in any twist - should be ok if rivet holes were not eased, but if rivet holes have been eased, pay care to the flatness of the assembly surface in case the box picks up some twist (it shouldn't because the rivet holes are quite tight when accurately placed)

Use skin pins, or sheet metal pins Cleco.

Get the end cap into place, use skin pins (we use Cleco brand) to locate the end cap while riveting.

Measure the width of the assembly from outside face to outside face of the left and right endcaps, and check it is 1007mm +/- 0.5mm. Worst case 1006mm box might fit a 1008mm box but the interlocks would be tight.

We use an electric riveting gun for speed, but a manual gun works fine.

### End cap assembly troubleshooting....

Holes can be eased with a 4mm power drill to fix small misalignments - bear in mind rivet still needs to be able to clamp, so as a last resort to save a box from the bin you can use a washer to cover an oversize hole, on the inside of the box (i.e. on the inside of the endcap, which had its hole eased. Don't ease the hole in the main body because that will be visible from outside.

## Silver taping to seal the joints - or reinforcement aluminium.

There is a revision to this stage in order to provide additional ridigity - information to follow. Bear in mind boxes will need to be twist and bend free - assemble on a flat surface.


## Stickering

After assembly, before stickering, run around with a sanding block 180 grit standard paper.

Clean the metal free of dust and oil, say brakecleaner, acetone, IPA or vinyl wrap spray. Then apply the vinyl wraps as follows.

First cut four corners off all stickers, ie. ends, top and back. The cut is made diagonally through the image of the corner connector (called an iso lock?) We are cutting the corners off, so when they overlap, you don't get a wrinkle, and exposes the corner cast to the metal, so the adhesive holds it onto the metal directly - having roughed the corner with 180 grit sandpaper to give the adhesive something to bite into.

Apply top sticker first. Centralise it, lock in place with masking tape. Cut 50mm off the backing paper, smooth that one off, lift the whole sticker up, peel all the backing paper off, then gradually smooth it on starting from one side, applying it at an angle (so you don't just chuck it down flat).

Then the back - same technique. The back will overlap the top. Looking to get a few mm overlap at the top, and to run 2-3mm under the bottom as well. It's not a lot - just enough - get this automatically if you centralise the sticker.

Then the two ends.

Left hand side - cut out the holes for teh XLR connectors with a scalpel (after applying the wrap).

Consider heat gun application on edges to encourage adhesion, if this is suggested by your vinyl wrap supplier. Certainly not before - else they will stretch. Do not heat gun whilst applying as they will stretch and distort.

# Apply the corner castings

Print the corner castings. There are five different parts. Two of each of four corner castings, plus four of the locks, 12 pieces per container in total.

The back corner castings have more material in them, the front corner castings have cutouts for the screen.

The lock parts only go in the castings on the top. These need to be glued in at the same time the casting is glued on so that there is no dried glue stopping it fitting it in. Then masking tape to keep it square while drying.

Clean up any overspill, especially in the bottom negative feature. i.e. with the bottom corner castings, don't allow the sealant to spill into the bottom receptable where it will lock together with the box below.

After gluing, while drying, place in normal orientation on a flat table or floor, so you don't lock in any twist or strain.   

(to do add images)

Wait 24 hours for adhesive to go off, or as per manufacturer recommendation.


## Captive nuts

Fit the two captive nuts into the square holes. Glue 3d-printed cover piece on top using same glue as for corner castings (Stiks like). Attention: do not get any glue into the captive nut (don't make it solid!) or its threads. Hold the cover pieces in place with a clamp will setting. Align them to the edge.

## Front screens

Take the 995mm by 420mm PETG that you ordered and laser cut two screw holes, one on each of the short sides (DXF supplied). You could order these sheets precut and drill the hole if you do not have access to a laser. We ordered them precut and lasered the holes.

Note these are not on the centre.

## Magnetic tape.

Tape is fitted to the edges. (note we use two polarities to avoid the 3mm offset we found we got with single polarity tape on both parts) - the two polarity tape is self aligning (todo add picture)

Attach first to the raw lumex (remove protective screen from the side the magnetic strip goes) - polarity A and polarity B. Put the B on the plastic, and A on the metal. They must all be the same for interchangability.

Apply top and bottom long edge side of the screen is applied first 995mm. Note the screw holes are not centered, which makes a top or bottom but not a front or back (vertically asymmetrical - i.e. apply the magnetic tape on either side, and then work out which side is now forced to be the top).
Then add the end pieces to suit the gap, leaving minimum gap.

Use a brayer roller to ensure good adhesion.

Cut two polarity A strips to 420mm, and then place onto the screen. Note that the joins are intended to be in a different place. 
Then lay down the tape magnet-to-magnet again for the long sides, and cut to ensure minimum gap.

Then lay the screen into position on the container with the backing in place. loosely fit some long bolts through the holes. Then lift it up and peel the backing whilst it is in place. Peel out from one strip at a time. To top and bottom and then end and end or vice versa. This keeps the alignment

## Install Torx security screw
TR25 M5 by 16mm (We got away with M5 x 15mm, M5 by 13mm absolute minimum length possible we think)




## Electrics

Box ready for lights and power and networking.

### Bill of materials - Electric

DC power board
XLR format powercon panel socket (20a)
XLR format RJ45 pass through
12V-24V Light strip (24V, 3000K, SMD2835, IP20, 120degree beam angle, 6 LED per 25mm (240 LED per metre) Self adhesive. 950mm 1off per container.
1300mm of hookup wire 0.5mm^2, red   (16x 0.2mm strands)
1300mm of hookup wire 0.5mm^2, black (16x 0.2mm strands)
cable tie mounts RS 865-9701 (7 on bottom, 5 on the side/top) 13 off per box. Fire retardant nylon.
cable ties are nylon (fire retardant)
- black 100 by 2.5mm is RS 233-499 bag of 1000
- natural 100 by 2.5mm is RS 811-1690 bag of 1000
- black 150 by 3.6mm is RS 233-500 bag of 1000
- natural 150 by 3.6m RS 492-0453 bag of 1000
M3x10mm countersunk screws, 4 off (two per XLR connector)
Powercon assembly heatshrink with adhesive is RS PRo 481-1832, 50mm length
625mm of hookup wire 1.0mm^2 red RS 763-7602 (H05 insulation)
625mm of hookup wire 1.0mm^2 black 763-7595  (H05 insulation)

RJ45 cable - custom length cat5 minimum End to End fully built, 615mm overall length. 
network switch power lead cut to 300mm, strip 5mm from the ends.
network switch, 5 port, 5V supply.
velcro 

600W 24V power supply (one per two boxes)
IEC connector pair, 
mains cable H05 standard (not H03)
2 core 1.5mm^2 cable

DC power board fixings:
standoff M3 by 8mm RS 105-8173 4-off
M3 nuts standard
M3 washers RS 560-338 4-off
M3x6mm panhead screw for fixing standoffs to the box. Optional upgrade - torx security drive (since accessible from outside the box)


Experiment Tray fixings

M2.5 standoffs for raspberry pis (4 per pi x 4 expt = 16 off per box)
M2.5 nuts 16 off
M2.5 washers 16 off

Experiment PCB
standoff M3 by 8mm RS 105-8173 (4 per experiment, 16-off
M3 nuts 
M3 washers RS 560-338 4-off


### Prepare floor of box

Using container component floor jig (DXF supplied - move left saddle 30mm!)

mark cable tie mount positions with marker pen

mark network switch location with marker pen

centre-punch through the holes for the stand offs for the DC power board

remove jig

Drill the standoff holes (drill diameter 3.2 - 3.5mm, the larger size gives some wiggle room.)

### LED strip

Solder 1300mm hookup wires to the light strip at one end, red to positive, black to negative.

Do not tin ends that go into the terminal block (solder creep).

Put kapton tape down first at either end of the strip, to avoid short circuits.

Apply the light strip just behind centre, so that there is no inteference between the wires and the central rivet in the end cap.

Hot glue over the end terminals where the wires are connected.
lift wires, blob of hot glue.
push wires into hot glue right where they terminate on strip
add more glue on top, smooth with a wetted, gloved, finger.

Apply self-adhesive cable tie saddles (there is a 4mm countersunk rivet hole in them, but we'd end up with the rivet on the outside,so reserve riveting for the middle cable tie mount on the experimental tray which is heavily loaded - the others don't need it).

There is a template for the floor (DXF supplied), for the end cap it is middle and ends on top and back corners.
(todo add images from whatsapp)

Cable tie application: there are two lugs on the cable tie mount. 
The lighting wires are small, so use cable tie through one lug
For the ethernet cable and power wire in the base, put cable tie through two lugs


### XLR power socket assembly

Strip 5mm at each end of the 635mm 1.0mm^2 hookup wires.
Solder the 625mm hookup wires to the socket Black to earth, red to neutral
50mm High shrink heat shrink with the resin.
two cable ties for security if not using adhesive heatshrink

### XLR connectors

Use M3x10mm countersunk screws, currently with pozi drive but drive is user-preference (must be countersunk head though).
mount XLR power assmebly with wires, and the RJ45 socket.

#### Mount network switch

2 strips 75mmm long
hook to container, loop to the switch.
on the underside of the switch there are square corner marks. line them up so that the strips are running parallel to the folds of the body (parallel to the long side of the box). See floor template for network switch position (DXF supplied)

### Mount DC power board

Attach standoffs to the PCB. M3 by 8mm RS 105-8173
M3 nut, M3 washer.
put box on the back, put one screw through to start it, then the one on the diagonal.
Start the rest of the screws to ensure they align. IF not, try loosening the standoffs on the baord. Else, ease the holes in the floor, but do NOT force or else you will end up cracking the PCB board.
If ease the holes, use washer.

### Complete wiring

Route wiring through saddles, fix power wires from XLR power socket into 24V in on DC power.
fix lights into 24V terminal blocks.
fix network switch power wires into the 5V at the opposite end - note white stripes usually mean positive terminal - but check carefully! Also, note that your network switch may be 9V, 12V or something odd - ensure you order one that is 5V or 12V or 24V or supply a DC-DC convertor in-line.

### Ready for trays

## Trays
2500 by 1250 Sheet 1.5mm 1050 grade
Cut into four even pieces lengthwise, so 625mm by 1250mm. Each slice gets you two trays. DXF supplied for laser cutting, including cut lines where the folds go.

### Folding

There is a 3mm cut wherever a fold is needed, four down and two up. All 90deg.

Folding order.

Feet first one side (same time)
Then legs that side
then other feet (same time)
then other legs
then tops.

Included in the DXF, which will vary per experiment, will be the mounting hole locations for the experiment and the electronics. This will be mostly experiment dependent, but it can be done after the folding. Align laser to marker on the centre of the tray (measure from tray corners on the diagonals) so long as you are not too close to the turned up edges, but they need a clearance space for the electronics in the centre of the box - given that any particular tray could be used on the left or right side of a box, eventually as trays get mixed and moved for maintenance.

add 8 self adhesive rubber feet (RS 236 509)

In terms of cable tie mount positions, there is a jig prepared for the spinner experiments; although the holes are marked on the jig for the PCBs need to be lasered to get the accuracy.

Recommendation - ensure that PCB mounting holes are on a rectangular pattern so that you can drill from either side if you are using a manual drill.

Laser a big hole for feeding through cables from underside, and protect cables from the sharp edges with a grommet. Choose grommet to suit panel thickness.

We used the bigger, lower profile of the two we bought. 34mm hole? RS 190-1975

Print corner cable cutout protectors, and superglue onto all four corners. (STL will be supplied) need on all four corners to protect camera cables, and the light power supply. Black PETG



## Camera mounts:

5mm clear acrylic, and 3D printed PETG,

1/4-20 screws by 3/8th.

Camera mount is clinch nutted, and so was the spinner (4 + 3 nuts) - camera probably universal, but experiment mount is not.

stand-offs done in same way as the main board.

Todo - photograph the current layout!


Arduino cable of X length USB A to micro
USB-A to USB-C cable  of X length
DC power cable barrel jack one end of X length, bare terminals the other - 
C920 logitech camera
USB microphone and USB A extension

RJ45 custom cable:
overall length end of plug to end of plug 760mm (check this!)

DC cable 785 from barrel jack tip to end of wire. 1.0mm^2 wired, 5mm strippred.
drill out end of barrel jack plug, solder wires, heatshrink power wire inside the barrel jack, heatshrink over the top of the whole plug to cover the modified end.

4-6mm 3:1 heatshrink for the inner one? 12mm 3:1 for the outer?

NOTE DC wires to motor in spinners were 500mm but really needed 550-600mm overall.


### Note on wire ends going into terminal blocks

If you don't tin, the wires will fray. IF you tin them you get solder creep. Solution - apply a square crimp. But for some connections like only going to go in once or twice so we are not currently doing this (e.g. lights and power are done once at assembly time).


## Prototype and improved version differences


## Assembly, operation, maintanance

## Construction time, and tools required as well.


## Tools list

- Whitney punch. 4mm (or imperial equivalent)
- Sanding block, 180 grit (or sheet metal deburring tool as optional extra to this)
- Clinch nut press tool (manufactured in house) - can by a commercial "clinch nut installation tool" that is closer to what a riv nut tool does (pop-rivet gun style)
e.g. [clinch nut installation tool](./img/clinch-nut-installation-tool.png). Our in-house basically a punch you load into a pillar drill and use that to press.
- Rivet gun M12 BPRT-201X
- sheet metal clamps 4 off per box you wish to be working on at a time (we ordered 20) (TODO part number ....)
- Cleco sheet metal pins for 4mm holes, and application tool. 6 off (enough for two per each of the three sides of the end cap being riveted) 
- 3D printer
- brayer roller
- laser cutter
- guillotine
- hydraulic folder
- TR25 Torx security screw driver
- heat gun for the stickering

TODO - when working out BOM, work out quantity break points that make sense for ordering, e.g. if we want to make 5/10 boxes, order this amount of stuff. Whatever seems sensible based on MOQs.


