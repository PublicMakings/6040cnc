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

#### Terminology

Tabletop mills are often listed with a four-digit number like 6040 (~24" x 15.5").
^ this refers to the XY work area in cm. 
Motors designated as 57 are equivalent to NEMA 23.

#### Possible Features

Axes - minimum of 3. The fourth axis is rotational and allows for lathe-like milling of cylindrical objects.  
Spindle -  power is listed in watts. Fancier spindles have more power and are water cooled.  
Slides - rod vs linear rail
Drive - trapezoidal vs ballscrew

#### Additional Considerations

Lots of folks have [done this before](http://www.eevblog.com/forum/reviews/china-cnc-6040-setup-testing-review/?PHPSESSID=0521816f3f32ad12d44d4c11fb0a35c8), 
so we don't have to go into things totally blind. Many reviewers indicate that the control systems that come with these
machines are no good - you'll hear a lot of complaints about the dreaded [blue board](http://drkfs.net/REVERSESTEPPER.htm) (which I did not end up with). I also picked up a [TinyG](https://www.youtube.com/watch?v=In9Q_R0Nui8) controller board just in case, but I haven't had to use it yet.

### Purchased!

#### eBay

When I finally decided to take the plunge, I made sure to read all the
fine print on my seller's eBay page. They had a 99% approval rating, but
I was still concerned when I noticed that, while the variable frequency
drive (VFD) was rated at 1.5kw, the spindle was not rated at all.

When I emailed the seller to check on this discrepancy, I was assured
that both items were rated at 1.5kw. I was also offered a chance at a
discount if I purchased the item outside of eBay. I wasn't dumb enough
to fall for that, but I was dumb enough to continue working with the
seller.

Despite my reservations I made the purchase, and sure enough, the
spindle I purchased was rated at 800w. A long email chain ensued, and the seller
wouldn't budge until I started an official complaint through eBay. I was
eventually offered $100 off which I accepted, because I really didn't
want to send the whole thing back. All told I'm happy with how things turned out.

#### Assembly (WIP)

Place X axis beam in Y axis brackets. 
Use a non-metallic mallet to tap into place to avoid stripping tapped holes. 
Bolt from sides and bottom. 
Attach motors. Take care to orient each wire harness towards its
corresponding cable run, and orient each standoff block to allow easiest
allen key access.
 
#### Coolant (WIP)

Water cooled spindles systems should use distilled water with an anti-corrosion additive. 
I picked [Inhibited Propylene Glycol](https://en.wikipedia.org/wiki/Polypropylene_glycol) due to its
low-ish toxicity. You mix it with water (and I must admit I just used the tap). You can get the stuff at Napa auto.

A pump came with the 6040, but you still need a reservoir to hold the
coolant. I made mine out of a plastic bucket and some panel-mount barb
fittings: 1 x [BHU2204](http://quickcouplings.net/osc/product_info.php?products_id=1080&osCsid=8e12c1e2b70df5345fca6878b4a5c1a3) 
and 1 x [BHU2206](http://quickcouplings.net/osc/product_info.php?products_id=1081). 
Beware the aluminum barbs that come with the pump - mine let
go in the middle of a cut and sprayed coolant all over. Now that
barb is reinforced with hose clamps.

One remaining issue: my pump does not always turn on when I hit the
switch. I think the problem is on the pump side, so I may need to
replace the switch.

#### Lubrication (WIP)

Planning to try pneumatic oil for ballscrew
lubrication. There appears to be much debate on the best solution
(grease vs oil etc.). I'll also use a standard buckethead vac for dust
management.