# litefeeder

Semi-automatic passive printable/castable SMD tape feeder for LitePlacer (should work with other pick and place machines with some adjustments).

Watch it in action: https://www.youtube.com/watch?v=S1jxeCK4YC0

Discussion: https://liteplacer.com/phpBB/viewtopic.php?f=11&t=6272

![assembled feeder](foto/20191010_142134_result.jpg "assembled feeder")

## General notes

The design is inspired by alexavr2's alexfeeder https://github.com/alexavr2/alexfeeder https://alex-avr2.livejournal.com/210450.html and Karl Ekdahl's clockwork feeder https://liteplacer.com/phpBB/viewtopic.php?f=11&t=191 https://vimeo.com/144454867 http://www.knasmusic.com/diyeverything/pickandplace/tapefeeders.php . It is easy to manufacture as the former and requires no additional motion as the latter.

However i think the best cheap feeder design is that found in chinese machines. https://youtu.be/GKw8WOlGR84?t=131 https://youtu.be/y14pdfjYsyo But it requires software support, also i did not find the tape pulling rod assembly sold separately in chinese stores, and i think it should be problematic to attach such assembly to an existing machine.

### Pros

* No software support required.
* No extra machine head movement required.
* Easy to manufacture.
* Low cost (about $1 per feeder without labor).

### Cons

* Can only feed 8/4 mm (and maybe 12/4 mm) tape.
* Does not peel the film. You can use 150 - 200 g weights for this or make film peeler as in chinese machines or alexfeeder.

## Manufacturing

### Parts needed

* 0.5*5 mm flat spring. https://www.aliexpress.com/item/32826247091.html
* 0.5*8*25 mm coil spring (20 mm may be fine too). https://www.aliexpress.com/item/33054199528.html
* 1.2 mm round nylon line for the tooth (1 mm may be fine too, also you can use metal pins from headers, but it requires additional filing).
* Super glue.
* 7*11 mm nylon spacers for the axle (optional, not needed if you print directly). https://www.aliexpress.com/item/32868508973.html
* Two 2.5*20 mm wood screws.
* One M3*35 screw for machine head.
* One plastic cap for machine head. I use M3 acorn nut https://www.aliexpress.com/item/32963279606.html , but you can use (rounded) M3 long nylon nut https://www.aliexpress.com/item/33002921745.html for better height adjustment or print your own cap.

### Printing and casting

You can make it with your favorite technology, but bear in mind that it contains plastic spring and rubbing parts, so the plastic should be strong and durable to some extent. For example, UV photopolymers for LCD printers (at least that i have) do not meet this requirements (and also my printer prints quite slowly), so i had to cast my feeders from polyurethane (Smooth-Cast 305).

There are number of polyurethane casting tutorials on youtube, e. g. https://www.youtube.com/watch?v=YGZ2OeQinzw https://www.youtube.com/watch?v=DEVi0mEaJJQ

Platinum silicones are generally better, but they are incompatible with most photopolymers with notable exception of Gorky Liquid Simple https://gorkyliquid.ru/catalog/fotopolimer-dlya-3d-printera/fotopolimernaya_smola_gorky_liquid_simple_krasnaya_1_kg which is quite good by other parameters and also is the cheapest photopolymer in my country. If you can not purchase this resin, try finding another platinum silicone compatible photopolymer or use tin silicone. "Protective coatings" do not work, at least to me.

Release agent is mandatory, especially when pouring second half of the silicone mold over the first half. I use Ease-Release 200. When casting polyurethane, applying release agent before each casting is not necessary, but it is good to apply it every 2 - 3 castings.

Each mold lasts for about 10 - 20 castings (30 if you are lucky, but it slightly grows with each casting).

![printed feeder on the substrate](foto/20191008_134800_result.jpg "printed feeder on the substrate")
![printed and washed feeder](foto/20191010_170213_result.jpg "printed and washed feeder")
![preparing for first half silicone molding](foto/20191008_143555_result.jpg "preparing for first half silicone molding")
![silicone and release agent](foto/20191008_143624_result.jpg "silicone and release agent")
![first half silicone curing](foto/20191008_150000_result.jpg "first half silicone curing")

