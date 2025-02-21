+++
date = '2025-02-04T12:54:33+01:00'
draft = false
title = 'Why should dungeons have factions?'
+++

Question mark?

It occurred to me only after writing up [Analysis of the Jakalla Map II]({{< ref "/mol-ohep/2025-01-31-analysis-ii.md" >}}) that I sort of naturally assumed dungeons should have factions. I'm 100% confident that I've read this somewhere, and it seems intuitively right. But why? And what should they do? I'll first try to give my own answer, probably based on half-remembered blog posts, and then try to give due credit by discussing what other people have said. 

Ok. Dungeons are big connected networks of rooms[^0]. Assumption: we don't want every room's form, connections, and contents to be completely random [^1]. Instead, we want verisimilitude in all but a few edge cases. The top floor of a tower having a long hallway that leads to an enormous wine cellar is baffling at the least. So we *want* some kind of structure to impose constraints on the form and content of dungeons. 

One structure is the physical - the constraints of the physics of the setting, and its resulting effects on the map. In a setting without high magic (or very calculated structural engineering), the above example of a hallway with room extending off of a tall tower is physically disallowed. It would crash to the ground. 

{{< figure 
    src="/images/Structurally-bad.png"
    alt="A doodle of a tower with an absurd room extending from the left side. Some trees below are in severe danger of getting crushed. "
    caption="This architect has never met a brick."
    >}}

So owing to the physical structure, the form and connections of the rooms can be constrained. 

This extends to following the rules of whatever map it is that is used. Some paths are free and easily traversable: wide, flat, etc. Some paths are blocked: locked doors, collapsed rooms, cliffs. Some paths are untraversable: walls. This means that any dungeon denizens that know about one another should be able to reach one another through free or since-blocked paths. 

Another structure is the historical. What happened in the past to make this place what it is? I don't think the answer needs to be long or complicated, or even be anything beyond "a wizard did it"[^2]. This constrains the form and connections of the rooms even further. "a wizard" could presumably have done anything, but if this dungeon is a sunken cathedral, it should have an altar and a nave and apse and such. Likewise, if this dungeon is a sewer, it should have sewage in it, and maybe a maintenance room, and probably a cellar or seven. 

But neither of these two structures necessarily say anything about the contents of the rooms. A sunken cathedral might contain an immortal archpriest riding a crab, but it may just as well be the home of naiads who settled there many years after the last worshipper left. This is because content is more malleable than form. Denizens come, and die. I think that this is where factions come in: they are a useful structure to impose on our dungeons to constrain some of the contents. Plus, the interplay between factions is a great playground for PCs to get involved. 

I think I want to clarify what I mean by faction. From that last paragraph, the implication is that factions are one of the major constraining factors in dungeon contents. So can we stock a dungeon entirely using factions? Maybe, if "generic dungeon entropy" counts as a faction - the oozes, spiders, ghouls, and rats that necessarily make up a nontrivial percentage of most encounter tables. Likewise, some *dungeons entire* count should then as factions, because they function as actors. 

I think that's probably a fine way to think about it. In fact, if I use these broad definitions, maybe I can sort of "stack" factions to determine the contents of a given area. Like so: 

{{< figure 
    src="/images/Faction-layers.png"
    alt="A sketch of layers of dungeon stacked on top of one another like lego bricks. "
    caption="Dungeon lego, if you will."
    >}}

This diagram should be seen as a cross-section of a dungeon. `Dungeon entropy` is everywhere, and also the most fundamental element, so it's the base layer. In part of this dungeon, a group of `lawless bandits` make their home. They've got a bunch of members who have formed a `cult`, so the cult occupies part of  their dungeon space. They also have a bunch of "tame" wyverns to use as mounts - partially in their space, and partially in a few roosting areas that are the wyverns' alone. 

In the other part of this dungeon a group of `goblins` have made their hideout. Awkwardly, a group of adventurous `archeologists` are also there - maybe kidnapped from a nearby ruin, or maybe desperately trying to avoid detection while completing their work? 

