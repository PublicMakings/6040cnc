### Driver Repair

#### Background

A little research shows that lots of folks are pretty down on these driver
boards sourced from China. I wound up blowing out an axis on the first
day I was using the mill for a couple continuous hours. As far as I can
tell this had nothing to do with my settings, as we were taking it nice
and slow with some soft wood.

Though opening the case technically voids my "warranty", I'm sure that's
not worth much given my conflicts with the eBay seller. Let's do it
for science!

#### Troubleshooting

Before you attempt these steps make sure you try the simple stuff, like
swapping cables on your bad axis with a good one (with the box powered
down of course). If this magically fixes the issue when jogging, the
motor and/or cable are not at fault.

#### Cracking the Case

Unplug all cables from the controller. Remove the
sheet metal screws and remove the cover. I still need to post a pic of
the interior - you'll see two big blocks, these are the power supply and
Variable Frequency Drive (VFD) that controls the spindle. There are also
four black units, one for each axis. Mine were labeled, but you can
always just follow the wires to the outside of the case.

#### Opening a Drive Unit

A drive unit opens just as easily as the case. I couldn't find any
issues on visual inspection, so I assume the drive chip is bad. Luckily
they are pretty cheap [online](https://www.digikey.com/product-detail/en/TB6560AHQ,8/TB6560AHQ8-ND/1730072), 
so I bought three. ~~I'll update this page if replacing the chip brings
the driver back online.~~ No dice on replacing the driver. Now I may try
swapping the other chips with a good drive unit, and after that I may
just buy a whole new driver from
[OmioCNC](http://www.omiocnc.com/x4-800-usb-4a-cnc-desktop-engraver.html).

#### TingG

I decided to throw out the crap original motor drivers and try the TinyG instead. I don't want to cut wires just in case I can find original form factor drivers that work, so I idetified the motor signal and power supply connectors as JST VH 3.96mm. Check out [this link](http://dangerousprototypes.com/blog/2017/06/22/dirty-cables-whats-in-that-pile/) to go down the rabbit hole on different connector specs.
