tour-sign

This is an automated sign indicating the time to (or time of) the next tour for open evenings at Nottinghack.

It's nothing special, but came about due to the current method of people just joining tours willy-nilly, and thus missing out on important details. By having a sign, we can get people together and give them a consistent experience in the future. Hopefully, this will also then lead to fewer misunderstandings about the Hackspace in general, and things that may otherwise be missed when joining a tour part-way through.

The actual physical part of the sign is laser-cut; SVG and DXF files can be found in the build folder. The circuit design and bom can be found under hardware, and the arduino sketch lives under src.

The software depends on AdaFruit's LED backpack library, and by extension their GFX library as well. One day, I might unpick that dependency, but that's not a job for now.