This is altogether a pretty vanilla example, but I think that by getting creative with what counts as a faction this is a pretty flexible approach to determining sources of denizens in a dungeon. In particular, although I listed very normal creatures (ghouls, spiders, etc) under dungeon entropy above, we could consider a dungeon entropy layer consisting of church moths, angel's wings, and maddening music emanating from the walls. The key thing is that these things are here *because this is a dungeon*, and for no other particular reason[^3]. 

Oh, right! I've been thinking of stocking in terms of *creatures*, but obviously there are also the tricks, traps, and empty rooms. I think we can assign these elements in part to the dungeon entropy layer (see also ["Tricks, Empty Rooms, & Basic Trap Design"](https://www.drivethrurpg.com/en/product/269764/tricks-empty-rooms-and-basic-trap-design) by Courtney Campbell on why dungeons should have traps), and in part to the various denizen layers. So maybe I broaden my definition of "faction" to also include all of the physical manifestations of the denizens that come with it - i.e. all dungeon content. That seems fine.  

Conclusion: factions are groupings of dungeon content that belong together, located in a specific area or areas. Dungeon content includes, but is not limited to, creatures, crawlies, and pit traps. We want factions because they give *structure* to the dungeon, constraining the number of things that could go into any given room. This structure is useful for GMs when making dungeons, but it must also be useful for players. Knowing that you are in a goblin warren instead of a mech factory is information that feeds into [the information-choice-impact loop](https://www.bastionland.com/2018/09/the-ici-doctrine-information-choice.html). 

### That Assumption About Logic In Dungeons

Right. The most-debated part of this whole business is certainly the assumption I made right at the very start: that we want some level of verisimilitude in the dungeon. By this I don't mean that a dungeon should be logical, or, gods forbid, *realistic*, but more that it should be internally consistent. Should it also be consistent with the outside world? Probably to some degree, but a lesser one. I think because the Mol Ohep sewers are so close to the surface of Mol Ohep, the consistency of the sewers should be pretty close to that of the surface. But something like the [Veinscrawl](https://coinsandscrolls.blogspot.com/2018/05/osr-veinscrawl.html) is explicitly and entirely disconnected from the consistency of the surface, and carries its own rules and logic. 

Campbell, of the above-cited [Tricks book](https://www.drivethrurpg.com/en/product/269764/tricks-empty-rooms-and-basic-trap-design), takes an especially strident tone against ecological realism in dungeons by arguing three parts, two of which are uninteresting (predation, zeitgeist). The third, however, is that 

> "monsters [...] are the physical manifestation of our fears and risk. [...] Vampires our fear of rape, the lich our fear of ancient rulers imposing their unending rule upon us, flesh golems the fear of what might come back if we were to raise the dead"

This, I think, is an interesting angle to approach the issue of dungeon content from. Monsters are supernatural manifestations of something in the subconscious; their presence doesn't need to make sense. Occasionally, it may even be better if it doesn't. However, I would argue that subconscious monsters need to engage with verisimilitude, even if only on a narrative level. A cellar complex with thirty rooms containing only djinni who do not know about each other for no good reason is baffling to the point of frustration. A cellar complex imprisoning the court of one djinn, all of whose members are convinced they are at home, because the djinn monkey's paw'd the wish of a rather bad-tempered wizard, has narrative verisimilitude and says something more about the danger of avarice. I agree that the *realism* of what the court members eat, where they get it, etc., is unnecessary at best. A wizard did it[^2]. 

The logical extreme of this style of dungeon is the [mythic underworld](https://mystical-trash-heap.blogspot.com/2022/10/on-dungeon-as-mythic-underworld.html)[^4]
, in which the dungeon is a creature governed by the dream-logic of the absurd. This could also be described by saying the `dungeon entropy` layer is especially thick. I have never played in a mythic underworld game, so I will simply say they exist and move on. 

The earliest reference I could find to the converse, realistic[^5] dungeons, comes in the form of Richard Gilbert's [Let there be a method to your madness](https://1eonline.info/d/dungeon.design.rational.htm), from 1977 and still available online (!). Gilbert's piece is primarily concerned with the form of the dungeon, without worrying too much about its modern contents. He emphasises the need for establishing the history of a place, so that the GM can figure out what the logical structure of all the rooms was. That sounds pretty similar to the physical and historical considerations I laid out above. 

The content constraint in this school of thought comes from [Gygaxyian naturalism](https://grognardia.blogspot.com/2008/09/gygaxian-naturalism.html), which gives us the ecology that Campbell was so concerned about - that spiders need to eat a certain amount of goblins to make webs. This is a simulations approach to the game that, at least in part, helps in creating a cohesive web of consequences for the player's actions. Burned down that mill? Price of grain goes up. Cut down the roots of the Great Tree? The pixies three levels up, who nested in its boughs, have all left.

I think the actions-consequence structure that naturalism gives is a desirable thing to have. There is a certain danger, in the mythic underworld, of losing yourself amongst the dreams and fancies of its mythos and become a passive observer to whatever it imposes on you. This danger does not generally exist in the naturalist dungeon, because in order for anything to happen, someone has to do something. And players hate it when nothing happens, so they will do things to make things happen. 

Nevertheless, the appeal of counting spider-calories is thoroughly lost on me. Perhaps I'll make the dungeon layer a little thicker in Jakalla, then. The modern factions can have the naturalism to make them make sense in the areas they control, and we can get a little weirder in between. I like that this implies that the dungeon is malleable, and is changed by its inhabitants. Want to make an area safe and comprehensible? Put safe and comprehensible things in it. 

As a collective, then, a faction is defined by not only its dungeon content (denizens, stuff, traps) but also by the logic, or lack thereof, it imposes on the dungeon. The dungeon around a dream cult can then be dreamlike and fanciful, even if over at the poachers next door it follows hard and fast food-tracking rules. 

This does broadens the definition of "faction" to perhaps a silly degree, because where colloquially it means "a guy and her minions" I've now lobbed in the entire *type of logic* that this guy's area follows. A better name for the logic, denizens, and stuff in (an area of) the dungeon might be something like *consistency set* - as in, the set of things that need to be consistent with one another, even if they're not necessarily consistent with the rest of the outside world. But I think "faction" works fine, tbh. 

### Wait yeah I was thinking about factions, not dungeon logic

Right. Having redefined "faction," why are we here again? Oh yeah! What do other people say about why dungeons have factions? 

[The Alexandrian](https://thealexandrian.net/wordpress/1686/roleplaying-games/keep-on-the-borderlands-factions-in-the-dungeon) succinctly states that factions bring life beyond the PCs to dungeons. They function as a brain-storming tool for the GM to rejiggle the contents of the dungeon between delves by being natural starting points for re-stocking. [Brian Rideout](https://deathtrap-games.blogspot.com/2024/05/how-we-lost-faction-play-and-why-it-is.html) of Deathtrap Games provides a similar perspective, although for him factions appear to be things PCs make, harkening back to Ye Olden Wargaming days. The faction wargame running in the background can then provide inpsiration for the GM's foreground game material. 

Lastly, here's a [cool faction generator](http://chaoticshiny.com/factiongen.php) I found in reading up for this post. I have no use for it atm, but it's cool!

[^0]: Graphs, if you will. Certainly someone has analysed dungeons using graph theory, but who? Graph theory is the math behind Jaquaysing, so it seems an obvious thing to do. And doing some googling, it seems, yes! We have [Melan diagrams](https://www.enworld.org/threads/dungeon-layout-map-flow-and-old-school-game-design.168563/) , which are graphs with one-branches squished down, and [Homicidal networks](https://homicidallyinclinedpersonsofnofixedaddress.com/2023/12/23/dungeons-as-networks/), the latter of which I may let loose on Jakalla at some point because the author kindly provides R code. 
[^1]: Some people do want this, or something like it - see also mythic underworld. Then this assumption obviously doesn't hold.
[^2]: Wizards! You've gotta love 'em. Fantasy's most convenient excuse for any given bullshit.
[^3]: In the same way that there are rats in the cellar because it's a cellar with rats in it. 
[^4]: philotomy.net appears to be offline. Unfortunately I couldn't find the original 2005 Jason Cone essay anywhere. 
[^5]: or *naturalistic*, as I found out in reading up for this piece

[[Top]](#top)