### Rationale

I'm one of the co-creators of [DIYLILCNC](http://diylilcnc.org/), a project that aims to make
CNC more accessible to artists, designers and makers. We started right
around the same time as Makerbot, and we all know now that cheap 3D printing
won out in a big way. CNC milling is harder, requiring more steps and
technical know-how. But it can also be more rewarding, as the resulting
objects preserve the character of the materials they are
carved from.

The first two DIYLILCNC kits were intended for folks that were willing to trade
some accuracy for cost/accessiblity. Now that those two designs are out in
the world, I got interested in purchasing a machine with a heavier metal gantry.

### Suppliers

You can find full kits or just mechanicals (gantry with no motors, spindle or
electrical control) on Amazon, Ebay and Aliexpress. I was surprised to
find that Aliexpress was not the cheapest route. A few sellers
maintain warehouses in the US, but shipping on heavy items can still be
pretty pricey. [This site](http://www.delftplate.com/?k=6040%20cnc%20router) 
helped me compare search terms on ebay to find the best deal. I searched for "6040 CNC".

### Terminology

Tabletop mills are often listed with a four-digit number like 6040 (~24" x 15.5").
  - This refers to the XY work area in cm. 
When referring to motors, 57 = NEMA 23.

### Features

Axes - minimum of 3. The fourth axis is rotational and allows for lathe-like milling of cylindrical objects.  
Spindle -  power is listed in watts. Fancier spindles have more power and are water cooled.  
Slides - rod vs linear rail
Drive - trapezoidal vs ballscrew

### Assembly  

Place X axis beam in Y axis brackets. 
Use mallet to tap into place (to avoid stripping tapped holes). 
Bolt from sides and bottom. 
Attach motors. 
  - Take care to orient each wire harness towards its corresponding cable run 
  - Orient each standoff block to allow easiest allen key access
 
### Maintenance

Water cooled spindles systems should use distilled water with an
anti-corrosion additive. I picked [Inhibited Propylene Glycol](https://en.wikipedia.org/wiki/Polypropylene_glycol) due to its
low-ish toxicity. Planning to try pneumatic oil for ballscrew
lubrication. There appears to be much debate on the best solution
(grease vs oil etc.). I'll also use a standard buckethead vac for dust
management.

### Additional Considerations

Lots of folks have [done this before](http://www.eevblog.com/forum/reviews/china-cnc-6040-setup-testing-review/?PHPSESSID=0521816f3f32ad12d44d4c11fb0a35c8), 
so we don't have to go into things totally blind. Many reviewers indicate that the control systems that come with these
machines are no good - you'll hear a lot of complaints about the "blue
controller." I also picked up a [TinyG](https://www.youtube.com/watch?v=In9Q_R0Nui8) controller board just in case, but I haven't had to use it yet.

