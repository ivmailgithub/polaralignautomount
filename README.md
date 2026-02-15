# polaralignautomount
claude &amp; gemini prompt:using example designs at https://github.com/OpenAstroTech/OpenAstroExplorer and   https://astrophiloslab.com/; https://www.printables.com/model/784937-am3-electronic-polar-alignment/files  design a   motorized cam system that can take higher payloads than 5kg, specifying:  ... tab in gemini adds a bunch of mech engineering stuff.  

After an afternoon playing around w/ claude and gemini burning up my freebies ... LLM actually can't do cad drawings not in their training data which is mostly text; papers docs etc.  I suppose if someone wanted to burn up 100million in compute scanning every cad drawing on the internet and learn mechanical engineering it would be done .. but i think that 100million is spent on porn pics not engineering cad.  It does generate stl model files ... the claude generator html pushed up generates the mockup of the build.  Gemini defaulted to 2.5flash this afternoon and all the stl files were just slabs .. no design openscad style python generator actually.  Last year the printNC guy did a gpt3 mechanical design for the x/y axis which was really neat .. maybe if you were shipping it out to space .. but everyone else just filled the beam w/ granite epoxy and ground the top flat.

so the two ai's settled on a ball screw design w/ nema23 motors ... huge  .. i mean i'm going to cast concrete to do the rotation and cnc the alt ... but the little 3dp models will be for the seestar50/dwarf3's

claude wrote the alpaca driver again ... gemini3 didn't use many api calls; actually low for the chat; claude burned up my daily immediately

so i'll test the stl models and mock up for the seestat50/dwarf3's.   No ai model actually stopped the design w/ a 100 harmonic drive costing more than the scope .. it just did it.   i actually have some 1604 ball screws around from the cnc build...but this is going to be a monster .. i kept asking how is a nema23 mortor and 6" ballscrew/pillow pivot bearings going to fit? make me a schematic assembly .. and both just generated a stl model file of a nema23 motor and a ball screww assembly....

20260119 mlastro adds sas66 and PA!!
20260215 .. happy new year ... https://arxiv.org/pdf/2508.00843v1
https://blog.adafruit.com/2026/02/14/from-pdf-to-lbr-using-deep-think-to-write-custom-cad-parts/
so still slabs and still llm's .. not the new vision llm on objects you would think cad drawings could be trainable w/o extensive labelling
