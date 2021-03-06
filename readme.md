### Getting Started

#### Rationale

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

#### Suppliers

You can find full kits or just mechanicals (gantry with no motors, spindle or
electrical control) on Amazon, Ebay and Aliexpress. I was surprised to
find that Aliexpress was not the cheapest route. A few sellers
maintain warehouses in the US, but shipping on heavy items can still be
pretty pricey. [This site](http://www.delftplate.com/?k=6040%20cnc%20router) 
helped me compare search terms on ebay to find the best deal. I searched for "6040 CNC".

#### Specs (What I Purchased)

 * Work Area: 60cm x 40cm
 * Motor Size: 57 / NEMA 23
 * Axes: 4 (XYZA)
 * Spindle: 800w, fluid-cooled
 * Controller: Parallel-based (so I can use [LinuxEMC](http://linuxcnc.org/))

#### Manufacturer(?)

After I purchased my rig from eBay and started using it I did some
repairs. This exposed manufacturer part numbers, which brought me to
[this site](http://www.omiocnc.com/x4-800-usb-4a-cnc-desktop-engraver.html). I
can't vouch for the site personally, but it certainly looks less sketchy
than the eBay sellers (who are probably just selling outdated/knockoff versions
of the OmioCNC product). These kits come with some nice extras, like a
tool touchoff sensor and a USB-based controller. The tradeoff is that
you're looking at ~$300 for shipping from China and need to find/purchase your own compatible machine controller software.

#### Additional Considerations

Lots of folks have [done this before](http://www.eevblog.com/forum/reviews/china-cnc-6040-setup-testing-review/?PHPSESSID=0521816f3f32ad12d44d4c11fb0a35c8), 
so we don't have to go into things totally blind. Many reviewers indicate that the control systems that come with these
machines are no good - you'll hear a lot of complaints about the dreaded
[blue board](http://drkfs.net/REVERSESTEPPER.htm) (which I did not end
up with). I also picked up a
[TinyG](https://www.youtube.com/watch?v=In9Q_R0Nui8) controller board
just in case, but I haven't had to use it yet.

#### Acknowledgements

Special thanks to [Signal Culture]( http://signalculture.org/tir.html#.Vrny91LIPtU), where I was Toolmaker in residence in
January 2016. Debora and Jason at Signal Culture provided me with the space to get this
project started. If you are an artist who works with technology you should check their program out.
