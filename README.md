# GrowLight
This repository is for a plant grow light and lighting control framework.

DISCLAIMER
This project involves exploring ideas that fundamentally involve danger. If you use this information, you take your own responsibility to handle that danger. You are encouraged to take your own safety precautions based on your own informed understanding of the dangers here, as this topic is not covered and no warranty is made or implied of the safety or efficacy of the methods here.

DOCSPEC
Different lights and controls for them exist.

Here's an example set of hardware:

Growing lights- 

these are 2835 LED's. LED spec describes the mm size of the rectangle of the LED chip, at time of writing these are current generation brightest-in-mass-production LED's.  Basically per watt, the cheapest lighting.

https://www.amazon.com/c%C3%A1lidas-blancas-voltios-impermeable-SYNCHKG071316/dp/B013C2U0IO/

Power Supply-

To run a good number of the LED's providing your light, you need a good supply of power.  12V may not be that much, but at 600 lights per strand, that pulls some juice.  The initial prototype was done with insufficient power supply, and what would happen was that it would turn on for a second, run out of amperage, flash out, and then the amperage would build back up and the light would come back on- infinitely in repeat.  Get a supply that matches the amperage draw of your electronics, and ideally that has some capacity over it.  Most power supplies have a power rating that specifies the maximum efficient load, which is usually around 80% of your power supply's specified maximums.

here is a 30 amp power supply, that is listed as 'amazon choice' on amazon.
https://www.amazon.com/MENZO-Universal-Regulated-Switching-Computer/dp/B06VWV5YCH/

Building materials- 

pegboard (of the sort usually used to mount tools above a toolbench- this material comes in large sheets for cheap, breaks easily and especially neatly when pre-cut with a box cutter along the holes, cuts like wood or almost like cardboard with a saw, is durable enough to use generally for small structures, and the holes perforate it in neat 90 degree lines.  Also, you can get this with white faces or with wood grain and with many color options- I like the white stuff but all of them work)

Steel Plumbers Tape-

This stuff is a 3/4" wide tape with holes in it every inch, made of a soft relatively thin gauge of steel. normally, it's used to hang water pipes and attach them to foundations in buildings, but it is a versatile highly-usable material, great for lots of things. Very worth having around the house to be able to steel-reinforce a wobbly table leg with, discretely from the underside, and other such useful household tasks.

Paracord or industrial Twine-

This is a category of material where we are bombarded by too many examples of really good solutions to the materials problem of the age-old human invention of 'string'. While there are many recommendations about cool kinds of string to make in the modern world- you should get your own spools of glass fiber and kevlar twine if you are even curious about this, and probably you should get them anyway, and have them alongside cotton and hemp strings and fishing line and the rest- but for this, something like paracord or an industrial plastic twine of the sort to tie up buoys and small boats to docks, or clothesline, or some other such small-multifiber-line.  The multiple fibers is an important point in it, this increases line durability because the load is averaged out between N number of strands and if any one of them breaks then it changes to stretch of n-1 strands instead of being broken outright.

1/4" threaded rod, bolts, and nuts-

These are grouped together despite being 3 logical separate items- 'nuts', 'bolts', and 'threaded rod'.  threaded rod is a segment of 'just the threading off a bolt', and the 'nuts' are the small hexagonal pieces that spin on the ends to clamp things along the rod's length.

As materials, these have the great advantage of being the size of the peg holes in pegboard, AND the size of the holes in the steel tape (which is perforated by these holes every inch, matching the pegboard also).

