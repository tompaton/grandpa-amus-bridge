## grandpa-amus-bridge

Model of the traditional Chinese bridge constructed by Grandpa Amu

# Grandpa Amu's Bridge

I found this traditional Chinese bridge design and construction
captivating.  The interlocking pieces mean that no fasteners or glue
is required and it gets stronger under load.

[Construction video](https://www.youtube.com/watch?v=PYkgEf3eWqA) and
[more, because who can get enough](https://www.youtube.com/watch?v=iSPAK3mcI3c)

![Bridge from the side](photos/side.jpg)

![Bridge from the emd](photos/end.jpg)


## CAD model

First I created a CAD model using
[DeclaraCAD](https://declaracad.com/).

This worked pretty well as
there are lots of repeated parts, and by using the `Cut` operation,
mortises could be automatically created in exactly the right locations
for the tenons.

[bridge.enaml source](src/bridge.enaml)

![Rendered CAD model](output/bridge-render.png)

Transparency helps see the structure and joints:

![Transparent render](output/bridge-render-transparent.png)

I was able to export a [bridge.step](output/bridge.step) file which
could be imported into [FreeCAD](https://www.freecadweb.org/) to
generate a drawing.

![Technical drawing detail](output/bridge-drawing.png)
[Full page drawing](output/bridge-drawing.pdf)


## Scale model

### Materials

* 8mm x 1200mm Tasmanian oak round dowel (2 pieces)
* 6mm x 6mm x 1200mm Tasmanian oak dressed all round moulding (2 pieces)
* 2.5mm x 100mm x 915mm balsa sheet (1 piece)

There wasn't much waste, probably about 20mm left from each of the
round and square dowels.  Only 1/3 of the balsa sheet was needed.

### Tools

* Craft knife
* Mini-hacksaw
* Sandpaper

![Craft knife](photos/20200822_163449.jpg)

### Construction

Even though I created the CAD model and drawings, construction was
done by eye, cutting with the craft knife when it would have been more
sensible to make a jig to drill out mortise holes.

Rails were created by splitting the square dowel.

![First steps](photos/20200711_163831.jpg)
![Base structure](photos/20200717_223040.jpg)
![Side rails](photos/20200811_224754.jpg)
![Final assembly](photos/20200819_222255.jpg)

### Finished model

The final model would hold together without glue, but it's a bit
fragile that way and I've spent enough time assembling it, so I glued
it with PVA craft glue.

It was then finished with a few coats of shellac.

![Finished bridge model](photos/20200822_103315.jpg)
![Detail](photos/20200822_103328.jpg)
![Underside detail](photos/20200822_103346.jpg)


## Next steps?

* 3D printed plastic model
* Paper model