Remove excess silicone.
![removing excess silicone](foto/20191009_113055_result.jpg "removing excess silicone")
<!---![](foto/20191009_121346_result.jpg "scotch bucket for second half of the silicone mold")-->

Quick and dirty vessel for the second half. Apply release agent! And do not forget spouts and vents.
![](foto/20191009_121354_result.jpg "scotch bucket for second half of the silicone mold")
![scotch bucket for second half of the silicone mold](foto/20191009_122915_result.jpg "second half silicone curing")

Insert nylon axle if you have them (but it also works without it).
![silicone mold with nylon axle inserted](foto/20191010_142933_result.jpg "silicone mold with nylon axle inserted")
<!---![](foto/20191010_143008_result.jpg "silicone mold ready to casting")-->
![silicone mold and polyurethane ready to casting](foto/20191010_143254_result.jpg "silicone mold and polyurethane ready to casting")

Extract the casting after about 40 - 50 minutes, remove spouts and vents and wait about 24 hours for polyurethane to fully cure. Or you can bake it in an oven at 60°C as the manual says.

### Assembly

Drill 1.2 mm hole at about 45° at the end of the dog.
![drilling tooth hole](foto/20191010_134024_result.jpg "drilling tooth hole")

Glue 1.2 mm nylon line into this hole.
![gluing nylon tooth](foto/20191010_134341_result.jpg "gluing nylon tooth")
<!---![](foto/20191010_135132_result.jpg "cutting the tooth")-->

Cut the line flush to the vertical face. So we have durable nylon tooth that will push the tape by its holes. You can also use metal pins, nails or whatever you want, but i think nylon line is the easiest way.
![cutting the tooth](foto/20191010_135155_result.jpg "cutting the tooth")

Bend and cut the flat spring so its long side is 43 - 44 mm and short side is 2 - 3 mm.
![flat spring source](foto/20191010_135735_result.jpg "flat spring source")
![cutting flat spring](foto/20191010_142010_result.jpg "cutting flat spring")
<!---![](foto/20191010_142122_result.jpg "assembled feeder")-->

Assemble the feeder.
![assembled feeder](foto/20191010_142134_result.jpg "assembled feeder")
<!---![](foto/20191010_142910_result.jpg "silicone mold with nylon axle inserted")-->
<!---![](foto/20191010_155337_result.jpg "template aligned to the liteplacer")-->

It's time to ruin the table where the machine rests. But before this you need to determine the right Y position for your feeders. Insert some tape into the feeder and push the lever several times. Now you know that it works (hopefully) and the machine nozzle should be above the first part cell not covered by the spring. Try to find such Y position that your feeder pickup coordinate will be almost at the lowest allowed Y coordinate (it is -3 mm in case of the liteplacer, so aim to about -2 mm).
![feeders in place](foto/20191011_121257_result.jpg "feeders in place 4")
![feeder in action](foto/20191011_121424_result.jpg "feeder in action 1")
<!---![feeder in action](foto/20191011_121431_result.jpg "feeder in action 2")-->

Print the feeder_screw_template.pdf and stick it to the table (ideally, but not necessary, parallel to the X axis). So your feeders will sit on the table with exactly 12 mm pitch. 
![template aligned to the liteplacer](foto/20191010_155356_result.jpg "template aligned to the liteplacer")

Punch holes at the line crossings.
![punching center holes for the feeders according to the template](foto/20191010_161504_result.jpg "punching center holes for the feeders according to the template")

Drill 1.5 mm holes.
![drilling holes for the feeders](foto/20191010_162736_result.jpg "drilling holes for the feeders")
<!---![feeders in place](foto/20191010_170919_result.jpg "feeders in place 1")-->

Screw some feeders.
![feeders in place](foto/20191011_121147_result.jpg "feeders in place 2")
<!---![feeders in place](foto/20191011_121207_result.jpg "feeders in place 3")-->

Invent some reel mount and film peeling mechanism.
![reel mount and film peeling mechanism](foto/20191011_121715_result.jpg "reel mount and film peeling mechanism")

Profit!
