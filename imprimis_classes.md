# Imprimis Class Improvement Plan
Elijah S Cole, 2022

*Game design is a gordian knot. Something can be simultaneously underpowered and overpowered.*
*Pull one loop of the knot and a superficially unrelated one will come undone.*
*Everything is connected in ways that can't be predicted, only explained after being observed.*
*Think Braess's paradox.*

## Gameplay Loop
*The gameplay loop is the atom of game design.*
Second to second the gameplay is what will dominate the player's attention.
All effective game dev starts by determining what the gameplay loop should be.
Imprimis' gameplay loop will undoubtedly involve shooting enemies and modifying terrain.
Games live or die on whether they got their gameplay loop right, so what exactly this loop is and how the classes function within it
must be a constant consideration and topic of discussion.

## Class Balance
Each class should have a specific role to serve in the basic gameplay loop.
Currently, Soldier is the strongest class yet is boring, while Demo and Engie are more interesting but feel relatively weak.
The reason Soldier is boring is that he has no way to modify the environment.
All classes need to have a way to interact with the destructable environment, or perhaps even multiple ways.
We should consider giving the soldier a way to break blocks, and then balance the other classes from there
I like the overheating-based ammo-stand-in system, it's interesting and unique and it works.
That said it's unorthodox so it will likely interact with other FPS systems in unpredictable ways. In fact, it probably already is.
How it interacts with everything else is something to keep in mind at all times.
*A round-based respawn system would make individual lives feel more meaningful,*
*and thus make any advantage a class has over another also feel more signifcant.*
*Though this would also make any differences in balancing more stark in contrast.*

## Engie
*The Engie's role in the gameplay loop is to modify the terrain to further enable combat.*
The issue with Engie is this: placing blocks isn't useful enough on its own to justify playing him.
To fill his role effectively, he needs a way to break blocks too. Simply placing blocks feels like not enough.
He might need a better weapon too: considering that combat is an integral part of the gameplay loop, 
restricting the Engie to a secondary weapon for offense leaves him feeling like a non-class.
There's also possibly an OP Engie strat:
By spamming blocks at chokepoints, the engie can create raised no-man's lands that impede enemy movement to allow for easy kills.
It's a question worth asking whether we should lean into or away from that.
A new weapon that's most effective at short range would help the engie to blockspam. 
These blockspam traps restrict sightlines and thus favor closerange combat.
For this reason Engie is also a candidate for a counter to the Soldier, whose railgun favors ranged encounters.
Change ideas:
	-Needs a way to break blocks, must be less effective than the Demo
		-Ideally also more precise than the Demo
		-Maybe he should have a short range trench shovel?

## Demo
*The Demo's role is to break blocks to open attack routes or destroy enemy cover, and to counter the Engie.*
Potential issue: the Demo fails his core role in that he can't break blocks as fast or faster than the Engie can place them.
I'm not sure whether this is a real issue, we need to do some tests on this.
As it stands, Demo *can* break the environment but anything more than superficial damage requires significant time and attention investment.
The cooldown on the demogun, which is both his block breaking tool and his primary weapon, means he can't use it to break blocks without
leaving himself open to attack and significantly reducing his ability to fight. 
This isn't neccessarily a bad thing as if this weren't the case Demo could be OP, but it's something to keep in mind.
A route to consider is giving the Demo more ways to interact with the environment or kill things.
His primary weapon doubling as a blockbreaking tool might be too restrictive.
Change ideas:
	Sticky nade gun
		-Lifted from TF2, if it ain't broke dont fix it
		-Sticky spam was a lethal noobcannon in TF2
		-But sticky spam did help TF2 demoman stand toe to toe with the TF2 soldier, who was an objectively stronger class

## Soldier
*The Soldier's role is to muscle into enemy territory and to score kills.*
Soldier is the most powerful class since his primary is an instant kill near-perfectly-accurate railgun with very high fire-rate.
This weapon might be too OP.
Even though the Soldier might be OP, he also is too weak in that he can't modify the environment.
He needs both a nerf and a buff.
The Soldier needs a signifcant downside. The TF2 soldier had extremely slow movement speed 
and truly lethal weapons or classes in tactical shooters often come with some kind of movement penalty, 
so that could be a good place to start.
Change ideas:
	Short range trench shovel
		-Needs some kind of downside, maybe a prohibitive cooldown is a good start
	Grenades
		-Limited uses per life would work well with a round-based match system
		-Could be challenging to code?
		-Needs to be balanced carefully. 
		-It should be able to make large enough changes to the environment to feel meaningful
		-But can't be a fucking nuke either
		-Maybe it shouldn't deal damage to enemies, only terrain?
	Modification or replacement of railgun
		-Railgun is possibly OP
		-Changes or replacements to it are an avenue to explore
	Slower movement speed
		-The Soldier needs a significant downside so he isn't objectively the best class
		-Slow movement speed is a common goto to nerf powerful characters in other games
	
		


